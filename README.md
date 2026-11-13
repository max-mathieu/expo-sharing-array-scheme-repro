# expo-sharing: array `scheme` breaks the share extension

`app.json` sets `"scheme": ["myapp", "myapp-alt"]` (valid per the Expo config type) with the `expo-sharing` plugin enabled on iOS and Android.

```sh
npm install
npx expo prebuild --no-install
cat android/app/src/main/res/values/strings.xml
cat ios/expo-sharing-extension/Info.plist
```
