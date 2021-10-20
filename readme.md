# React Native Tutorial for Beginners - Build a React Native App [2020]

## Sources
https://www.youtube.com/watch?v=0-S5a0eXPoc

## Setup

 * `node -v` : v16.5.0
 * `npm i -g expo-cli`
 * expo: install expo on iphone or android devices
 * visual code
   * install on mac
   * extensions :
     * React Native Tools : https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native
     * React-Native/React/Redux snippets : https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux
     * Prettier : https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
     * Material Icon Theme : https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme
   * settings : `"editor.formatOnSave": true`

### Xcode : 
   * install with app store
   * settings: xcode > preferences > locations Tab > Command Line tools: XCode 11.4.1
   * launch simulator : xcode > open developer tool > simulator
   * shortcut for paramters: # + D

### Android Studio:
  * install from web site: https://developer.android.com/studio
  * officals instruction : https://developer.android.com/studio/install#mac
  * TODO: problem in set PATH for fish/android (https://youtu.be/0-S5a0eXPoc?t=1291) 
  * configure > sdk manager> 
    * sdk platforms: lastest android: android 10 (latest stable)
    * sdk tools: a. sdk build-tools, a. emul, a. sdk platform tool, intel x86
  * configure for expo with https://docs.expo.dev/workflow/android-studio-emulator/ 
  * configure AVD manager > create > pixel 3a cause it s got playstore > lastest androide (10)

## Debug on VSCode
  * install React native tools:  https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native
  * Debug icon > create a launch.json file link in blue
  * choose react native > attach to packager
  * open new file .vscode/launch.json
  * run > add configuration > react native > debug application > ios > classic application
  * code > preferences > setting and search for React-native › Packager: Port change 8081 for 19000
  * don t forget to close the debug tab of chrome: http://localhost:19000/debugger-ui/

## Publish an App
  * first publish in expo with:  
    * a clic on "Publish or republish projet" in Expo left menu
    * or `$ expo publish`
  * fill infos
  * clic on publish
  * go on the terminal where we launch expo, because there some questions about account logging or creation: nicolas.trote@gmail.com  IkillXXExpoX
  * After that it will be publish on : https://expo.dev/@nicolastrote/DoneWithIt

## Shortcut
  *  + D : select <view> tag and after  + D for selecting and editing tags
    



## 1st App DoeWithIt

* `expo init DoneWithIt` > black
* `cd DoneWithIt`
* `npm start`



