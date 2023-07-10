# [Application fundamentals](https://developer.android.com/guide/components/fundamentals)

## So what does the Android SDK Tool actually do?

It compiles the code along with the data and resources files into `.apk` or `.aab`

## What is this APK?

So Android Package is an archive file with suffix `.apk` contains all the content necessary for the app to run at the runtime, and it is the file that is used to install the app on Android powered devices.
 
## What about AAB?

So Android App Bundle is an archive file with suffix `.abb` contains all the content required at the runtime including the metadata which is not required at the runtime. It is publishing format and cannot be used to install on android powered devices. It defers APK generation and signing at later stage.