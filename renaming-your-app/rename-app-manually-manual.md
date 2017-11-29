### Rename App Manually Manual

Renaming a react-native app manually is simple.

#### iOS

The_**app name**_displayed on the iPhone home screen comes from the CFBundleDisplayName \(or "Bundle display_**name**_"\) as the human-readable string in Xcode\) entry of your iOS app's info.plist.![](https://harrisrobin.gitbooks.io/react-native-checklist/content/assets/images/cbfbundledisplayname-ss.png)

#### Android

The app name on android comes from AndroidManifest.xml. Check the label attribute of`<application>`

This value is typically referenced as a named variable, defined in strings.xml![](https://harrisrobin.gitbooks.io/react-native-checklist/content/assets/images/app_name-ss.png)

  


