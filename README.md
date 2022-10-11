# react-native-reanimated

yarn add @react-native-community/masked-view @react-navigation/drawer @react-navigation/native @react-navigation/stack @reduxjs/toolkit axios deprecated-react-native-prop-types moment react react-native react-native-blob-util react-native-calendars react-native-config react-native-device-info react-native-dropdownalert react-native-flash-message react-native-gesture-handler react-native-pdf react-native-reanimated react-native-render-html react-native-safe-area-context react-native-screens react-native-sound react-native-vector-icons react-redux redux redux-saga

-yarn

watchman watch-del-all && killall -9 node && rm -rf yarn.lock package-lock.json node_modules ios/Pods ios/Podfile.lock android/app/build && yarn && cd ios && pod update && cd .. && yarn start -- --reset-cache

-npm

watchman watch-del-all && killall -9 node && rm -rf yarn.lock package-lock.json node_modules ios/Pods ios/Podfile.lock android/app/build && npm install && cd ios && pod update && cd .. && npm start -- --reset-cache

watchman watch-del-all
rm -rf yarn.lock package-lock.json node_modules
rm -rf android/app/build
rm ios/Pods ios/Podfile.lock
rm -rf ~/Library/Developer/Xcode/DerivedData
npm install && cd ios && pod update && cd ..
npm start -- --reset-cache

cmd
cd android && ./gradlew clean
open -a /Applications/Android\ Studio.app
cd android && gradle build --warning-mode=all
gradle build --warning-mode=all --stacktrace

---

npx react-native init AwesomeProject
