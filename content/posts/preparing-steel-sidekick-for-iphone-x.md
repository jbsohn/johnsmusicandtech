---
category:
  - uncategorized
date: "2017-11-09T17:16:39+00:00"
guid: http://johnsohn.info/?p=75
title: Preparing Steel Sidekick for iPhone X
url: /2017/11/09/prepare-steel-sidekick-for-iphone-x/

---
I just pushed an update of Steel Sidekick to the App Store to support the iPhone X screen resolution. The new "notch" for the camera was causing some issues.

![iPhoneX-Before](/wp-content/uploads/2017/11/iphonex-before.png)

I used the new safeAreaLayoutGuide on the UIView to determine where to display the fretboard.

```
if (@available(iOS 11.0, *)) {
  CGRect safeRect = [self.view.safeAreaLayoutGuide layoutFrame];
  left = safeRect.origin.x;
}
```

After trying a few different layouts I ultimately decided to move the fretboard into the safe area and extend the strings under the notch.
![iPhoneX-After](/wp-content/uploads/2017/11/iphonex-after1.png)

If you have an iPhone X and download the latest version the notch should no longer hide the open string notes.
