---
title: "Clear Your Mac's DNS History: A Comprehensive How-To Tutorial"
date: 2024-08-30T13:20:51.601Z
updated: 2024-08-31T13:20:51.601Z
categories:
  - BestProducts
description: "This Article Describes Clear Your Mac's DNS History: A Comprehensive How-To Tutorial"
excerpt: "This Article Describes Clear Your Mac's DNS History: A Comprehensive How-To Tutorial"
thumbnail: https://thmb.techidaily.com/50b8c0240239aa64db52b1f5d6c9798f04334cb3acf289ccfe4f5fa8ce22d8a0.jpg
---

## Clear Your Mac's DNS History: A Comprehensive How-To Tutorial
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## What Does Flushing DNS Do?

 Each time you access a website in your web browser, the URL you enter is sent to a[DNS server](https://www.lifewire.com/what-is-a-dns-server-2625854) for translation into an[IP address](https://www.lifewire.com/what-is-an-ip-address-2625920) . This information is stored in a cache on your Mac for easy retrieval in the future, hence the term_DNS cache_ .

 When you try to access a website you’ve been to recently, your Mac uses its DNS cache instead of checking with an actual DNS server. The web browser doesn’t have to go through the extra step of communicating with a remote DNS server, which results in less time between entering a website address and the website loading.

 If the local DNS cache is corrupt or outdated, it’s kind of like trying to use an old phone book that's been vandalized. Your web browser checks the cache to find an IP address for the website you’re trying to visit, and it finds either the wrong address or an unusable one. This can slow the process down or prevent websites or specific web page elements, like videos, from loading.

 When you flush your DNS cache, you instruct your Mac to delete its local DNS records. This in turn forces your web browser to check with a DNS server for fresh information. You should always flush your DNS cache after[changing the DNS servers on your Mac](https://www.lifewire.com/network-preference-pane-change-macs-dns-settings-2260394) . It can also be helpful if you’re having connectivity problems.  

 FAQ

* How do I check the DNS cache on a Mac?  
 Open the built-in Console log-viewer app on your Mac and type**any:mdnsresponder** into the search bar. Then, launch Terminal, type in**sudo killall –INFO mDNSResponder** , and press**Enter** or**Return** . Back in the Console app, you can view a list of cached DNS records.
* How do I clear the DNS cache on Windows 10?  
 To[clear the DNS cache on Windows 10](https://www.lifewire.com/flush-and-clear-windows-dns-cache-5095298) , open the Run dialog box, type in**ipconfig /flushdns** , and click**OK** . You can also use the same command in the Windows command prompt if you want more information on the process.
* What is DNS cache poisoning?  
 DNS cache poisoning, also known as DNS spoofing, is when someone deliberately enters false or incorrect information into a DNS cache. After the false information is input, future DNS queries will return incorrect responses and direct users to the wrong websites.

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
<li><a href="https://fox-direct.techidaily.com/new-heartstrings-harmony-best-music-to-accompany-your-engagement/"><u>[New] Heartstrings Harmony  Best Music to Accompany Your Engagement</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-the-guide-to-earning-through-streams-dm-and-yo-unveiled/"><u>[New] In 2024, The Guide to Earning Through Streams  Dm & Yo Unveiled</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-nailing-the-perfect-capture-mac-tips-for-screencasting-streamed-video-for-2024/"><u>[New] Nailing the Perfect Capture  Mac Tips for Screencasting Streamed Video for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/2024s-leading-console-platforms-for-gamers/"><u>2024'S Leading Console Platforms for Gamers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comparing-iphone-15-pro-max-with-samsung-galaxy-s24-ultra-key-distinctions-revealed/"><u>Comparing iPhone 15 Pro Max with Samsung Galaxy S24 Ultra: Key Distinctions Revealed</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/complete-guide-to-clearing-your-inbox-on-the-gmail-mobile-application/"><u>Complete Guide to Clearing Your Inbox on the Gmail Mobile Application</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/complete-walkthrough-on-how-to-permanently-remove-your-tiktok-profile/"><u>Complete Walkthrough on How to Permanently Remove Your TikTok Profile</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/diagnosing-and-repairing-common-errors-with-microsoft-outlooks-spell-check-utility/"><u>Diagnosing and Repairing Common Errors with Microsoft Outlook's Spell Check Utility</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-guide-organizing-your-files-with-custom-finder-preferences/"><u>Effective Guide: Organizing Your Files with Custom Finder Preferences</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/effortless-instant-collage-techniques-for-facebook-pages/"><u>Effortless Instant Collage Techniques for Facebook Pages</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/elevate-expression-with-audio-in-statuses-for-2024/"><u>Elevate Expression with Audio in Statuses for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-link-disneyplus-to-chromecast-for-hassle-free-viewing/"><u>How To Link Disney+ to Chromecast for Hassle-Free Viewing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-refresh-and-revamp-your-powerpoint-slides-with-ease/"><u>How To Refresh & Revamp Your PowerPoint Slides With Ease</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-quickfirerecorder-firefox-plugin/"><u>In 2024, QuickFireRecorder Firefox Plugin</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/in-depth-look-at-metaquest-3-anticipated-release-dates-cost-analysis-and-hardware-specs-revealed/"><u>In-Depth Look at MetaQuest 3: Anticipated Release Dates, Cost Analysis, and Hardware Specs Revealed</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/master-the-process-of-flushing-and-restoring-your-systems-bios-configuration-with-cmos-clears/"><u>Master the Process of Flushing and Restoring Your System's BIOS Configuration with CMOS Clears</u></a></li>
<li><a href="https://windows11.techidaily.com/master-windows-performance-with-extended-display-setup/"><u>Master Window's Performance With Extended Display Setup</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-art-of-monitoring-your-data-plans-utilization-online/"><u>Mastering the Art of Monitoring Your Data Plan's Utilization Online</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigate-your-journey-with-these-top-8-travel-planner-tools/"><u>Navigate Your Journey with These Top 8 Travel Planner Tools</u></a></li>
<li><a href="https://facebook.techidaily.com/picturing-a-love-story-how-facebook-changes-dating-dynamics/"><u>Picturing a Love Story: How Facebook Changes Dating Dynamics</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/powerless-to-start-a-guide-to-repairing-computers-with-no-electrical-response/"><u>Powerless to Start? A Guide to Repairing Computers With No Electrical Response</u></a></li>
<li><a href="https://video-capture.techidaily.com/professional-macbook-webcam-capture-techniques-guide-for-2024/"><u>Professional MacBook Webcam Capture Techniques Guide for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/questband-meta-series-latest-updates-on-features-pricing-and-launch-timeline/"><u>QuestBand Meta Series - Latest Updates on Features, Pricing & Launch Timeline</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-infinix-note-30-vip-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Infinix Note 30 VIP Screen | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-the-mingwm1n10dll-file-not-found-issue-a-step-by-step-guide/"><u>Resolving the 'Mingwm1n10.dll File Not Found' Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/simplifying-email-management-how-to-automate-sorting-in-gmail-with-personalized-rules/"><u>Simplifying Email Management: How to Automate Sorting in Gmail With Personalized Rules</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/stay-on-top-of-your-fitness-goals-with-these-10-essential-exercise-logging-tools-in-amelie2024/"><u>Stay on Top of Your Fitness Goals with These 10 Essential Exercise Logging Tools in Amelie_2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-fix-for-windows-driver-issue-code-41-error-handling/"><u>Step-by-Step Fix for Windows Driver Issue - Code 41 Error Handling</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-to-repair-a-non-responsive-application-on-macos/"><u>Step-by-Step Guide to Repair a Non-Responsive Application on macOS</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-downloading-fandango-app-onto-your-firestick/"><u>Step-by-Step Guide: Downloading Fandango App Onto Your Firestick</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-guide-restoring-deleted-or-forgotten-emails-on-gmail/"><u>The Ultimate Guide: Restoring Deleted or Forgotten Emails on Gmail</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-picks-disneyplus-must-watch-films-of-the-moment/"><u>Top Picks: Disney+ Must-Watch Films of the Moment</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshoot-cant-be-opened-dev-cant-be-verified-solutions-for-mac-users/"><u>Troubleshoot 'Can’t Be Opened - Dev Can't Be Verified': Solutions for Mac Users</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-guide-fixing-call-of-duty-warzone-pc-crashes/"><u>Troubleshooting Guide: Fixing Call of Duty Warzone PC Crashes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-combining-your-favorite-songs-into-one-master-spotify-list/"><u>Ultimate Guide: Combining Your Favorite Songs Into One Master Spotify List</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlock-a-world-of-knowledge-17-prime-locations-for-free-books-online/"><u>Unlock a World of Knowledge: 17 Prime Locations for Free Books Online</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlock-the-power-of-google-gemini-with-these-tips/"><u>Unlock the Power of Google Gemini with These Tips</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-cost-savings-find-the-top-7-free-internet-fax-services/"><u>Unlocking Cost Savings: Find the Top 7 Free Internet Fax Services</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-magic-behind-internet-ready-television-sets/"><u>Unveiling the Magic Behind Internet-Ready Television Sets</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-the-ultimate-list-of-glitch-art-video-editors-for-mobile-devices/"><u>Updated The Ultimate List of Glitch Art Video Editors for Mobile Devices</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/viewing-someones-insta-without-an-account-what-you-need-to-know/"><u>Viewing Someone's Insta Without An Account: What You Need to Know</u></a></li>
</ul></div>
