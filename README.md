1. Copy your msso_config.json file inside platforms/android/app/src/main/assets folder
2. This app depends upon the MAS Android Native dependencies 2.1.00 pulled via JCenter, which have been already ingested into the build file i.e. you don't need to make any change in build configurations. Just open the app in Android Studio, build and run.

In case, if you need to work with native libraries directly i.e. not using the JCenter denpendecy injection, then follow the steps mentioned in [**MAS Cordova Developer Guide**](https://techdocs.broadcom.com/content/broadcom/techdocs/us/en/ca-enterprise-software/layer7-api-management/mobile-sdk-for-ca-mobile-api-gateway/2-1/Cordova/Cordova_2-1.html) under the section **`Developer Mode: Build your app with frameworks of native SDKs`**.

```
Disclaimer: This app is build using Cordova version 8.0. It won't compile if using Cordova Version less than 8.0, because Cordova Android has changed the internal structure of Android folders and this app only conforms to the new folder structure.
```