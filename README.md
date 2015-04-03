# GcalOpenStatus

Simple Google Calendar based opening hours script, ideal for restaurants, hotels, shops

## Installation
This plugin uses https://github.com/moment/moment for easy time and date manipulation in Javascript. So this needs to be included first. 

Copy the `GcalOpenstatus.js` from the `js` folder to your directory. Use the code provided below to load the plugin.

    <script src="../js/GcalOpenstatus.js"></script>

Then use the code below to initialize the plugin, you can choose any html element as the plugin replaces the html.

    <script> 
      $('your-element').gcalOpenStatus(); 
    </script>

## Usage

To make this plugin do it's magic you need to have a Google account and register as developer. More information here https://code.google.com/apis/console. When you are registered and logged in go to the Google Developers Console homescreen and create a new project, follow the onscreen instructions.

When you have created a new project go to the APIs & auth section. Use the search to enable the Calendar API. Last step is to create a new public API key for you project. You can to this in the APIs & auth - Credentials section. Copy the created API Key as we need in in our final step to make the plugin work.



