# PWA-Budget-Tracker

This project will demonstrate knowledge learned during Unit 18 of class. Progressive web apps are designed to add additional functionality to an existing web app. 

Since we are starting with a working budget tracker I will be focused on turning it into a progressive web app.

## PWA Features to enable

### Offline Mode
Implementing this feature will allow the site to operate temporarily offline. Its possible to demonstrate this by using the developer tools built-in to Chrome.

This feature is made possible by creating a service worker. The service worker will be loaded when the browser opens the webpage. It will cache the app locally and make it possible to continue using the site, even when the internet is unavailable.

The service worker is a feature that is available on most browsers. 

### Background Sync
Once the app is able to work offline, we need to enable a mechanism for saving any changes offline. For instance when the user inputs a new expense, it will be cached in local browser storage, until the connection is restored to the internet. Also refered to as saving offline, its a feature that is available on most websites that people dont realize is happening in the background.


## Application deployed with Heroku and MongoDB Atlas.

https://limitless-brushlands-19435.herokuapp.com/