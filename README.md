# How to Run

###### Prerequisites

➜ Install Node 14 LTS

➜ <https://github.com/emtiajium/ielts-gibberish>

➜ Add Firebase to the Android project

> [OAuth 2.0 Client ID](https://console.cloud.google.com/)

> Enable Google Sign-In in the Firebase console

###### Clone the repo and install all dependencies

➜ `git clone git@bitbucket.org:sheenab/ielts-gibberish-android.git`

➜ `cd ielts-gibberish-android`

➜ `npm install`

###### Create your configuration and edit

➜ `config.json.text` > `config.json`

➜ `capacitor.config.json.text` -> `capacitor.config.json` 

###### Start the development environment

➜ `npm run serve`

###### Run the web app on browser

➜ <http://localhost:8080/>

###### Run the web app natively on Android

➜ Read [these](https://facebook.github.io/react-native/docs/running-on-device.html) and execute three task given below

> Enable Debugging over USB

> Plug in your device via USB

> Connect to the development server

➜ `npm run serve:android:anew`

➜ Open the project (`/android`) in Android Studio

➜ `cp ./java/strings.xml ./android/app/src/main/res/values/strings.xml`

➜ Sync project with gradle files

➜ Shift + F10

## Deploy the web app to the Google Firebase Hosting

➜ Install [Firebase CLI](https://firebase.google.com/docs/cli)

➜ Set config for the production
> config.json

> capacitor.config.json

➜ `npm run deploy:firebase`

## Change Log

-   `0.1.0`: User creation with Google authentication + Basic vocabulary functionalities 
