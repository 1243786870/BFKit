![BFKit Banner](http://github.fabriziobrancati.com/bfkit/resources/banner.jpg)

BFKit is a collection of useful classes to **develop Apps faster**.

Installing and Usage
====================

###Manual
- Copy the **library** folder (**BFKit**) to the project
- Add the **AudioToolbox** framework to the project
- Import the file "**BFKit.h**"
- Enjoy!

###Pod
- Create a Podfile in your project directory
- Write: 
```ruby
  platform :ios, '7.0'
  xcodeproj 'Project.xcodeproj'
  pod 'BFKit'
```
- Obviously change "Project"  with your real project name
- Open Terminal e type:
```bash
  pod install
```
- Import the file "**BFKit.h**"
- Enjoy!

Requirements
============
- iOS SDK **7.0** or later

Language support
================
```en, it, ru, uk, id, zh```

More soon!

Notes
=====
Some things are not updated to iOS 8 (in example font enums), but it will be soon!

What does it do?
================
Adds some useful method to some classes.

###Foundation:
- NSArray
- NSDate
- NSFileManager
- NSMutableArray
- NSNumber
- NSProcessInfo
- NSString

###UIKit:
- UIButton
- UIColor
- UIDevice
- UIFont
- UIImage
- UIImageView
- UILabel
- UIScrollView
- UITableView
- UITextField
- UIView
- UIWebView
- UIWindow

###BFKit:
- BFPassword
- BFSystemSound

It makes possible to create User Interfaces and working with Foundation framework faster.
It adds a class to check the strength of a password and a class to play system sounds with an enum.

I'll add here a list of all available methods soon!

Changelog
=========

###Version 1.1.0
- Added UIWindow category
- Added system macros
- Added new iOS devices
- Added pulse animation
- Added Russian, Ukrainian, Indonesian and Chinese
- Minor enhancements & bugfixes

Author
======
Fabrizio Brancati

- [Website](http://www.fabriziobrancati.com)
- [Email](mailto:fabrizio.brancati@gmail.com)

License
=======
BFKit is available under the MIT license. See the LICENSE file for more info.
