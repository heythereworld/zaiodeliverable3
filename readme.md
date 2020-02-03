# Week 3 deliverable for Zaio Bootcamp

React Native - Net Ninja.
Nemesis Team - Chris Pretorius

# Description from Specification
Emulate Net Ninja's YouTube React Native playlist (Gamezone - review application)

# Bonus
16. Provide step-by-step instructions (numbered list) on how to deploy the application on both the App and Play Store
17. Implement practical 3rd party components and building 4 additional features to the application

# Step-by-step instructions
1. To publish your Expo app, first, you need to make sure that all your app.json configurations are set up. 
2. There are many properties that you can add, but only three are required: name, slug, sdkVersion. 
3. Click the Publish button in Expo Dev Tools.to publish your project. If you’re using command line, run “expo publish”.
4. You will get a link (like this: expo.io/@username/app-name) where two versions of the code will be generated for iOS and Android.
5. Every time you update the app, you will need to publish it again, and the changes will be reflected right away and available to your users.

# Step-by-step instructions (Android)
1. Run “expo build:android”.
2. You can either upload your own keystore or have Expo generate one for you. If you choose to have Expo generate one for you, make sure to back it up as you will need it to submit any future updates of the app, and without it you won’t be able to update the app anymore.
3. To back up the keystore, run “expo fetch:android:keystore”.
4. Your Android app will now start building. You can check the status of the build by running “expo build:status”.
5. Once your app has been built, you will be given a .apk URL of your Android app that you can download.

# Step-by-step instructions (iOS)
1. Run “expo build:ios”
2. The same way as Android’s keystore, you can either upload your own distribution certificate or let Expo handle it for you.
3. Your iOS app will now start building. You can check the status of the build by running “expo build:status”.
4. Once your app has been built, you will be given a .ipa url of your iOS app that you can download.
