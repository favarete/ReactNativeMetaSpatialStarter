# React Native Meta Spatial Starter

This project provides a minimal implementation of the [React Native Community Template](https://github.com/react-native-community/template) 'Hello World' app, seamlessly integrated with the [Meta Spatial SDK](https://github.com/meta-quest/Meta-Spatial-SDK-Samples) 'Hello World' example for Android. 

Currently, integrating the Meta Spatial SDK with React Native can be challenging. This starter template aims to simplify the process and save you some hassle.

![QuestDemo.gif](QuestDemo.gif)

--- 

## How to Run

1 - Clone the repository:  
`git clone git@github.com:favarete/ReactNativeMetaSpatialStarter.git`  

2 - Install the dependencies from the main folder (_ReactNativeMetaSpatialStarter_)   
`npm install`  

3 - For development, run the bundler (this is needed for hot reloading during development)  
`npm start`  

4 - Now you can run the Android app inside your device or emulator. I don't use Android Studio, usually I build and run like this:  
From the android folder (_ReactNativeMetaSpatialStarter/android_)  
`./gradlew :app:assembleDebug`  
`adb install ./app/build/outputs/apk/debug/app-debug.apk`  

_If you want an AAB you can use_ `./gradlew :app:bundleDebug`  

5 - For release, you can skip step 3 and 4, and build everything into the apk running this:  
`./gradlew :app:assembleRelease`  

_If you want an AAB you can use_ `./gradlew :app:bundleRelease`  
