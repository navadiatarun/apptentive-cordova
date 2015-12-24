Apptentive Cordova Changelog
============================

This document lets you know what has changed in the Cordova plugin. For changes in each version of the native SDKs, please see:

- [Android Changelog](https://github.com/apptentive/apptentive-android/blob/master/CHANGELOG.md)
- [iOS Changelog](https://github.com/apptentive/apptentive-ios/blob/master/CHANGELOG.md)

v2.1.0 - December 22, 2015
=========================

- Apptentive Android SDK: 2.1.1
- Apptentive iOS SDK: 2.1.0
- Sending custom data through `Apptentive.showMessageCenter()`, `Apptentive.addCustomDeviceData(successCallback, errorCallback, key, value)` and `Apptentive.addCustomPersonData(successCallback, errorCallback, key, value)` now support typed `value`. The supported value types are Number, Boolean and String
- Updated to the latest Apptentive iOS SDK v2.1.0

v2.0.1 - November 5, 2015
=========================

- Apptentive Android SDK: 2.0.1
- Apptentive iOS SDK: 2.0.5
- Fixed a bug where the callback provided to `Apptentive.addUnreadMessagesListener()` wasn't getting called on Android.
- Updated to the latest Apptentive iOS SDK v2.0.5

v2.0.0 - September 22, 2015
===========================

- Apptentive Android SDK: 2.0.1
- Apptentive iOS SDK: 2.0.2
- Upgrades the Apptentive Cordova plugin with v2.0 of our Android and iOS SDKs
- Includes a completely redesigned Message Center