# WKWebViewExtension

[Extended Reading](https://dequan1331.github.io/) | [中文](./README-CN.md) | [扩展阅读](https://dequan1331.github.io/)

An extension for WKWebView . 

Providing `WKWebView MenuItems delete` 、 `WKWebView support protocol` 、 `WKWebView clear cache or iOS8` and so on.

> Together with WKWebViewExtension, components serve HybridPageKit, which is a general sulotion of news App content page.


## Requirements
iOS 8.0 or later

		
##	Installation

1.	CocoaPods
	
		platform :ios, '8.0'
		pod 'WKWebViewExtension'

2.	Cloning the repository

	```objective-c
	#import <WKWebViewExtensionsDef.h>
	```

## Features

1.	DeleteMenuItems  `iOS11 this issue has been fixed `

	
		WKWebView Support Delete System MenuItems
   		Delete System Items Without cut/copy/paste/delete
   		

2.	SupportProtocol

		WKWebView Support Protocol Like UIWebView

3.	SafeClearCache

		WKWebView Support iOS8 Clear All Cache
		
4.	SafeScrollTo

		WKWebView Safe ScrollTo Specific Offset Without Blank Screen by Runloop
		
5.	SafeEvaluateJS

		Safe Evaluate JS And Retainify Webview For CallBack, and Make Sure CallBack IS NOT null
		
6.	ExternalNavigationDelegates

		WKWebView Support Internal And Extenal Delegates

7.	SyncConfigUA

		Sync Config UA Without WKWebView
		
## Licenses

All source code is licensed under the [MIT License](https://github.com/dequan1331/WKWebViewExtension/blob/master/LICENSE).

## Contact

<img src="./contact.png">