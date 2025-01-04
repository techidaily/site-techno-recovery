---
title: "Revealing Hidden Data in macOS: The Ultimate Terminal Command Tutorial"
date: 2025-01-03T16:10:10.294Z
updated: 2025-01-04T16:21:45.546Z
categories:
  - BestProducts
description: "This Article Describes Revealing Hidden Data in macOS: The Ultimate Terminal Command Tutorial"
excerpt: "This Article Describes Revealing Hidden Data in macOS: The Ultimate Terminal Command Tutorial"
thumbnail: https://thmb.techidaily.com/852437a8f4dc8f33eb3a839d8b7d9a1e3df217c9c33ef7947ef934470397fa43.jpg
---

## Revealing Hidden Data in macOS: The Ultimate Terminal Command Tutorial
 Your Mac has a few secrets, hidden folders, and files that are invisible to you. You may not even realize how much hidden data there is on your Mac, from basic things, such as preference files for user data and apps, to core system data that your Mac needs to run correctly. Apple hides these files and folders to prevent you from accidentally changing or deleting important data that your Mac needs.

 Apple's reasoning is good, but there are times when you may need to view these out-of-the-way corners of your Mac's file system. You'll find that accessing these hidden corners of your Mac is one of the steps in many Mac troubleshooting guides, as well as guides for backing up important data, such as[mail messages](https://www.lifewire.com/transfer-apple-mail-to-new-mac-2260915) or[Safari bookmarks](https://www.lifewire.com/back-up-or-move-safari-bookmarks-to-new-mac-2260891) . Fortunately, Apple includes ways to access these hidden goodies in[OS X](https://www.lifewire.com/install-mac-os-on-pc-5075590) and the more recent[macOS](https://www.lifewire.com/what-is-macos-4691239) . This guide concentrate on using the Terminal app, which provides a command line-like interface to many of the Mac's core functions.

![macOS Terminal with hidden files in a Finder window superimposed](https://www.lifewire.com/thmb/0GxCNfM-Nwq84X9L67jj4gSEqP4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/ScreenShot2019-01-03at3.13.16PM-5c2ea61c46e0fb0001abc508-fb8027cc5efa44e2a3c858234aac1ae3.jpg)

 With Terminal, a simple command is all it takes to get your Mac to spill its secrets.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use Terminal

1. Launch**Terminal** , located at**/Applications/Utilities/** .  
![Terminal application in macOS Finder Utilities folder](https://www.lifewire.com/thmb/MlM5SU4iQfZRMK1iLmULOs4OewA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_view-hidden-mac-folders-using-terminal-2260776-5c2ea70b46e0fb000123c164.jpg)
2. Type or copy and paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles TRUE**  
**killall Finder**  
![Terminal window with commands inline](https://www.lifewire.com/thmb/z9u9E5cQZxfSmppiqZSimKAfX_s=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_view-hidden-mac-folders-using-terminal-2260776-5c2ea73546e0fb0001415cda.jpg)
3. Entering the two lines above into Terminal allows you to use the[Finder](https://www.lifewire.com/use-mac-finder-2260739) to display all the hidden files on your Mac. The first line tells the Finder to display all files, regardless of how the hidden flag is set. The second line stops and restarts the Finder, so the changes can take effect. You may see your desktop disappear and reappear when you execute these commands; this is normal.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Was Hidden Can Now Be Seen

 Now that the Finder is displaying[hidden files](https://www.lifewire.com/what-is-a-hidden-file-2625898) and folders, just what can you see? The answer depends on the specific folder you're looking at, but in just about every folder, you'll see a file named**.DS\_Store** . The DS\_Store file contains information about the current folder, including the icon to use for the folder, the location its window will open in, and other bits of information the system needs.

 More important than the ubiquitous .DS\_Store file are the hidden folders that allow Mac users to access files such as the[Library folder](https://www.lifewire.com/os-x-is-hiding-your-library-folder-2260833) within your[Home folder](https://www.lifewire.com/move-macs-home-folder-new-location-2260157) . The Library folder contains many files and folders that relate to specific apps and services that you use on your Mac. For example, have you ever wondered where your email messages are stored? If you use Mail, you'll find them in the hidden Library folder. Likewise, the Library folder contains your[Calendar](https://www.lifewire.com/back-up-or-move-ical-or-calendar-data-to-new-mac-2260870) , Notes,[Contacts](https://www.lifewire.com/back-up-or-move-contacts-or-address-book-data-2260801) ,[Saved Application States](https://www.lifewire.com/managing-resume-feature-os-x-2259802) , and much more.

 Go ahead and look around the Library folder, but don't make any changes unless you have a specific problem that you're attempting to fix.

 Now that you can see all the hidden folders and files in the Finder, you'll probably want to hide them again, if only because they tend to clutter up Finder windows with extraneous items.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Hide the Clutter

1. Launch**Terminal** , located at**/Applications/Utilities/** .
2. Type or copy/paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles FALSE**  
**killall Finder**  
![Terminal with ShowAllFiles set to FALSE](https://www.lifewire.com/thmb/7JHA9g9EOKMG8xeydvO7Yp3H_24=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_view-hidden-mac-folders-using-terminal-2260776-5c2ea75e46e0fb0001a438c8.jpg)
3. Poof! The hidden files are once again hidden. No hidden folder or file was harmed in the making of this Mac tip.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## More About Terminal

 If the power of the Terminal app intrigues you, you can find out more about what secrets Terminal can uncover in this guide:[Use the Terminal Application to Access Hidden Features](https://www.lifewire.com/mac-terminal-commands-4774997) .

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[Subscribe](https://www.lifewire.com/#)

Tell us why!

 Other  Not enough details  Hard to understand

 Submit

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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-breaking-barriers-in-advertising-animating-for-maximum-roi-on-fb/"><u>[New] In 2024, Breaking Barriers in Advertising Animating for Maximum ROI on FB</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pureimagezone-premium-tool-to-remove-backgrounds/"><u>[New] PureImageZone Premium Tool to Remove Backgrounds</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-premium-motion-mastery-modules/"><u>[Updated] 2024 Approved Premium Motion Mastery Modules</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-clearing-up-audio-issues-in-half-volume-facebook-content/"><u>[Updated] Clearing Up Audio Issues in Half-Volume Facebook Content</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-unlock-the-art-of-snapchat-pins/"><u>[Updated] Unlock the Art of Snapchat Pins</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/a-comprehensive-guide-to-skillful-imagery-research-within-facebooks-platform/"><u>A Comprehensive Guide to Skillful Imagery Research Within Facebook's Platform</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/curious-about-apples-punctuation-policy-discover-why-they-shun-exclamation-marks-on-their-site-zdnet/"><u>Curious About Apple's Punctuation Policy? Discover Why They Shun Exclamation Marks on Their Site | ZDNET</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/hit-the-right-note-easy-steps-to-snag-a-spotify-subscription-at-student-prices/"><u>Hit the Right Note: Easy Steps to Snag a Spotify Subscription at Student Prices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-your-device-choices-with-tips-from-toms-hardware/"><u>Mastering Your Device Choices with Tips From Tom's Hardware</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/steps-to-take-if-you-cant-access-your-instagram-account-anymore/"><u>Steps to Take if You Can't Access Your Instagram Account Anymore</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-t-mobiles-intra-country-roaming-rules/"><u>Understanding T-Mobile's Intra-Country Roaming Rules</u></a></li>
</ul></div>

