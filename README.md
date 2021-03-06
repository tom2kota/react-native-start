# react-native-start 0.6Gb
React Native Basic project setup

-------------------------------

## [Installing Expo CLI](https://docs.expo.io/get-started/installation/)

``` 
npm install -g expo-cli

expo whoami

expo register
expo login

```

- [fb-watchman](https://www.npmjs.com/package/fb-watchman)

- [Installing on macOS or Linux via Homebrew](https://facebook.github.io/watchman/docs/install/#buildinstall)

## [Create a new app](https://docs.expo.io/get-started/create-a-new-app/)

```
expo init
```

-------------------------------

## Initial setup

1) clone repo
2) ```npm i``` & alternatively: ```npm install --global expo-cli```
3) npm start and open [localhost](http://localhost:19002/)
4) connect Mobile device
5) setup **expo** app from AppStore
6) select **Tunnel** or **LAN** and scan QR code
7) check result http://localhost:19002/ & on mobile

    ```
    INFO
    11:21
    Starting Metro Bundler on port 19001.
    INFO
    11:22
    Tunnel ready.
    Info
    11:39
    Building JavaScript bundle: finished in 406ms.
    ```
    
    [http://localhost:19001/](http://localhost:19001/):
    
    ``` 
    React Native packager is running.

    Visit documentation
    ```
    

8) stop the bundler => *Ctrl + C*

------------------------------

## Installing Requirements


  - Homebrew (install first)
  - Node (with Homebrew)
  - Watchman (with Homebrew)
  - The React Native CLI
  - Xcode
  - [Java SE Development Kit 14](https://www.oracle.com/java/technologies/javase-jdk14-downloads.html)
  - Python 
  - NodeJS
  - React Native CLI ```npm install -g react-native-cli```



```
react-native --version

npm install -g create-react-native-app

react-native init rn-starter

npx --package react-native-cli react-native

npm start

npm run eject

```

-------------------------------

### references:

- [Semantic Versioning Cheatsheet](https://bytearcher.com/goodies/semantic-versioning-cheatsheet/)
- [Tilde](https://bytearcher.com/articles/semver-explained-why-theres-a-caret-in-my-package-json/)
- [React Native Directory](https://reactnative.directory/)
- [Online Editor](https://snack.expo.io/)
- [Setting up the development environment](https://reactnative.dev/docs/environment-setup)
- [Docs](https://reactnative.dev/docs/)
- [Publishing to Google Play Store](https://reactnative.dev/docs/signed-apk-android)
- [Use our step-by-step guide to get started with Expo in minutes](https://expo.io/learn)
- [Snack](https://snack.expo.io/)
- [React Native Instructions](https://aka.ms/ReactNative)
- [React Native - Environment Setup](https://www.tutorialspoint.com/react_native/react_native_environment_setup.htm)
- [Commands](https://medium.com/unpacking-react-native/react-native-cli-8e17281a3d7d)
- [Expo init](https://medium.com/@ralph1786/start-a-project-with-react-native-and-expo-cli-92df0fcf575c)
