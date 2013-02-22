---
layout: post
title: "Set UIWebView's background color"
date: 2013-02-20 17:13
comments: true
categories: iOS
---
set the webview's opaque property to NO .. and set the background of the view underneath to green.

when the webview is CDVCordovaView, just set it opaque to NO, and set the view's background color: 
```objective-c
self.webView.backgroundColor = BACKGROUND_COLOR;
```
