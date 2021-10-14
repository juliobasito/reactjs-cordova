# reactjs-cordova

## Preresiquites :

Node and npm : https://nodejs.org/en/download/

Gradle : https://gradle.org/install/

Cordova : https://cordova.apache.org/docs/en/10.x/guide/cli/

## Getting started :

`npm install`

### Run app on browser :

`npm start`

### Run app on android (device or emulator)

Install Android SDK : https://developer.android.com/about/versions/12/setup-sdk

`cordova add platform android`

`cordova run android`

(You may have the following error during run : https://stackoverflow.com/questions/68387270/android-studio-error-installed-build-tools-revision-31-0-0-is-corrupted, 
you can fix it by changing d8 name by dx on your appData folder)

