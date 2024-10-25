---
title: Two Effective Methods for Updating Applications on macOS Explained by ZDNet
date: 2024-10-18T04:33:37.630Z
updated: 2024-10-24T18:19:19.301Z
tags:
  - apple
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/apple/    https://www.zdnet.com/a/img/resize/d9afbf29c82e696df98495c44b609bc7a135ebb3/2024/01/05/f413ba01-74e1-4edb-8d1e-41b8aa539d45/fullscreen-1-4-24-7-23pm.jpg?width=170&height=96&fit=crop&auto=webp
---

## Updating Your Mac OS Applications: A Tutorial on Two Effective Methods - Insights

![fullscreen-1-4-24-7-23pm](https://www.zdnet.com/a/img/resize/4d0754ca50eca284946b9049b2a02512354bb4c1/2024/01/05/f413ba01-74e1-4edb-8d1e-41b8aa539d45/fullscreen-1-4-24-7-23pm.jpg?auto=webp&width=1280)

Screen Sharing on MacOS Sonoma

Jason Perlow/ZDNET

Any time I see updates available for my MacOS machines, I immediately apply them. Why? Because those updates often contain security patches that keep my computers safe. Those updates might also contain new features for apps or performance and reliability improvements. Either way, I find these updates to be an essential part of [maintaining the security of my devices](https://www.zdnet.com/article/how-to-update-every-apple-device/) and keeping my mind at ease.

**Also: [How I purged over 175GB of files from my Mac in under a minute (and you can too)](https://www.zdnet.com/article/how-i-purged-over-175gb-of-files-from-my-mac-in-under-a-minute/)**

When I go to update a MacOS device, I know there's more than one way to approach the task -- from the App Store (via the MacOS GUI) or from the command line. Because I've spent decades [working with Linux](https://www.zdnet.com/article/thinking-about-switching-to-linux-things-you-need-to-know/), I'm 100% comfortable using the command line, so I will sometimes open the terminal app, check for upgrades, and then run them when they're available. Or, if I'm feeling a bit lazy, I'll just go the App Store route.

Let me show you both approaches.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to update MacOS apps from the App Store

**What you'll need:** The only things you'll need are an Apple device (a MacBook or iMac) and a valid user account on the machine. That's it. Let's get to the updates.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Open the App Store

The fastest way to check and see if there are any updates available is by clicking the Apple button in the upper-left corner, where you might see something like _2 updates_ listed (indicating you have two apps that have updates available). Click that entry to open the App Store.

I have two available updates on my MacBook Pro.

Screenshot by Jack Wallen/ZDNET

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Update your apps

When the App Store opens, you can either update the apps individually (by clicking the Update button associated with the app in question) or update them all at once (by clicking Update All). During the update process, you might be prompted to close an app (or even a related app) if it's blocking the update from continuing. Should that be the case, close the app in question, return to the App Store, and click Continue from the pop-up warning.

These two apps on my MacBook Pro have pending updates.

Screenshot by Jack Wallen/ZDNET

Once the update is completed, close the App Store and you're done.

## How to update MacOS apps from the command line

This is a bit more complicated, for two reasons: first, you have to find out what apps are available for updating, and, second -- as with Linux -- the app names are case-sensitive.

## 1\. Open the Terminal app

To run commands, you must first open the terminal app, which can be done from the Launchpad. Click the Launchpad icon in your Dock and then type _terminal_. Click the launcher to open the Terminal app.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137223/26400" target="_top" id="2137223">
  <img src="//a.impactradius-go.com/display-ad/26400-2137223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137223/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Check for available updates

Next, you need to run the command to check for updates. The command in question is _softwareupdate_ and is used for both checking and running the updates. To check for available updates, issue the command:

sudo softwareupdate -l

You will be prompted for your sudo password (which is your MacOS user password). 

**Also: [How to update every Apple device (iPhone, iPad, Apple Watch, Mac, more)](https://www.zdnet.com/article/how-to-update-every-apple-device/)**

The -l option stands for _list_. This will print out any available app updates and, if required, it will inform you if a restart is needed to complete any recent OS updates. If you see such a warning, make sure to do the reboot to complete the process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049370/7443" target="_top" id="2049370">
  <img src="//a.impactradius-go.com/display-ad/7443-2049370" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049370/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Update the apps

Let's say the command lists that Apple Mail has an update available, which should be listed as _Mail_ (remember, case sensitivity). Before you update the app, make sure to close it first. Once closed, update the app with a command like this:

sudo softwareupdate -i Mail

After successfully typing your sudo password, the update will proceed. When the update completes, you may or may not have to restart the machine. (You will be informed if a reboot is necessary.) You can then re-open the app you just updated and enjoy whatever fresh features or security patches the update applied.

**Also: [The Apple products you shouldn't buy this month](https://www.zdnet.com/article/the-apple-products-you-shouldnt-buy-this-month/)** 

This is about as simple a method as you'll find to help keep your MacOS machines running smoothly and securely. Never leave an app update lingering because it often contains security patches, which are required for the health and well-being of your operating system.

#### Apple

[iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")

[My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")

[We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")

[6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

* [iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")
* [My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")
* [We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")
* [6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/new-audiovisual-harmony-incorporating-audio-into-powerpoint-presentations/"><u>[New] Audiovisual Harmony Incorporating Audio Into PowerPoint Presentations</u></a></li>
<li><a href="https://youtube-data.techidaily.com/oundational-codes-for-youtube-enthusiasts/"><u>[New] Foundational Codes for YouTube Enthusiasts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-when-should-you-share-your-insta-story/"><u>[New] In 2024, When Should You Share Your Insta Story?</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-comprehensive-review-of-lg-bp350-display-technology-and-capabilities/"><u>2024 Approved Comprehensive Review of LG BP350 Display Technology and Capabilities</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/5-best-free-sms-applications-for-apple-iphone-users/"><u>5 Best Free SMS Applications for Apple iPhone Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/assessing-the-moisture-resistance-of-the-new-iphone-15/"><u>Assessing the Moisture Resistance of the New iPhone 15</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/correcting-problems-in-microsoft-edge-browser-functionality/"><u>Correcting Problems in Microsoft Edge Browser Functionality</u></a></li>
<li><a href="https://games-able.techidaily.com/discover-gaming-excellence-ifa-2023s-must-try-tech/"><u>Discover Gaming Excellence: IFA 2023'S Must-Try Tech</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-solutions-troubleshooting-and-resolving-windows-code-39-error/"><u>Effective Solutions: Troubleshooting and Resolving Windows Code #39 Error</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elite-8-tools-transforming-digital-images/"><u>Elite 8 Tools Transforming Digital Images</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-the-differences-cat5-vs-cat6-network-wires/"><u>Exploring the Differences: Cat5 vs Cat6 Network Wires</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-snag-screenshots-like-a-pro-on-windows-11-a-step-by-step-tutorial/"><u>How to Snag Screenshots Like a Pro on Windows 11 – A Step-by-Step Tutorial</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-honor-play-40cmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Honor Play 40CMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-the-world-of-ev-charging-explaining-the-nuances-between-level-1-2-and/"><u>Navigating the World of EV Charging: Explaining the Nuances Between Level 1, 2, And</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/small-scale-success-with-the-safest-online-meeting-tools-for-2024/"><u>Small-Scale Success with the Safest Online Meeting Tools for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/unraveling-screen-distortion-in-pc-gaming-monitors/"><u>Unraveling Screen Distortion in PC Gaming Monitors</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/why-the-ps5-is-a-game-changer-4-convincing-arguments-for-acquisition/"><u>Why the PS5 Is a Game-Changer: 4 Convincing Arguments for Acquisition</u></a></li>
</ul></div>

