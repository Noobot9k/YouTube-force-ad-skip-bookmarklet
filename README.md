# YouTube force skip ad bookmarklet
A bookmarklet that skips the currently viewed YouTube ad for when adblocker isn't working.

[test](url)
[test2](javascript: void(0);(function(){document.querySelectorAll('video')[0].currentTime = document.querySelectorAll('video')[0].duration; document.querySelectorAll('button.ytp-ad-skip-button-modern')[0].click(); })())
