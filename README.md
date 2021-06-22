# Number Guesser - Read Me
A number guessing game built by React Native where the player chooses a number, and let the computer guesses that number. The guesses will then be displayed at the end of the game. 

## Installation

* Make sure you have `node.js` installed
* `sudo npm install expo-cli --global` to install Expo's command line interface globally
* `cd` into your project's folder, and `npm i` to install the required packages and dependencies
* Make sure you have Android Studio & Xcode set up for Android & iOS virtual devices debugging
* Make sure you have Expo app downloaded from the App Store / Google Play Store for debugging on the physical device
* `npm start` to launch Expo's client server, you can either click on `Launch on Android Studio`, `Launch iOS simulator` or use your phone's camera to scan the QR code to build the app

## App Flow

Welcome to Number Guesser! 

Pick a number, and the computer will guess your number! 

<img src="/public/assets/gifs/game_flow.gif" width="350"/>

The times of computer's guesses will be recorded, and an end-of-game screen will show. 

If you did not provide any number, an alert will pop up, and show you the range. 

<img src="/public/assets/gifs/no_number.gif" width="350"/>

You can clear the input number if you wish to change it. 

<img src="/public/assets/gifs/clear_number.gif" width="350"/>

If you lie to the computer of the number, a prompt will show you not to lie! 

<img src="/public/assets/gifs/dont_lie.gif" width="350"/>

## Tech Stack
This project used ReactJs, React Native, Expo, JavaScript and CSS. 

