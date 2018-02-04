This repo is intend to demostrate use react-native-zip-archive to unzip file with non-ASCII pathname on Android

````sh
yarn
./node_modules/.bin/react-native run-android
````

you're supposed to see the app show 'Hello World!' which is unziped from a zip called '压缩包'. you can also connect to the emulator using 'adb shell' and navigate to '/data/user/0/com.example/files' to check that
