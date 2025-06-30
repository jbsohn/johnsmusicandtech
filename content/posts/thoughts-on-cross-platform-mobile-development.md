---
category:
  - uncategorized
date: "2017-11-02T03:38:45+00:00"
guid: https://johnsohninfo.wordpress.com/?p=42
title: Thoughts On Cross Platform Mobile Development
url: /2017/11/02/thoughts-on-cross-platform-mobile-development/

---
I have been experimenting over the last few years looking for the definite answer to cross platform mobile development. These are some of my thoughts after evaluating some approaches.

## Hybrid - Cordova/PhoneGap

Write the app in HTML5 with Javascript. Most of the user interface and code work across Android and iOS. I have done a lot of this at work recently. The big issues are on older version of Android without an updated HTML5 webview. I have also found JavaScript not to be a very good language to write a large, scalable application in although TypeScript/ES6 may change my mind about this. This approach I feel gives advantage to the developer and takes away from the user by not giving them a full native experience on the platform.

## C++

I tested this approach with my Steel Sidekick application. The entire non UI is written in C++. The fret board view is using OpenGL ES for Graphics. Since OpenGL ES runs on both Android and iOS (as well as Windows and Mac) I can even use some of the UI code across all platforms. The only implementation needed for a new platform is the UI interface. I still need to complete the Mac and Android portion. A lot of companies are using this approach. The Microsoft Office and Dropbox mobile apps all use C++. I had not used C++ recently and it was nice going back to it but you definitely cannot jump into it like JavaScript.

## Java (using J2Obc)

This approach has all the non-UI code written in Java. The Java code can be used on Android and on the web using GWT. On iOS the java-2-objective c process translates the Java code to Objective C which can then be imported into the Swift/Objective C project on iOS and Mac. This is the approach used by Google. Google is heavily backing the j2objc project if commits to the GitHub project is any indicator.

## Xamarin

Microsoft implementation (through acquisition) of the Android and iOS API in C#. The native code is all written in C# instead of Objective C/Swift on iOS and Java for Android. The non-UI code is shared across Android and iOS. The native API's are exposed in C#. It seems like a good choice especially for Microsoft shops. It was one of my top picks when we evaluated it at work. In the end it does not seem to much different than the C++ or Java. The native code is written in C# which I feel is a little non-standard but it could work. I am going to investigate this in more detail.

## ReactNative

Most of the  app code is written in Javascript. The native API is exposed as Javascript. It is a little like Xamarin. If the native toolkit does not exist on your platform you still need to write code Objective C/Swift on iOS or Java for Android. This seems to have a lot of momentum behind it. Facebook is backing this project. The Facebook mobile app is written in React Native. I did not think this was a good choice when I first investigated it but it is growing on me as I look into it further.
