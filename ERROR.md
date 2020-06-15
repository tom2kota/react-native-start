# npm install errors

```
Expo DevTools is running at http://localhost:19002
Opening DevTools in the browser... (press shift-d to disable)
Some of your project's dependencies are not compatible with currently installed expo package version:
 - react-native-reanimated - expected version range: ~1.7.0 - actual version installed: ~1.9.0
 - react-native-screens - expected version range: ~2.2.0 - actual version installed: ^2.8.0
 - react-native-safe-area-context - expected version range: 0.7.3 - actual version installed: ^3.0.5
 - @react-native-community/masked-view - expected version range: 0.1.6 - actual version installed: ^0.1.10
Your project may not work correctly until you install the correct versions of the packages.
To install the correct versions of these packages, please run: expo install [package-name ...]
Error: Invalid sdkVersion. Valid options are 7.0.0, 8.0.0, 9.0.0, 10.0.0, 11.0.0, 12.0.0, 13.0.0, 14.0.0, 15.0.0, 16.0.0, 17.0.0, 18.0.0, 19.0.0, 20.0.0, 21.0.0, 22.0.0, 23.0.0, 24.0.0, 25.0.0, 26.0.0, 27.0.0, 28.0.0, 29.0.0, 30.0.0, 31.0.0, 32.0.0, 33.0.0, 34.0.0, 35.0.0, 36.0.0, 37.0.0, 38.0.0
Starting Metro Bundler on port 19001.

  exp://192.168.254.252:19000
```

``` 
// package.json

{
  "main": "node_modules/expo/AppEntry.js",
  "scripts": {
    "start": "expo start",
    "android": "expo start --android",
    "ios": "expo start --ios",
    "web": "expo start --web",
    "eject": "expo eject"
  },
  "dependencies": {
    "@react-native-community/masked-view": "^0.1.10",
    "expo": "^37.0.12",
    "expo-cli": "^3.21.5",
    "react": "^16.13.1",
    "react-dom": "^16.13.1",
    "react-native": "^0.62.2",
    "react-native-gesture-handler": "^1.6.1",
    "react-native-reanimated": "^1.9.0",
    "react-native-safe-area-context": "^3.0.5",
    "react-native-screens": "^2.8.0",
    "react-navigation": "^4.3.9",
    "react-navigation-stack": "^2.7.0"
  },
  "devDependencies": {
    "babel-preset-expo": "^8.2.1",
    "@babel/core": "^7.10.2"
  },
  "private": true
}
```

```  
Starting project at /home/kiskass/WebstormProjects/react-21
Expo DevTools is running at http://localhost:19002
Opening DevTools in the browser... (press shift-d to disable)
Some of your project's dependencies are not compatible with currently installed expo package version:
 - react-native-reanimated - expected version range: ~1.7.0 - actual version installed: ^1.9.0
 - react-native-screens - expected version range: ~2.2.0 - actual version installed: ^2.8.0
 - react-native-safe-area-context - expected version range: 0.7.3 - actual version installed: ^3.0.5
 - @react-native-community/masked-view - expected version range: 0.1.6 - actual version installed: ^0.1.10
Your project may not work correctly until you install the correct versions of the packages.
To install the correct versions of these packages, please run: expo install [package-name ...]

Stopping packager...
› Closing Expo server
Could not get status from Metro bundler. connect ECONNREFUSED 127.0.0.1:19001

  exp://192.168.254.252:19000
```