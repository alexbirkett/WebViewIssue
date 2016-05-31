# WebViewIssue
Demonstrates that Android's WebView class requests data even after onPause has been called

This has been tested on a Samsung GT-I505 runnig Android 5.0.1

Steps to reproduce issue

* Open app
* Send app to background by pressing home button

Expected results

* No requests are made http://livewidgets.tv2.no

Actual results

* Web view polls http://livewidgets.tv2.no
