Unofficial copy of LinkedIn source version 1.1.4 relased on November 2, 2015

Gradle
------
This library was created just to import linkedin sdk through gradle through JitPack which helps in faster compilation.

    allprojects {
      repositories {
            maven { url "https://jitpack.io" }
      }
    }
  
  
    dependencies {
         compile 'com.github.neurospeech:unofficial-linkedin-sdk-android:v1.1.4'
    }

LinkedIn's Mobile SDK for Android is an open-source library intended to reduce the 
friction of integrating LinkedIn's data and services into your Android applications.

Features
--------

* Easy single sign-on (SSO) authentication, in conjunction with the official LinkedIn mobile app.
* A convenient wrapper for making authenticated calls to LinkedIn's REST APIs.
* "Deep linking" to additional member content in the official LinkedIn mobile app.
* A sample application that provides working examples of all of the SDK's features.

Website & Documentation
-----------------------
[https://developer.linkedin.com/docs](https://developer.linkedin.com.docs)

Quickstart Guides
------------------------------

* [Getting Started with the Mobile SDK for Android](https://developer.linkedin.com/docs/android-sdk.html)
* [Authenticating with the Mobile SDK for Android](https://developer.linkedin.com/docs/android-sdk-auth.html)
