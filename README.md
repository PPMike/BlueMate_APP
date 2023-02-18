# BlueMate_APP

####  This repo will contains our repository, now you need to follow the next steps to run the repository.

## 1. Step one: Download GitHub Desktop.

#### [GitHub Desktop](https://desktop.github.com)
#### Next login and select this repository
#### Now download all the files

## 2. Step two: Install expo.
```
$  npm install -g expo-cli exp
```
## 3. Step three: Install libraries.

```
$  npm install firebase
$  npm install expo-constants dotenv
$  npm install react-native-gesture-handler
$  npm install react-native-screens
$  npm install react-native-safe-area-context
$  npm i @react-native-community/masked-view
$  npm install react-native-gifted-chat
$  npm install @react-navigation/native
$  npm install @react-navigation/native-stack
```
##  4. Step four: Run the app.
```
$ expo start
```

## Extra:

####  If you want install Anroid Studio to test the apps on the computer:
####  [Android Studio](https://developer.android.com/studio)
####  On the three points, on the right upper corner you have to select *"Virtual Device Manager"*
####  Next *Create Device*
####  Next *Pixel 4* with Play Store this part is important
####  Next dowload the  Release Name *S* with the API Level *31*

#### Now after the *expo start* command press *a*


####  If you want to run the app on your cell phone dowload *Expo Go* on PlayStore or AppStore
####  On Android you have to scan the QR with the app
####  On IPhone you have to scan the QR with the camera

##  Possible errors:

#### If you get the nex error:
```
_reactNative.Keyboard.removeListener is not a function
```
####  Follow the next steps: [RemoveListenerError](https://stackoverflow.com/questions/68696600/reactnative-keyboard-removelistener-is-not-a-function)
####  Replace the code on MessageContainer.js
#### This file is in the next direction: BLUEMATE_APP/node_modules/react-native-gifted-chat/lib/MessageContainer.js
(ImageCodeReplace)[https://github.com/PPMike/BlueMate_APP/blob/main/imagen_2023-02-18_035853056.png]

 
