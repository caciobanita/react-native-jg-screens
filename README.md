
# react-native-jg-screens

## Getting started

`$ npm install react-native-jg-screens --save`

### Mostly automatic installation

`$ react-native link react-native-jg-screens`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.jg.screens.RNJgScreensPackage;` to the imports at the top of the file
  - Add `new RNJgScreensPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-jg-screens'
  	project(':react-native-jg-screens').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-jg-screens/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-jg-screens')
  	```


## Usage
```javascript
import RNJgScreens from 'react-native-jg-screens';

// TODO: What to do with the module?
RNJgScreens;
```
  