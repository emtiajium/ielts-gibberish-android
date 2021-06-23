# How to Run

###### Prerequisites

➜ Install Node 14 LTS

➜ [OAuth 2.0 Client ID](https://console.cloud.google.com/)

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

➜ `rm -rf android/`

➜ `ionic build`

➜ `npx cap add android`

➜ `npx cap sync`

➜ Open the project (`/android`) in Android Studio

➜ Replace `MainActivity.java`, `strings.xml`

➜ Sync project with gradle files

➜ Shift + F10

## Change Log

-   `0.1.0`: ***
