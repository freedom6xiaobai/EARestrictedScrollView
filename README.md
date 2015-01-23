#EARestrictedScrollView

[![CI Status](http://img.shields.io/travis/ealeksandrov/EARestrictedScrollView.svg?style=flat)](https://travis-ci.org/ealeksandrov/EARestrictedScrollView)
[![Version](https://img.shields.io/cocoapods/v/EARestrictedScrollView.svg?style=flat)](http://cocoadocs.org/docsets/EARestrictedScrollView)
[![License](https://img.shields.io/cocoapods/l/EARestrictedScrollView.svg?style=flat)](http://cocoadocs.org/docsets/EARestrictedScrollView)
[![Platform](https://img.shields.io/cocoapods/p/EARestrictedScrollView.svg?style=flat)](http://cocoadocs.org/docsets/EARestrictedScrollView)

**`UIScrollView` sublass with ability to restrict scrolling area.**

In plain `UIScrollView` only `contentSize` can be changed, but not the origin of scrolling area. This simple and universal solution allows to restrict scrolling area with `CGRect`.

##CocoaPods

[CocoaPods](http://cocoapods.org/) is the recommended way to use EARestrictedScrollView in your project.

* Simply add this line to your `Podfile`: `pod 'EARestrictedScrollView', '~> 0.1.0'`
* Run `pod install`.
* Include with `#import "EARestrictedScrollView.h"` to use it wherever you need.

##Manual installation

* Add `EARestrictedScrollView` header and implementation to your project (2 files total).
* Include with `#import "EARestrictedScrollView.h"` to use it wherever you need.

##How To Use It

Change scrolling area with new `restrictionArea` property. Reset restriction with passing `CGRectZero` to `restrictionArea`.

##Author

Created and maintained by Evgeny Aleksandrov ([@EAleksandrov](https://twitter.com/EAleksandrov)).

## License

`EARestrictedScrollView` is available under the MIT license. See the LICENSE file for more info.
