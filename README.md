# YouTube force-skip ad bookmarklet
A bookmarklet that skips the currently playing YouTube ad. Useful for when your adblocker isn't working.

![image](https://github.com/Noobot9k/YouTube-force-ad-skip-bookmarklet/assets/32988106/9d8790e1-f636-4c37-8343-94eaff921943)

Bookmarklets are bookmarks that run JavaScript code on the current page when clicked instead of taking you to a URL.

This should work on any browser though the installation process will be a little different from browser to browser. The instructions included here are for Chromium-based browsers.

This bookmarklet isn't meant to replace your ad blocker. YouTube is currently waging a war on ad blockers and sometimes uBlock Origin won't work and you'll have to disable it to watch YouTube. When this happens, having this bookmarklet can be handy for skipping unskippable ads.

# Installation

1. Right-click anywhere on your bookmark bar and click "add page..."
2. Name it something memorable like "Skip ad"
3. For easy access, don't place it in a folder. Put it directly on the bookmark bar.
4. Remove everything in the URL box and replace it with the following code:
   
   ⚠ WARNING! ⚠
   Bookmarklets are code that runs on the current page when clicked. **ONLY INSTALL BOOKMARKLETS FROM TRUSTED SOURCES!** They can do nasty stuff like steal login tokens. READ THE CODE AND MAKE SURE IT IS SAFE BEFORE CONTINUING!

   (You can easily copy it by clicking the ![image](https://github.com/Noobot9k/YouTube-force-ad-skip-bookmarklet/assets/32988106/2608a35e-eebe-4b55-b5c5-965e014889db) button)
```
javascript: void(0);(function(){document.querySelectorAll('video')[0].currentTime = document.querySelectorAll('video')[0].duration; document.querySelectorAll('button.ytp-ad-skip-button-modern')[0].click(); })()
```

5. Click "save"
6. Find the bookmarklet if it's hidden or in a folder and move it somewhere accessible on your bookmark bar.

# Usage

Next time YouTube stops you from watching a video with uBlock Origin on and forces you to disable it and watch an ad, click the "Skip ad" bookmarklet and the ad will skip to the end and auto-click the "skip" button for you.

Avoid clicking the bookmarklet too many times because if no ad is playing it will skip to the end of your video. I might fix this if it starts to bug me.


<sub>
Copyright (c) 2023, Chris Johnson
All rights reserved.

This source code is licensed under the MIT license found in the
LICENSE file in the root directory of this source tree. 
</sub>
