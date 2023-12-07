# YouTube force skip ad bookmarklet
A bookmarklet that skips the currently playing YouTube ad. Useful for when your adblocker isn't working.

1.) Right-click anywhere on your bookmark bar and click "add page..."
2.) Name it something memorable like "Skip ad"
3.) For easy access, don't place it in a folder. Put it directly on the bookmark bar.
4.) Remove everything in the URL and replace it with the following:
```
javascript: void(0);(function(){document.querySelectorAll('video')[0].currentTime = document.querySelectorAll('video')[0].duration; document.querySelectorAll('button.ytp-ad-skip-button-modern')[0].click(); })()
```
5.) Click "save"
6.) Find the bookmarklet if it's hidden or in a folder and move it somewhere accessible on your bookmark bar.

Next time YouTube stops you from watching a video with uBlock on and forces you to disable it and watch an ad, click the "Skip ad" bookmarklet and the ad will skip to the end and auto-click the "skip" button for you.

Avoid clicking the bookmarklet too many times because if no ad is playing it will skip to the end of your video. I might fix this if it starts to bug me.


<sub>
Copyright (c) 2023, Chris Johnson
All rights reserved.

This source code is licensed under the MIT license found in the
LICENSE file in the root directory of this source tree. 
</sub>
