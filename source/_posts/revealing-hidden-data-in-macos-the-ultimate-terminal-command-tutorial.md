---
title: "Revealing Hidden Data in macOS: The Ultimate Terminal Command Tutorial"
date: 2024-08-26T06:06:51.703Z
updated: 2024-08-27T06:06:51.703Z
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

## How to Use Terminal

1. Launch**Terminal** , located at**/Applications/Utilities/** .  
![Terminal application in macOS Finder Utilities folder](https://www.lifewire.com/thmb/MlM5SU4iQfZRMK1iLmULOs4OewA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_view-hidden-mac-folders-using-terminal-2260776-5c2ea70b46e0fb000123c164.jpg)
2. Type or copy and paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles TRUE**  
**killall Finder**  
![Terminal window with commands inline](https://www.lifewire.com/thmb/z9u9E5cQZxfSmppiqZSimKAfX_s=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_view-hidden-mac-folders-using-terminal-2260776-5c2ea73546e0fb0001415cda.jpg)
3. Entering the two lines above into Terminal allows you to use the[Finder](https://www.lifewire.com/use-mac-finder-2260739) to display all the hidden files on your Mac. The first line tells the Finder to display all files, regardless of how the hidden flag is set. The second line stops and restarts the Finder, so the changes can take effect. You may see your desktop disappear and reappear when you execute these commands; this is normal.

## What Was Hidden Can Now Be Seen

 Now that the Finder is displaying[hidden files](https://www.lifewire.com/what-is-a-hidden-file-2625898) and folders, just what can you see? The answer depends on the specific folder you're looking at, but in just about every folder, you'll see a file named**.DS\_Store** . The DS\_Store file contains information about the current folder, including the icon to use for the folder, the location its window will open in, and other bits of information the system needs.

 More important than the ubiquitous .DS\_Store file are the hidden folders that allow Mac users to access files such as the[Library folder](https://www.lifewire.com/os-x-is-hiding-your-library-folder-2260833) within your[Home folder](https://www.lifewire.com/move-macs-home-folder-new-location-2260157) . The Library folder contains many files and folders that relate to specific apps and services that you use on your Mac. For example, have you ever wondered where your email messages are stored? If you use Mail, you'll find them in the hidden Library folder. Likewise, the Library folder contains your[Calendar](https://www.lifewire.com/back-up-or-move-ical-or-calendar-data-to-new-mac-2260870) , Notes,[Contacts](https://www.lifewire.com/back-up-or-move-contacts-or-address-book-data-2260801) ,[Saved Application States](https://www.lifewire.com/managing-resume-feature-os-x-2259802) , and much more.

 Go ahead and look around the Library folder, but don't make any changes unless you have a specific problem that you're attempting to fix.

 Now that you can see all the hidden folders and files in the Finder, you'll probably want to hide them again, if only because they tend to clutter up Finder windows with extraneous items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## Hide the Clutter

1. Launch**Terminal** , located at**/Applications/Utilities/** .
2. Type or copy/paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles FALSE**  
**killall Finder**  
![Terminal with ShowAllFiles set to FALSE](https://www.lifewire.com/thmb/7JHA9g9EOKMG8xeydvO7Yp3H_24=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_view-hidden-mac-folders-using-terminal-2260776-5c2ea75e46e0fb0001a438c8.jpg)
3. Poof! The hidden files are once again hidden. No hidden folder or file was harmed in the making of this Mac tip.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/new-how-to-react-if-your-live-video-is-quashed-on-facebook-for-2024/"><u>[New] How to React if Your Live Video Is Quashed on Facebook for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-image-intensifiers-ranking-the-best-10-photography-lenses/"><u>[New] In 2024, Image Intensifiers  Ranking the Best 10 Photography Lenses</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-nail-the-next-best-thing-youtube-studio-editing-mastery/"><u>[New] In 2024, Nail the Next Best Thing  YouTube Studio Editing Mastery</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovations-in-videography-infusing-narratives-effortlessly/"><u>[New] Innovations in Videography  Infusing Narratives Effortlessly</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-fast-techniques-to-restructure-your-youtube-sequence/"><u>[Updated] 2024 Approved  Fast Techniques to Restructure Your YouTube Sequence</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-tailoring-your-obs-feeds-for-best-social-media-impact/"><u>[Updated] 2024 Approved  Tailoring Your OBS Feeds for Best Social Media Impact</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-explore-virtual-realms-with-top-gadgets-and-peripherals/"><u>[Updated] Explore Virtual Realms with Top Gadgets and Peripherals</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-prove-your-skills-with-flawless-ps4-screen-capture-for-gamers/"><u>[Updated] In 2024, Prove Your Skills with Flawless PS4 Screen Capture for Gamers</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-to-slowing-youtube-videos-37-chars/"><u>2024 Approved  The Ultimate Guide to Slowing YouTube Videos (37 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-troubleshooting-the-windows-camera-app/"><u>A Complete Guide to Troubleshooting the Windows Camera App</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/a-step-by-step-guide-on-turning-on-and-utilizing-your-oss-concealed-pathfinder-feature/"><u>A Step-by-Step Guide on Turning On & Utilizing Your OS's Concealed Pathfinder Feature</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/catching-every-gadget-reveal-viewing-samsungs-unpacked-ceremony-on-the-web/"><u>Catching Every Gadget Reveal: Viewing Samsung's Unpacked Ceremony on the Web</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/choosing-your-phone-companion-iphone-or-android-the-ultimate-comparison/"><u>Choosing Your Phone Companion: IPhone or Android - The Ultimate Comparison</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comparing-cosmic-universes-metaverse-vs-multiverse-explained/"><u>Comparing Cosmic Universes  Metaverse vs Multiverse Explained</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-guide-to-public-no-cost-domain-name-systems/"><u>Comprehensive Guide to Public, No-Cost Domain Name Systems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-tutorial-on-turning-on-browser-cookies/"><u>Comprehensive Tutorial on Turning On Browser Cookies</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/demystifying-memes-everything-you-need-to-know/"><u>Demystifying Memes: Everything You Need to Know</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/differences-between-signal-and-whatsapp-which-is-more-secure-for-your-chats/"><u>Differences Between Signal and WhatsApp – Which Is More Secure for Your Chats?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-latest-budget-friendly-study-apps-for-students-preparing-for-school/"><u>Discover the Latest Budget-Friendly Study Apps for Students Preparing for School</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/easy-tips-and-tricks-taking-a-screenshot-on-your-hp-notebook/"><u>Easy Tips & Tricks - Taking a Screenshot on Your HP Notebook</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ended-device-drive-error-43/"><u>Ended Device Drive Error #43</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/facebook-multi-photo-upload-tutorial-streamline-posting-several-pictures-simultaneeously/"><u>Facebook Multi-Photo Upload Tutorial: Streamline Posting Several Pictures Simultaneeously.</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-electric-cars-unlock-free-benefits-hov-lane-privileges-and-dedicated-parking-spaces/"><u>How Electric Cars Unlock Free Benefits: HOV Lane Privileges and Dedicated Parking Spaces</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-xiaomi-13t-pro-easily-by-drfone-android/"><u>How To Unlock a Xiaomi 13T Pro Easily?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-can-you-unlock-apple-iphone-8-after-forgetting-the-passcode-by-drfone-ios/"><u>In 2024, Can You Unlock Apple iPhone 8 After Forgetting the Passcode?</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-channel-labeling-101-how-to-make-yourself-hard-to-ignore/"><u>In 2024, Channel Labeling 101  How to Make Yourself Hard to Ignore</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-motorola-edge-40-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-realme-12-proplus-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Realme 12 Pro+ 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/instagram-personalization-how-to-disable-recommended-user-tags/"><u>Instagram Personalization: How to Disable Recommended User Tags</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ipad-cracked-open-methods-for-no-code-entry-solutions/"><u>IPad Cracked Open: Methods for No-Code Entry Solutions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/leverage-ai-to-improve-teamwork-incorporating-github-copilot-in-your-microsoft-teams-operations/"><u>Leverage AI to Improve Teamwork: Incorporating GitHub Copilot in Your Microsoft Teams Operations</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/macos-15-sequoia-is-coming-find-out-the-announcement-date-enhancements-and-latest-updates/"><u>MacOS 15 Sequoia Is Coming: Find Out the Announcement Date, Enhancements & Latest Updates!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-service-policies-a-deep-dive-into-usage-guidelnates/"><u>Navigating Service Policies: A Deep Dive Into Usage Guidelnates</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/next-gen-gaming-faceoff-evaluating-sonys-ps5-slim-against-the-full-ps5-model/"><u>Next-Gen Gaming Faceoff: Evaluating Sony's PS5 Slim Against the Full PS5 Model</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/no-more-buffering-defeat-the-netflix-error-code-nw-1-19-with-these-proven-solutions/"><u>No More Buffering: Defeat the Netflix Error Code NW-1-19 with These Proven Solutions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/reactivate-iphone-notifications-steps-to-address-the-non-ringing-problem/"><u>Reactivate iPhone Notifications: Steps to Address the Non-Ringing Problem</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/reactivate-the-shadows-steps-to-recover-facebooks-dimmed-display-settings/"><u>Reactivate the Shadows: Steps to Recover Facebook's Dimmed Display Settings</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/1723052251129-regularly-back-up-wallet-data-and-store-private-keys-securely-offline-to-prevent-unauthorized-access/"><u>Regularly Back up Wallet Data and Store Private Keys Securely Offline to Prevent Unauthorized Access.</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/sneak-peek-at-upcoming-oxygenos-device-estimated-prices-arrival-dates-and-potential-features-discussed/"><u>Sneak Peek at Upcoming OxygenOS Device: Estimated Prices, Arrival Dates & Potential Features Discussed</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solve-common-issues-by-learning-how-to-factory-reset-your-samsung-tv-model/"><u>Solve Common Issues by Learning How to Factory Reset Your Samsung TV Model.</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-the-issue-steps-to-successfully-restart-your-non-responsive-airpods/"><u>Solving the Issue: Steps to Successfully Restart Your Non-Responsive AirPods</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-setting-up-your-oculus-questquest-cuaccount/"><u>Step-by-Step Guide: Setting Up Your Oculus Quest/Quest cuAccount</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-setting-up-your-samsung-soundbar-with-television/"><u>Step-by-Step Guide: Setting Up Your Samsung Soundbar with Television</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-instrucuions-leveraging-slack-for-time-management-with-custom-reminders/"><u>Step-by-Step Instrucuions: Leveraging Slack for Time Management with Custom Reminders</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/strategies-for-discerning-genuine-contacts-from-impostor-link-requests-on-social-platforms/"><u>Strategies for Discerning Genuine Contacts From Impostor Link Requests on Social Platforms</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-definitive-trick-to-effortlessly-sync-up-your-bose-soundlink-system/"><u>The Definitive Trick to Effortlessly Sync Up Your Bose Soundlink System</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-next-leap-in-smartphone-innovation-expected-price-technical-details-and-release-window-for-upcoming-foldable-iphone-revealed/"><u>The Next Leap in Smartphone Innovation: Expected Price, Technical Details, & Release Window for Upcoming Foldable iPhone Revealed</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-perfect-viewing-order-enjoy-the-conjuring-series-step-by-step/"><u>The Perfect Viewing Order: Enjoy the 'Conjuring' Series Step by Step</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-fix-for-when-mfplatdll-wont-load-your-go-to-resource/"><u>The Ultimate Fix for When mfplat.dll Won’t Load: Your Go-To Resource</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-selection-of-12-free-movie-streaming-websites/"><u>The Ultimate Selection of 12 Free Movie Streaming Websites</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722883827890-troubleshoot-hulus-rununk13-issue-with-these-easy-fixes/"><u>Troubleshoot Hulu's RUNUNK13 Issue with These Easy Fixes!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-tutorial-easy-techniques-to-screen-capture-like-a-pro/"><u>Ultimate Tutorial: Easy Techniques to Screen Capture Like a Pro</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-efficiency-top-5-tactics-for-maximizing-your-facebook-usage/"><u>Unlocking Efficiency: Top 5 Tactics for Maximizing Your Facebook Usage</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-sony-2024-forecast-major-releases-industry-news-and-insider-details/"><u>Unveiling Sony 2024 Forecast: Major Releases, Industry News & Insider Details</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-latest-windows-enhancements-service-pack-details-for-july-2024/"><u>Unveiling the Latest Windows Enhancements - Service Pack Details for July 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Motorola Edge 40 Neo? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/what-to-do-when-your-automot-grooves-audio-system-abruptly-fails/"><u>What To Do When Your Automot Groove's Audio System Abruptly Fails</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/what-to-expect-at-the-upcoming-apple-event-schedule-details-hottest-gossip-and-full-insights/"><u>What to Expect at the Upcoming Apple Event: Schedule Details, Hottest Gossip, and Full Insights</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/wwdc-2025-sneak-peek-latest-apple-innovations-and-exclusive-updates-revealed/"><u>WWDC 2025 Sneak Peek: Latest Apple Innovations & Exclusive Updates Revealed</u></a></li>
</ul></div>
