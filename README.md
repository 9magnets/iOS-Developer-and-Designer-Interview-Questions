# iOS-Developer-and-Designer-Interview-Questions

A small guide to help those looking to hire a developer or designer for iOS work. While tailored for iOS, many questions could be used for Android developers or designers as well. A great self-test if you're looking to keep current or practice for your own interview.

Inspired by the wonderful [Front-end Job Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions), I've done my best to match their format and have pulled some of their best questions for inclusion here. Pull requests and suggestions to this repository are highly encouraged.

Contributors: Original work by [Cameron Banga](https://twitter.com/cameronbanga). Big thanks to [Joe Pasqualetti](https://joepasq.com) for his significant additions here so far!

## <a name='contents'>Table of Contents</a>

  1. [General Questions](#general)
  1. [iOS Technologies Questions](#tech)
  1. [Coding Questions](#code)
  1. [Interface Questions](#ui)
  1. [Design Questions](#design)
  1. [App Store Questions](#appstore)
  1. [Fun Questions](#fun)
  1. [Other References](#references)
  1. [License](#license)

####[[⬆]](#contents) <a name='general'>General Questions:</a>

* What did you learn yesterday/this week?
* What excites or interests you about making software?
* Which version control systems are you familiar with?
* Do you have experience working with projects on GitHub?
* Do you contribute to any iOS open source projects on GitHub or a similar site?
* Can you describe your workflow when you work on creating an iOS app?
* Are you familiar with CocoaPods? Can you explain what they are and how they work?
* In general, explain software licensing and how this applies to work we do.
* Describe your general testing practices when building an iOS app.
* How can apps support other languages, date formats and currencies?
* What is Instruments and how is it useful?

####[[⬆]](#contents) <a name='tech'>iOS Technologies Questions:</a>

* Explain Handoff, and in general, how it it allows iOS and Mac/web apps to communicate?
* What technologies/services are contained inside of iCloud?
* What is an iOS extension? Can you list a few examples of popular/common extensions?
* What is HealthKit?
* What is HomeKit?
* What is Apple Pay? Could you describe a way we could use it in our applications?
* Explain application sandboxing.
* What is VoiceOver? Explain some of the accessibility features included in iOS and how developers can utilize them.
* How does application multitasking work on iOS?
* What features does Game Center offer for iOS games?
* What are iBeacons?
* What is Cocoa/Cocoa Touch?
* Explain in general, what Core Audio, Core Data, and Core Location are, and how they help iOS apps.
* Describe the role of SpriteKit and SceneKit.
* What is Metal?
* What is the responder chain? How does it work?
* What are the different actions that buttons and other controls can respond to?
* What is the role of the application delegate?
* Explain NSUserDefaults. How would you serialize an array to disk?
* How would you store user's credentials?
* Explain Keychain Services.
* Why are caching and compression important on mobile devices?
* Explain ~/Documents, ~/Library, ~/tmp. What directory is ~ on iOS?
* How does AirPlay work? How would you use it (programmatically) to enhance the utility and presentation of an app?
* Give a brief overview of what sensors, IO and communication methods (Wifi, telephony, etc) are available on iOS. How can you make use of these?
* What are the hardware performance differences among the iPad 2 / iPad mini 1-3, iPad Retina, iPad Air 2, iPhone 5, 5s, 6, and 6+. What do these constraints mean for performance intensive apps?

####[[⬆]](#contents) <a name='code'>Coding Questions:</a>

* What does Cocoa Touch include and not include?
* Why do Cocoa Touch classes start with two capital letters?
* What is Swift, what is Objective-C and how do they relate and compare?
* Explain why optionals are useful in Swift.
* Explain `NSError` and how it works (or doesn't) in Swift.
* How does `instancetype` work and how is it useful.
* When is `let` appropriate in Swift? `var`?
* Why and where is the `map` function useful.
* How do you track down bugs? What are your tools of choice?
* There is a bug in Cocoa. What do you do?
* There is a regression in a new distributed version of our app causing crashes. What do you do? How do you prevent new bugs?
* How are Objective-C classes implemented? Describe how the Objective-C runtime is implemented.
* What security does iOS offer to protect customers and privileged information?
* Our app downloads data and displays it in a table view. In accordance with MVC where is the best place to perform the download? 
* How does MVC influence the design of a codebase?
* What methods are part of the controller life-cycle? The view life-cycle?
* What design patterns does iOS make use of? What design patterns do you use in your codebase?
* What threads does iOS provide and how can you best utilize them?
* Give a brief description of how `UIScrollView` is implemented. How does it operate with gesture recognizers, multiple touches and the run loops?
* What API would you add or improve on iOS?

####[[⬆]](#contents) <a name='ui'>Interface Questions:</a>

* What is the screen resolution of the iPhone 5, 6, 6+. and iPad Air 2?
* What units is the resolution measured in?
* Explain the purpose of Interface Builder, what is a NIB file?
* What image filetype should iOS UI assets be saved in?
* Describe some differences between a Storyboard and a standard NIB file.
* Describe Auto Layout.
* What is the device status bar? How tall is it in points? Is it opaque or transparent? What does it do during a phone call or navigation?
* What is a navigation bar? Can you show me an Apple app on your phone that uses a navigation bar?
* What is a tab bar? Can you show me an Apple app on your phone that uses a tab bar?
* What is a toolbar? Can you show me an Apple app on your phone that uses a toolbar?
* What is a table view? What is a collection view?
* Describe when a popover is most appropriate.
* What is a split-view controller?
* What sort of content would be appropriate to place in a picker view?
* When are a label, text field and text view appropriate?
* What does a segmented control do?
* What is a modal view?
* What kind of notifications does iOS offer?

####[[⬆]](#contents) <a name='design'>Design Questions:</a>

* What is an iOS app icon? Describe it as best as you can.
* What is the smallest size an app icon could be? What's the largest size it could be?
* Can an app icon contain any transparency?
* How does a Newsstand icon differ from a regular app icon?
* Explain a launch image.
* Describe the purpose of Auto Layout, and in general, how it works.
* Describe the role of animation in design of software.
* Describe the role of interactivity and feedback when designing software.
* What are some differences to take into account when building an iPhone app vs an iPad app?
* Describe the importance and role of prototyping when working on an app design.

####[[⬆]](#contents) <a name='appstore'>App Store Questions:</a>

* What are In-App Purchases? How do they work? What can be purchased with IAP?
* Have you ever submitted an app to the App Store? Can you explain the general process?
* What is iTunes Connect?
* What is a provisioning profile?
* What is an App ID?
* What are the differences between Development and Production iOS signing certificates?
* How is TestFlight used? How were UUIDs used in ad-hoc app distribution?
* When do purchase receipts need to be verified?
* What is required to display iAds?

####[[⬆]](#contents) <a name='fun'>Fun Questions:</a>

* What's a cool thing you've coded recently? What's something you've built that you're proud of?
* What are some things you like about the developer tools you use?
* what are some of your favorite independent Mac or iOS developers?
* Do you have any pet projects? What kind?
* What would you change about Xcode?
* What is your favorite iOS API? 
* Do you have a pet or favorite bug report?
* What are your favorite ways to investigate an new technology?

####[[⬆]](#contents) <a name='references'>Other References:</a>

* [iOS Dev Weekly](https://iosdevweekly.com)
* [Accidental Tech Podcast](http://atp.fm)
* [Debug Podcast](http://www.imore.com/debug)
* [The Talk Show](https://daringfireball.net/thetalkshow/)
* [NSHipster](http://nshipster.com)
* [KZBootstrap](https://github.com/krzysztofzablocki/KZBootstrap)
* [WWDC Videos](https://developer.apple.com/videos/wwdc/2014/)
* [ASCII WWDC](http://asciiwwdc.com)
* [Pttrns](http://www.pttrns.com)
* [Ray Wenderlich Tutorials](http://www.raywenderlich.com)
* [iOS Version Stats](http://david-smith.org/iosversionstats/)
* [iOS Human Interface Guidelines](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/)
* [Black Pixel blog post on hiring iOS and Mac engineers](http://blackpixel.com/blog/2013/04/interview-questions-for-ios-and-mac-developers-1.html)
* [Macoscope guide to a technical interview](http://macoscope.com/blog/so-you-have-a-technical-interview-at-macoscope/)

####[[⬆]](#contents) <a name='license'>License:</a>

Released under the [MIT License](http://opensource.org/licenses/MIT). See LICENSE file for details.
