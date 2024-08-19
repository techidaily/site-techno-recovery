---
title: "Simple Solutions: Getting Support and Assistance on Windows 11"
date: 2024-08-18T16:38:49.287Z
updated: 2024-08-19T16:38:49.287Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Simple Solutions: Getting Support and Assistance on Windows 11"
excerpt: "This Article Describes Simple Solutions: Getting Support and Assistance on Windows 11"
thumbnail: https://thmb.techidaily.com/db7b5b29f3dd85ab1439e42aeefbd0af6cf9e882cf1c9c7fcb2a6858953bbb8e.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://facebook-video-share.techidaily.com/new-making-the-most-out-of-creative-commons-licenses/"><u>[New] Making the Most Out of Creative Commons Licenses</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-peekpoint-analysis-a-guide/"><u>[New] Peekpoint Analysis  A Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-enhanced-game-recorders-beyond-fbx-frameworks/"><u>[Updated] Enhanced Game Recorders Beyond FBX Frameworks</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-essential-budget-gaming-hardware-the-ultimate-keyboard-list/"><u>[Updated] Essential Budget Gaming Hardware  The Ultimate Keyboard List</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-demystifying-the-journey-to-knowing-who-watches-you/"><u>[Updated] In 2024, Demystifying the Journey to Knowing Who Watches You</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/android-phone-settings-how-to-deactivate-amber-and-other-emergency-alerts/"><u>Android Phone Settings: How to Deactivate AMBER and Other Emergency Alerts</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/chronological-watchlist-for-all-the-man-of-steel-pictures/"><u>Chronological Watchlist for All The Man of Steel Pictures</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-guide-to-adjusting-network-discovery-options-on-windows-11-systems/"><u>Comprehensive Guide to Adjusting Network Discovery Options on Windows 11 Systems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/easy-ways-to-caption-visual-content-in-instagrams-featured-segment/"><u>Easy Ways to Caption Visual Content in Instagram's Featured Segment</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/educators-guide-top-screen-capture-tools/"><u>Educator's Guide  Top Screen Capture Tools</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-methods-for-diagnosing-and-correcting-kernel32dll-failures-in-windows-systems/"><u>Effective Methods for Diagnosing and Correcting Kernel32.dll Failures in Windows Systems</u></a></li>
<li><a href="https://screen-capture.techidaily.com/emulate-elegance-the-premier-selection-of-ps1-emulators-for-pc/"><u>Emulate Elegance  The Premier Selection of PS1 Emulators for PC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/enhance-file-handling-effective-methods-for-transferring-to-your-computer-for-2024/"><u>Enhance File Handling  Effective Methods for Transferring to Your Computer for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-advice-resolving-issues-with-non-ejectable-dvd-bd-and-cd-drives/"><u>Expert Advice: Resolving Issues with Non-Ejectable DVD, BD & CD Drives</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-tips-on-how-to-address-and-repair-the-missing-binkw32dll-error/"><u>Expert Tips on How to Address and Repair the Missing BinkW32.dll Error</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/explore-our-carefully-curated-top-8-learning-apps-set-to-dominate-the-digital-classroom/"><u>Explore Our Carefully Curated Top 8 Learning Apps Set to Dominate the Digital Classroom</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-the-contrast-understanding-ht-amps-versus-stereo-systems-for-your-living-space/"><u>Exploring the Contrast: Understanding HT Amps Versus Stereo Systems for Your Living Space</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-the-world-of-live-tv-boxes-unveiling-what-streamers-really-mean/"><u>Exploring the World of Live TV Boxes: Unveiling What Streamers Really Mean</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/fixing-the-stop-0x0000001d-error-for-smooth-computer-operations/"><u>Fixing the STOP 0X0000001D Error for Smooth Computer Operations</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/free-film-feast-must-watch-movies-on-youtube-in-july-2024-our-recommendations/"><u>Free Film Feast: Must-Watch Movies on YouTube in July 2024 - Our Recommendations</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-can-you-relocate-your-digital-photograph-collection-google-photos-to-icloud/"><u>How Can You Relocate Your Digital Photograph Collection: Google Photos to iCloud?</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-apple-iphone-6-plus-location-on-viber-drfone-by-drfone-virtual-ios/"><u>How to Change/Fake Your Apple iPhone 6 Plus Location on Viber | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-determine-another-individuals-place-on-an-iphone-expert-tips/"><u>How to Determine Another Individual's Place on an iPhone: Expert Tips</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-enable-or-disable-the-on-screen-keyboard-in-windows-10/"><u>How to Enable or Disable the On-Screen Keyboard in Windows 10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-vivo-y100-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Vivo Y100 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-hailing-a-cab-still-cheaper-than-booking-an-uber-the-price-comparison/"><u>Is Hailing a Cab Still Cheaper than Booking an Uber? The Price Comparison</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/keep-your-snaps-alive-strategies-for-longevity-for-2024/"><u>Keep Your Snaps Alive – Strategies for Longevity for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/most-popular-apps-for-your-samsung-smart-tv/"><u>Most Popular Apps for Your Samsung Smart TV</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-the-media-maze-exploring-key-variations-between-cable-and-streaming-technologies/"><u>Navigating the Media Maze: Exploring Key Variations Between Cable and Streaming Technologies</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-2024-approved-how-to-make-a-photo-collage-on-maciphone-using-iphoto/"><u>New 2024 Approved How to Make a Photo Collage on Mac/iPhone Using iPhoto?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/plan-your-harry-potter-film-journey-from-start-to-finish/"><u>Plan Your Harry Potter Film Journey From Start to Finish</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/proven-strategies-for-wiping-out-your-pcs-recovery-volume-on-a-windows-operating-system/"><u>Proven Strategies for Wiping Out Your PC’s Recovery Volume on a Windows Operating System</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/seamlessly-transition-to-x-instructions-for-formerly-twitter-users/"><u>Seamlessly Transition to X: Instructions for Formerly Twitter Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solution-guide-why-are-some-emails-not-coming-to-your-yahoo-mail/"><u>Solution Guide: Why Are Some Emails Not Coming to Your Yahoo Mail?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-to-taming-your-inbox-mastering-gmail-labels/"><u>Step-by-Step Guide to Taming Your Inbox: Mastering Gmail Labels</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-tutorial-discover-how-to-turn-on-the-invisible-file-explorer-path/"><u>Step-by-Step Tutorial: Discover How to Turn On the Invisible File Explorer Path</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-complete-walkthrough-for-syncing-a-subwoofer-and-enhancing-soundscape-on-samsungs-soundbar/"><u>The Complete Walkthrough for Syncing a Subwoofer and Enhancing Soundscape on Samsung's Soundbar</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-essentials-of-output-impedance-explained-simply/"><u>The Essentials of Output Impedance Explained Simply</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-future-is-here-apple-watch-ultra-teaser-analysis-with-price-estimates-release-windows-and-leaked-specs/"><u>The Future Is Here: Apple Watch Ultra Teaser Analysis with Price Estimates, Release Windows and Leaked Specs</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-list-8-favorite-ebook-reader-apps/"><u>The Ultimate List: 8 Favorite eBook Reader Apps</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-rated-cell-phone-trade-in-offers-on-verizon-this-month/"><u>Top-Rated Cell Phone Trade-In Offers on Verizon This Month</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-tips-for-discs-drives-that-wont-open-dvd-blu-ray-and-cd-fixes/"><u>Troubleshooting Tips for Discs Drives That Won't Open: DVD, Blu-Ray & CD Fixes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-troubleshooting-guide-solving-your-zoom-camera-issues/"><u>Ultimate Troubleshooting Guide: Solving Your Zoom Camera Issues</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-nintendo-switch-online-disruptions-identifying-if-the-problem-lies-with-the-service-or-your-connection/"><u>Understanding Nintendo Switch Online Disruptions: Identifying if the Problem Lies with the Service or Your Connection</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/unlocking-potential-with-ai-essential-uses-of-chatgpt-for-companies/"><u>Unlocking Potential with AI: Essential Uses of ChatGPT for Companies</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-world-of-streaming-devices-what-are-they/"><u>Unveiling the World of Streaming Devices: What Are They?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/what-is-the-telegram-app/"><u>What Is the Telegram App?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->