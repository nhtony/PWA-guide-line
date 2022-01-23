# Progressive Web Apps - Complete Guide
This source code is part of Maximilian Schwarzmüller's "Progressive Web Apps - Complete Guide" course on udemy.com.

# How to Use
You need [Node.js](https://nodejs.org) installed on your machine. Simply download the installer from [nodejs.org](https://nodejs.org) and go through the installation steps.

Once Node.js is installed, open your command prompt or terminal and **navigate into this project folder**. There, run `npm install` to install all required dependencies.

Finally, run `npm start` to start the development server and visit [localhost:8080](http://localhost:8080) to see the running application.

# Manifest Configuaration

```
{
    "name": "Test", // Long name of app (e.g on SplashScreen)
    "short_name": "Test Test...", // Short name of app (e.g below icon)
    "icons": [
        {
            "src": "/src/images/icons/app-icon-48x48.png",
            "type": "image/png",
            "size": "48x48"
        },
    ], // Icons or app (e.g to be shown on homescreen)
    "start_url": "./index.html", // Which page to load on startup
    "scope": ".", // Which page are included "PWA Experience"
    "display": "standalone", // Should it look like a standalon app 
    "orientation": "portrait-primary",  // Set default orientation
    "background_color": "#111", // Background whilst loading & on SlashScreen
    "theme_color": "#3f51b5", // Them color (e.g on top bar in task switcher)
    "description": "A simple Instagram Clone, implementing a lot of PWA love.",
    "dir": "ltr", // Read direction of your app
    "lang": "en-US" // Main language of app
}
```
