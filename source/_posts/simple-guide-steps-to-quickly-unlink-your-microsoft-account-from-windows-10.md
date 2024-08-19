---
title: "Simple Guide: Steps to Quickly Unlink Your Microsoft Account From Windows 10"
date: 2024-08-18T16:42:12.321Z
updated: 2024-08-19T16:42:12.321Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Simple Guide: Steps to Quickly Unlink Your Microsoft Account From Windows 10"
excerpt: "This Article Describes Simple Guide: Steps to Quickly Unlink Your Microsoft Account From Windows 10"
thumbnail: https://thmb.techidaily.com/89441e52c524b595c11d3154d801c69d4c1e26e0cadba6aa4959212fd46b070e.jpg
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-unveil-the-power-of-vrecorder-installs-demystified/"><u>[New] In 2024, Unveil the Power of VRecorder  Installs Demystified</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-6-completely-different-places-to-get-youtube-icons-and-logos-for-2024/"><u>[Updated] 6 Completely Different Places to Get YouTube Icons and Logos for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-easy-path-sending-fb-videos-to-whatsapp-contacts/"><u>[Updated] Easy Path  Sending FB Videos to WhatsApp Contacts</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-capture-every-click-essential-screen-recorders-for-modern-browsers/"><u>[Updated] In 2024, Capture Every Click  Essential Screen Recorders for Modern Browsers</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-no-displayed-video-fixing-camera-issue-with-sony-a6400-for-2024/"><u>[Updated] No Displayed Video  Fixing Camera Issue with Sony A6400 for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-maximizing-revenue-a-youtube-channelers-guide/"><u>2024 Approved  Maximizing Revenue  A YouTube Channeler’s Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/2024s-leading-edge-gaming-devices-a-comprehensive-guide/"><u>2024'S Leading Edge Gaming Devices - A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/75-times-smaller-and-fibonaccistuesday-we-need-to-ensure-that-individuals-withholding-the-right-handedness-of-ctrlplus123-mvn-but-i-wastingjuneau-is-an-unpu6/"><u>75 Times Smaller and Fibonacci_s/Tuesday, We Need to Ensure that Individuals Withholding the Right-Handedness of Ctrl+123 Mvn, but I Wasting=Juneau Is an Unpublished Researchers</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/a-comprehensive-guide-to-vyncs-analytics-suite-trustworthy-features-met-with-convoluted-payment-plans/"><u>A Comprehensive Guide to Vyncs Analytics Suite: Trustworthy Features Met with Convoluted Payment Plans</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/affordable-and-fast-ev-charge-stations-why-experts-say-powerdrive-tops-every-list-for-cost-effective-solutions/"><u>Affordable and Fast EV Charge Stations - Why Experts Say PowerDrive Tops Every List for Cost-Effective Solutions!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/before-you-decide-5-must-know-tips-when-selecting-refurbished-computers/"><u>Before You Decide: 5 Must-Know Tips When Selecting Refurbished Computers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-fixes-for-when-android-fails-to-sendreceive-messages/"><u>Comprehensive Fixes for When Android Fails to Send/Receive Messages</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-guide-to-understanding-netflix-as-a-digital-entertainment-hub/"><u>Comprehensive Guide to Understanding Netflix as a Digital Entertainment Hub</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/demystifying-bass-management-a-comprehensive-guide-on-operation-and-advantages/"><u>Demystifying Bass Management: A Comprehensive Guide on Operation & Advantages</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-techniques-for-handling-the-d3dx924dll-not-found-error/"><u>Effective Techniques for Handling the 'd3dx9_24.dll Not Found' Error</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/elevating-iphone-and-ipad-camera-performance-for-stunning-photos-and-videos/"><u>Elevating iPhone & iPad Camera Performance for Stunning Photos and Videos</u></a></li>
<li><a href="https://techtrends.techidaily.com/enhance-your-viewing-experience-linking-disney-plus-to-chromecast-in-minutes/"><u>Enhance Your Viewing Experience: Linking Disney Plus to Chromecast in Minutes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-tips-for-resetting-your-iphone-15-with-ease/"><u>Expert Tips for Resetting Your iPhone 15 with Ease</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-to-correcting-the-absent-libcurldll-mistake/"><u>Guide to Correcting the Absent Libcurl.dll Mistake</u></a></li>
<li><a href="https://extra-tips.techidaily.com/hdr-mastery-the-complete-sdr-to-hdr-transformation/"><u>HDR Mastery  The Complete SDR-to-HDR Transformation</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-resolve-the-frustrating-error-code-0xc0000185-a-step-by-step-guide/"><u>How to Resolve the Frustrating Error Code 0XC0000185: A Step-by-Step Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-seamlessly-migrate-windows-10-to-your-freshly-installed-hard-drive/"><u>How To Seamlessly Migrate Windows 10 to Your Freshly Installed Hard Drive</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-13-without-passcode-4-easy-methods-drfone-by-drfone-ios/"><u>How To Unlock iPhone 13 Without Passcode? 4 Easy Methods | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/inside-the-windows-10-battery-report-tool-expert-insights-for-optimal-performance/"><u>Inside the Windows 10 Battery Report Tool: Expert Insights for Optimal Performance</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/julys-must-watch-a-collection-of-top-free-movies-available-on-youtube/"><u>July's Must-Watch: A Collection of Top Free Movies Available on YouTube</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-google-gemini-a-comprehensive-tutorial/"><u>Mastering Google Gemini: A Comprehensive Tutorial</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-to-your-personalized-apple-support-session-booking-tips-inside/"><u>Navigating to Your Personalized Apple Support Session - Booking Tips Inside</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/protecting-your-email-from-spam-the-definitive-guide-to-gmail-safelisting-techniques/"><u>Protecting Your Email From Spam: The Definitive Guide to Gmail Safelisting Techniques</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/quick-and-effective-methods-how-to-locate-anyone-on-facebook-with-minimal-effort/"><u>Quick and Effective Methods: How to Locate Anyone on Facebook with Minimal Effort</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/radio-praha/"><u>Radio Praha</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/setting-up-and-using-twitch-two-factor-authentication-2fa-a-comprehensive-guide/"><u>Setting Up & Using Twitch Two-Factor Authentication (2FA): A Comprehensive Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/side-by-side-review-unveiling-differences-between-ipad-mini-and-ipad-air/"><u>Side-by-Side Review: Unveiling Differences Between iPad Mini & iPad Air</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/simplifying-mobile-commerce-your-complete-tutorial-on-activating-and-utilizing-apple-pay-on-an-apple-watch/"><u>Simplifying Mobile Commerce: Your Complete Tutorial on Activating and Utilizing Apple Pay on an Apple Watch</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-the-problem-when-your-nintendo-wii-cant-play-discs-anymore/"><u>Solving the Problem: When Your Nintendo Wii Can’t Play Discs Anymore</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/step-by-step-instruction-on-downloading-installing-and-using-ez-grabber-for-2024/"><u>Step-by-Step Instruction on Downloading, Installing & Using EZ Grabber for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/syncing-screens-a-comprehensive-guide-to-using-airplay-with-a-macbook-and-television/"><u>Syncing Screens: A Comprehensive Guide to Using AirPlay with a MacBook & Television</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-insider-guide-to-efficient-windows-10-usage-for-2024/"><u>The Insider Guide to Efficient Windows 10 Usage for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-guide-to-experience-star-wars-saga-in-order-on-disney-plus/"><u>The Ultimate Guide to Experience Star Wars Saga - In Order, On Disney Plus</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-zte-axon-40-lite-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your ZTE Axon 40 Lite Phone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-5-encrypted-email-providers-to-protect-your-privacy/"><u>Top 5 Encrypted Email Providers to Protect Your Privacy</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-picks-must-watch-lgbtq-series-on-netflix-in-july-2024/"><u>Top Picks: Must-Watch LGBTQ Series on Netflix in July 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-loud-computer-fans-tips-for-silent-operation-restoration/"><u>Troubleshooting Loud Computer Fans – Tips for Silent Operation Restoration</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-secret-mac-folders-with-terminal-commands/"><u>Unlocking Secret Mac Folders with Terminal Commands</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-hidden-treasures-discover-these-incredible-emoji-secrets/"><u>Unveiling Hidden Treasures: Discover These Incredible Emoji Secrets</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-honor-100-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Honor 100 Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/zoom-version-update-guide-for-windows-and-mac-users-quick-fixes-and-tips/"><u>Zoom Version Update Guide for Windows and Mac Users - Quick Fixes & Tips</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->