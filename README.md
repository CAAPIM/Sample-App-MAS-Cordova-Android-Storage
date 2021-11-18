[![Maintenance](https://img.shields.io/badge/Maintained%3F-no-red.svg)](https://bitbucket.org/lbesson/ansi-colors)
:bangbang: | Please note that Cordova and Xamarin support for the SDK has been deprecated with release 2.1. The 2.1 release will be the last release with Cordova and Xamarin support. Please do not submit any new changes as they are no longer being accepted. Please contact Broadcom support [**https://support.broadcom.com/**](https://support.broadcom.com/) to report any defects or make a request for an update.
:---: | :---

1. Copy your msso_config.json file inside platforms/android/app/src/main/assets folder
2. This app depends upon the MAS Android Native dependencies 2.1.00 pulled via JCenter, which have been already ingested into the build file i.e. you don't need to make any change in build configurations. Just open the app in Android Studio, build and run.

In case, if you need to work with native libraries directly i.e. not using the JCenter denpendecy injection, then follow the steps mentioned in [**MAS Cordova Developer Guide**](https://techdocs.broadcom.com/content/broadcom/techdocs/us/en/ca-enterprise-software/layer7-api-management/mobile-sdk-for-ca-mobile-api-gateway/2-1/Cordova/Cordova_2-1.html) under the section **`Developer Mode: Build your app with frameworks of native SDKs`**.

```
Disclaimer: This app is build using Cordova version 8.0. It won't compile if using Cordova Version less than 8.0, because Cordova Android has changed the internal structure of Android folders and this app only conforms to the new folder structure.
```
