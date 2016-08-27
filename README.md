# automatedhome
A JavaScript application simulating house automation: pressing a button on a control panel would visually turn on a light, change the temperature or close the curtains.
It is based on an example from [Just Another Automated Home](https://github.com/marybeshaw/Just-Another-Automated-Home)

### Some constraints:
* The application must use jQuery
* The components must have HTTP based "server" interaction (use a static file for simplicity, data persistence is not required). For example, the heating component retrieves the current temperature from the server and also sends the desired one back to the server.
* The solution has to be extensible and documented, so that we can develop our own components that react to events

### Features added by Denny Ma:
* Updated the floor plan to [White House](https://commons.wikimedia.org/wiki/File:US-WhiteHouse-Logo.svg)
* Data persistence enabled. Room temperature set and saved on the web server.
* Room temperature is loaded with the value set dynamically

### Instructions on how to run the demo
* Follow the Instructions document in [java based web server](https://github.com/macongpeng/webserver)
* Copy the files to the root of the web server. The default root is html
* Start the web server. Hit the url of http://127.0.0.1:8081/index.HTML

### The screenshot of the demo
![The screenshot of the demo](https://github.com/macongpeng/automatedhome/blob/master/images/automatedhome.png)
