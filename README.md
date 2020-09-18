
# react-native-shudan

## Getting started

`$ npm install react-native-shudan --save`

### Mostly automatic installation

`$ react-native link react-native-shudan`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-shudan` and add `RNShudan.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNShudan.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNShudanPackage;` to the imports at the top of the file
  - Add `new RNShudanPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-shudan'
  	project(':react-native-shudan').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-shudan/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-shudan')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNShudan.sln` in `node_modules/react-native-shudan/windows/RNShudan.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Shudan.RNShudan;` to the usings at the top of the file
  - Add `new RNShudanPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNShudan from 'react-native-shudan';

// TODO: What to do with the module?
RNShudan;
```
  