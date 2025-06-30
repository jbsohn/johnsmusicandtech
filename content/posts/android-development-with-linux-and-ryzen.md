---
category:
  - uncategorized
date: "2018-01-14T19:53:46+00:00"
guid: http://johnsohn.info/?p=133
title: Android Development with Linux and Ryzen
url: /2018/01/14/android-development-with-linux-and-ryzen/

---
Apple macOS is my primary environment these days but I have a PC I like to work with that has gone through quite a number of upgrades over the years. I recently upgraded to an AMD Ryzen 5 1600 CPU and motherboard.  Even though Android has not been my primary development platform I have kept up with Android development going back to the days of Eclipse then Android Studio when it became the official Android development tool. I have been a little frustrated with the Android development environment after spending a lot of time in Xcode and Visual Studio over the years. The Android Studio version 2.0 release seemed very good to me but the emulator performance and build times had still been a little disappointing.

After upgrading I was interested in seeing how Android Studio would run on my upgraded PC in Windows 10. I anxiously downloaded the latest version 3 release and nothing felt like it really changed from my AMD FX CPU. I did not time anything or run any benchmarks but in general nothing really "felt" different. Also, the AMD processor does not support HAXM which in theory is supposed to make the Android Emulator run almost as good as the iOS simulator on macOS.

After doing a little searching I discovered that the Android simulator is fully supported under Linux even on AMD. I had used Linux back in the days of Slackware in the late 90s and can remember installing Red Hat 5.0 but after working primarily on mobile apps for over four years now macOS and a little Windows are all I have really worked on during this time. The last time I used Linux on the desktop [Linux Mint](http://www.linuxmint.com) was my preferred distribution and it still held the #1 spot on [DistroWatch.com](http://www.distrowatch.com) so I went with that.

The Linux Mint install was quick and painless. I did a little research and found Android Studio (and a lot of other development software) can be installed quite easily on Ubuntu systems with [umake](https://wiki.ubuntu.com/ubuntu-make). A little more setup and I was up and running. I did not benchmark anything but everything was snappy and quick. The Android emulator came up without any issues and it was the fastest I have ever seen it run on any of my systems. I am very impressed. I am going to continue with this Linux as my primary OS for Android development but I am sure macOS will still be used as well. I am going to pass on Windows 10 for now at least with AMD.

![Screenshot from 2018-01-13 23-55-20](/wp-content/uploads/2018/01/screenshot-from-2018-01-13-23-55-20.png)![IMG_2082](/wp-content/uploads/2018/01/img_2082.jpg)
