---
title: "Solving the Windows Update Error: Code 0X80070005 - Access Denied"
date: 2024-08-18T16:36:35.391Z
updated: 2024-08-19T16:36:35.391Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Solving the Windows Update Error: Code 0X80070005 - Access Denied"
excerpt: "This Article Describes Solving the Windows Update Error: Code 0X80070005 - Access Denied"
thumbnail: https://thmb.techidaily.com/e03e7f36869e1845d154715bfdea777a291cb2eaca41f020a72559cf27e30f77.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-compact-video-summary-key-insights-unveiled/"><u>[New] 2024 Approved  Compact Video Summary  Key Insights Unveiled</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-playlist-extraction-made-simple-download-steps-revealed/"><u>[New] 2024 Approved  Playlist Extraction Made Simple  Download Steps Revealed</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ow-to-effortlessly-eradicate-unwanted-youtube-post-comments-for-2024/"><u>[New] How to Effortlessly Eradicate Unwanted Youtube Post-Comments for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-capturing-android-sounds-without-root-access-guide/"><u>[New] In 2024, Capturing Android Sounds Without Root Access [Guide]</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-three-key-strategies-to-frame-your-insta-films-better-for-2024/"><u>[New] Three Key Strategies to Frame Your Insta Films Better for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-top-10-hd-webcams-essential-purchasing-tips-for-2024/"><u>[New] Top 10 HD Webcams  Essential Purchasing Tips for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-propel-your-profile-5-core-techniques-for-instagram-marketing-gurus/"><u>[Updated] 2024 Approved  Propel Your Profile  5 Core Techniques for Instagram Marketing Gurus</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-inquiry-exploring-shared-videos-and-images-in-direct-conversations/"><u>[Updated] In 2024, Inquiry  Exploring Shared Videos & Images in Direct Conversations</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-the-great-livestream-showdown-streamlabs-vs-obs-head-to-head/"><u>[Updated] In 2024, The Great Livestream Showdown  Streamlabs Vs. OBS Head-to-Head</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-inside-vitas-advanced-video-editing-tools-full-review-and-expert-tutorial-2024/"><u>[Updated] Inside Vita's Advanced Video Editing Tools  Full Review & Expert Tutorial 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-the-ultimate-guide-for-streamlining-iphone-video-content/"><u>[Updated] The Ultimate Guide for Streamlining iPhone Video Content</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-optimal-sites-for-pixel-sounds/"><u>[Updated] Unveiling Optimal Sites for Pixel Sounds</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-captivating-hdr-portraits-for-the-art-enthusiast/"><u>2024 Approved  Captivating HDR Portraits for the Art Enthusiast</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-virtual-screens-the-ultimate-guide/"><u>2024 Approved  Virtual Screens  The Ultimate Guide</u></a></li>
<li><a href="https://buynow-info.techidaily.com/2024s-premier-pathways-to-becoming-a-pro-coder-from-home/"><u>2024'S Premier Pathways to Becoming a Pro Coder From Home</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-strategies-for-overcoming-haldll-problems-in-windows-os-variants/"><u>Comprehensive Strategies for Overcoming Hal.dll Problems in Windows OS Variants</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effective-strategies-for-distributing-your-conversations-with-chatgpt-online/"><u>Effective Strategies for Distributing Your Conversations with ChatGPT Online</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-strategies-for-resolving-opening-errors-in-macos-programs/"><u>Effective Strategies for Resolving Opening Errors in macOS Programs</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/excel-mastery-a-step-by-step-guide-to-merging-two-spreadsheets/"><u>Excel Mastery: A Step-by-Step Guide to Merging Two Spreadsheets</u></a></li>
<li><a href="https://techtrends.techidaily.com/exciting-mobile-adventures-top-puzzle-games-similar-to-the-room-and-myst/"><u>Exciting Mobile Adventures: Top Puzzle Games Similar to 'The Room' & 'Myst'</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/explore-these-4-amazing-complimentary-web-based-schedulers/"><u>Explore These 4 Amazing Complimentary Web-Based Schedulers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/fixing-the-lib4eay32dll-file-not-found-effective-troubleshooting-techniques/"><u>Fixing the lib4eay32.dll File Not Found: Effective Troubleshooting Techniques</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-can-i-retrieve-my-lost-email-address/"><u>How Can I Retrieve My Lost Email Address?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-does-dts-play-fi-enhance-your-listening/"><u>How Does DTS Play-Fi Enhance Your Listening?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-vivo-y78t-by-drfone-android/"><u>How to Bypass FRP on Vivo Y78t?</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/how-to-craft-standout-names-for-your-youtube-channel/"><u>How to Craft Standout Names for Your YouTube Channel</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-google-pixel-fold-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Google Pixel Fold Quickly? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-reset-another-users-password-securely-on-a-windows-computer/"><u>How to Reset Another User's Password Securely on a Windows Computer</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-resolve-the-issue-when-mfc4dll-is-absent-or-cannot-be-located/"><u>How to Resolve the Issue When Mfc4^_dll Is Absent or Cannot Be Located</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-restore-mscorwksdll-and-solve-system-compatibility-issues/"><u>How to Restore 'Mscorwks.dll' And Solve System Compatibility Issues</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-vivo-y100i-power-5g-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Vivo Y100i Power 5G to Apple TV | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-battle-tactics-against-lynels-in-breath-of-the-wild/"><u>Mastering Battle Tactics Against Lynels in Breath of the Wild</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/most-sought-after-game-platforms-2024-edition/"><u>Most Sought-After Game Platforms: 2024 Edition</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-the-road-ahead-key-questions-before-going-electric/"><u>Navigating the Road Ahead: Key Questions Before Going Electric</u></a></li>
<li><a href="https://article-posts.techidaily.com/pristine-movie-trailer-curated-list/"><u>Pristine Movie Trailer Curated List</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pushing-the-envelope-in-color-correction-top-10-luts-for-lightroom-experts/"><u>Pushing the Envelope in Color Correction  Top 10 LUTs For Lightroom Experts</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/samsung-tv-troubleshooting-guide-changing-from-default-browser-to-an-alternative-one/"><u>Samsung TV Troubleshooting Guide: Changing From Default Browser to an Alternative One</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/splish-splash-with-tech-understanding-the-wet-test-results-for-your-iphone-15/"><u>Splish Splash with Tech: Understanding the Wet Test Results for Your iPhone 15</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/spotify-mastery-the-ultimate-tutorial-for-blending-multiple-playlists-into-one/"><u>Spotify Mastery: The Ultimate Tutorial for Blending Multiple Playlists Into One</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-rebooting-your-macbook-pro-efficiently/"><u>Step-by-Step Guide: Rebooting Your MacBook Pro Efficiently</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-solutions-to-stop-subwoofer-feedback/"><u>Step-by-Step Solutions to Stop Subwoofer Feedback</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/thaw-out-a-stuck-chromebook-eight-effective-remedies-to-try/"><u>Thaw Out a Stuck Chromebook: Eight Effective Remedies to Try</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-how-to-on-reviving-a-disabled-snapchat-username/"><u>The Ultimate How-To on Reviving a Disabled Snapchat Username</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722879678133-the-ultimate-ranking-of-smart-spectacles-find-your-perfect-pair/"><u>The Ultimate Ranking of Smart Spectacles – Find Your Perfect Pair!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-80s-cinema-hits-essential-movies-from-the-decade-to-stream-today/"><u>Top 80S Cinema Hits: Essential Movies From the Decade to Stream Today</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-realme-narzo-n55-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Realme Narzo N55 Screen | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-tips-for-when-you-cant-find-normalizdll-on-your-pc/"><u>Troubleshooting Tips for When You Can’t Find Normaliz.dll on Your PC</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-tips-restoring-functionality-to-outlooks-missing-spellcheck-feature/"><u>Troubleshooting Tips: Restoring Functionality to Outlook's Missing Spellcheck Feature</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-connecting-your-samsung-universal-remote-with-any-television/"><u>Ultimate Guide: Connecting Your Samsung Universal Remote with Any Television</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-duckduckgo-exploring-its-features-and-security/"><u>Understanding DuckDuckGo: Exploring Its Features & Security</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unraveling-filmora-editing-inquiries-for-2024/"><u>Unraveling Filmora Editing Inquiries for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/upcoming-launch-of-google-pixel-tablet-detailed-timeline-features-and-specifications/"><u>Upcoming Launch of Google Pixel Tablet: Detailed Timeline, Features & Specifications</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722889881829-whats-new-dive-into-the-features-of-applee-latest-ipad-genius/"><u>What's New ? Dive Into the Features of Apple'e Latest iPad Genius</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/yahoo-mail-not-receiving-emails-heres-how-you-can-fix-it/"><u>Yahoo Mail Not Receiving Emails? Here’s How You Can Fix It!</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/zoom-your-stories-to-attention-on-instagram-for-2024/"><u>Zoom Your Stories to Attention on Instagram for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->