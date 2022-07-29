# Moovincool

React Native
Make sure setup React native https://reactnative.dev/docs/environment-setup. We Should setup yarn also https://classic.yarnpkg.com/en/docs/install/#mac-stable amd for ios, make sure https://cocoapods.org is setup.

The boilerplate provides an architecture optimized for building solid cross-platform mobile applications through separation of concerns between UI and business logic.

<p align="center">
  <img src="https://i.ibb.co/YZPPyXq/icon-Android.png" width="200">
</p>

### Folder structure

```
├── ...
├── __mocks__/
├── __tests__/
├── android/
├── ios/
├── src/
│   ├── assets/
│   │   ├── fonts/
│   │   ├── icons/
│   │   ├── images/
│   ├── components/
│   │   ├── bottomSheet/
│   │   ├── container/
│   │   ├── text/
│   │   ├── hooks/
│   ├── configs/
│   │   ├── language/
│   │   │   ├── en.tsx
│   │   │   ├── ...
│   ├── core/
│   │   ├── common/
│   │   │   ├── BlockCustom
│   │   │   ├── Button
│   │   │   ├── ButtonBack
│   │   │   ├── DateInput
|   │   │   ├── EmptyView
│   │   │   ├── FlastlistHorizontal
│   │   │   ├── Header
│   │   │   ├── IconButton
│   │   │   ├── ImageView
│   │   │   ├── Input
│   │   │   ├── ListBottomSheet
│   │   │   ├── Loading
│   │   │   ├── Popup
│   │   │   ├── Progress
│   │   │   ├── SearchBox
│   │   │   ├── StatusBar
│   │   │   ├── styles
│   │   │   ├── TextCustom
│   │   │   ├── ...
│   │   ├── helpers/
│   │   │   ├── index.tsx
|   │   │   ├── isNote8or9.tsx
│   │   │   ├── sizePixel.tsx
|   │   │   ├── sizeScreen.tsx
|   │   │   ├── Validation.tsx
│   │   │   ├── ...
│   │   ├── redux/
│   │   │   ├── action.ts
│   │   │   ├── reducers.ts
│   │   │   ├── store.ts
│   │   │   ├── ...
│   │   ├── utils/
│   │   │   ├── AppHelper.ts
│   │   │   ├── AppView.ts
│   │   │   ├── default.ts
│   │   │   ├── navigation.ts
│   │   │   ├── types.ts
│   │   │   ├── ...
│   ├── navigaiton/
│   │   │   ├── DrawerContent.tsx
│   │   │   ├── index.tsx
│   │   │   ├── NavigaitonType.tsx
|   │   │   ├── rootNavigation.tsx
|   │   │   ├── styles.tsx
│   │   │   ├── ...
│   ├── screens
│   │   ├── Main
│   │   │   ├── Contact
│   │   │   ├── Home
│   │   │   │   ├── advancedSetting
│   │   │   │   ├── components
│   │   │   │   ├── remoteAccess
│   │   │   │   ├── default.tsx
│   │   │   │   ├── HomeScreen.tsx
│   │   │   │   ├── styles.tsx
│   │   │   ├── Manual
│   │   │   ├── Pairing
└── ...
```

### Getting Started

Make sure node version installed is `>=12.x.x`. Then install using yarn (or npm):

```
yarn install
```

Start the Metro Bundler:

```
yarn start
```

###### iOS

One time. Move to `ios` folder and install pods:

```
cd ios && pod install
```

Launch application from XCode (`Command + R`) Or launch from Terminal:

```
yarn ios
# runs the following command. change device name here
# `npx react-native run-ios --simulator='iPhone 11'`
```

###### Android

Start an Android Simulator from:

```
Android Studio > Tools > AVD Manager > Run any device
```

Similarly, run from Android Studio itself Or from Terminal:

```
yarn android
# runs the following command
# react-native run-android --variant=Debug
```

### Commands

|                 | Remark                                                             |
| --------------- | ------------------------------------------------------------------ |
| `yarn start`    | Starts metro bundler                                               |
| `yarn ios`      | Starts iOS app. Start metro bundler first                          |
| `yarn android`  | Starts Android app. Start metro bundler and Android emulator first |
| `yarn lint`     | linting                                                            |
| `yarn lint:fix` | tries to fix linting issues automatically                          |

#### M1 support

Some additional steps may be required for project to work on M1.

- Disable Rosetta in Terminal
- Install ffi

```
sudo arch -x86_64 gem install ffi
```

- Re-install dependencies

```
arch -x86_64 pod install
```

Now try and run CocoaPods.

P.S.: Thanks to samanthadotcom#7043 (discord)

# moovincool
