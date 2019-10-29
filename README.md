# MAHacksV

## Our project, KibbleCalc

Our project allows dog owners to calculate the calories that their dog needs per day. It also allows people to view real-time charts about the dogs that have been submitted to the website, or app. Our application is cross platform using cordova to be portable to the browser, Electron, Android, and iOS.

To run this project you will need to have Node.js, npm, and Cordova installed.

## How to Run in the Browser


Install npm packages from the root directory.

	npm install

Run node.js server from the root directory.

	node .

Add the browser platform to cordova, run this from the MAHacks subdirectory.

	cordova platform add

Run client side app with cordova from the MAHacksV subdirectory. This is to to start the UI in a browser window.

	cordova run browser

## How to Build as an Electron Application

Add the electron platform for Cordova from the MAHacksV subdirectory.

	cordova platform add electron

Build the electron app for your platform from the MAHacksV subdirectory.

	cordova build electron