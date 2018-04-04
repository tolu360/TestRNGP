# TestRNGP
A sample app to test and debug the library at https://github.com/tolu360/react-native-google-places

To run this in the iOS Simulator or the Android Emulator, do the following:

- Clone or download the repo to your machine.
- Run `yarn` **OR** `npm install` to pull in Js Dependencies.
- Run `cd ios && pod install` to pull in CocoaPods.
- If my Google API keys do not work for you, replace them with yours in `AppDelegate.m` and/or in `AndroidManifest.xml`. You may need to change the bundle ID or app ID (`com.arttitude360.testrngp`) to make it work with your own keys. Or consider using a tool like https://github.com/junedomingo/react-native-rename to rename the app and the app ID (on Android) at a go.
- Always launch with the `TestRNGP.xcworkspace` file in `Xcode`.
