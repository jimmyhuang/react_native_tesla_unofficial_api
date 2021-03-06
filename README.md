# Tesla Remote App

## Overview:
This is a basic mobile implementation of the official Tesla App, in which users can find out the vehicle state of their cars, such as charging status and odometer readings, as well as perform basic remote actions, such as flashing headlights or unlocking their car.

Learn more about creating this project at: [A Beginner's Guide to the Unofficial Tesla API](https://medium.com/@jhuang5132/a-beginners-guide-to-the-unofficial-tesla-api-a5b3edfe1467). 

## Demo:
General Demo

<img src="https://i.imgur.com/ViGxPQ0.gif" width="50%" height="50%">

Home Page

<img src="https://i.imgur.com/98VlAuG.png" width="20%" height="20%">

Vehicle Page

<img src="https://i.imgur.com/LcxD3Ug.png" width="20%" height="20%">

## Start the App:
* Clone this repository and then cd into it.
* Run `npm i` to download all dependencies
* After all the dependencies are downloaded and installed, type `react-native run-ios` to automatically open the app
* If there are any issues, please ensure that you have the latest version of XCode

## Troubleshooting:
* If you experience issues with the vehicle state not showing, it is likely due to the fact that the unofficial Tesla API does not wake up the car if it is in deep sleep. You will need to wake it up using the official Tesla app first.

## Acknowledgements:
* Created using Facebook's [Create-React-Native-App](https://github.com/react-community/create-react-native-app) 
* [Unofficial Tesla API Documentation](https://tesla-api.timdorr.com/)

