---
title: "Solving System Lock-Up: Freezing Issues on Windows 10 Devices"
date: 2024-08-18T16:45:27.671Z
updated: 2024-08-19T16:45:27.671Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Solving System Lock-Up: Freezing Issues on Windows 10 Devices"
excerpt: "This Article Describes Solving System Lock-Up: Freezing Issues on Windows 10 Devices"
thumbnail: https://thmb.techidaily.com/2e909ca12d5d0ef3819e924e4b2acc53554680366614c69f27f338ed1d92d5d7.jpg
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-comparing-the-costs-and-advantages-of-various-youtube-plans/"><u>[New] 2024 Approved  Comparing the Costs and Advantages of Various YouTube Plans</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-avoid-the-backtrack-blunder-with-these-tips-for-2024/"><u>[New] Avoid the Backtrack Blunder with These Tips for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-hacking-the-meme-game-master-kinemaster-skills/"><u>[New] Hacking the Meme Game  Master KineMaster Skills</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-what-does-pfp-mean-in-tiktok-a-complete-guide/"><u>[New] In 2024, What Does PFP Mean in TikTok?[A Complete Guide]</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-virtual-identity-your-metaverse-persona-creation-companion/"><u>[New] Mastering Virtual Identity  Your Metaverse Persona Creation Companion</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-prime-tools-for-pro-video-creation-on-android-windows-for-2024/"><u>[New] Prime Tools for Pro Video Creation on Android, Windows for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-skys-best-the-ultimate-hd-collection-websites/"><u>[New] Sky's Best - The Ultimate HD Collection Websites</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-superior-economical-live-camera-snapper/"><u>[New] Superior Economical Live Camera Snapper</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-windows-11-essential-steps-for-audio-recording-for-2024/"><u>[New] Windows 11  Essential Steps for Audio Recording for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-how-to-use-io-screen-recorder/"><u>[Updated] 2024 Approved  How to Use IO Screen Recorder</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-unlocking-visual-potential-perfect-aspect-ratios-revealed/"><u>[Updated] 2024 Approved  Unlocking Visual Potential  Perfect Aspect Ratios Revealed</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/akko-mod007b-board-insights-for-serious-gaming/"><u>Akko MOD007B Board Insights for Serious Gaming</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-visual-synopsis-creator/"><u>Audio Visual Synopsis Creator</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/beaming-performance-spk10-037-light-kit-sets-standard-high/"><u>Beaming Performance: SPK10-037 Light Kit Sets Standard High</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/best-reading-apps-of-2024-picked-by-us-top-8-selections/"><u>Best Reading Apps of 2024 (Picked by Us) - Top 8 Selections</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-strategies-to-drop-multiple-geo-tags-in-google-maps/"><u>Comprehensive Strategies to Drop Multiple Geo-Tags in Google Maps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-curve-concepts-for-text-visualization-for-2024/"><u>Crafting Curve Concepts for Text Visualization for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/customize-your-typography-adjusting-fonts-in-windows-11-made-easy/"><u>Customize Your Typography: Adjusting Fonts in Windows 11 Made Easy</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-best-free-backup-applications-a-curated-list-of-32-options/"><u>Discover the Best Free Backup Applications: A Curated List of 32 Options</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-most-inspiring-movies-ranked-1-11-for-personal-empowerment/"><u>Discover the Most Inspiring Movies Ranked #1-#11 for Personal Empowerment</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/easy-steps-activatedeactivate-your-computers-touch-keyboard-on-windows-10-systems/"><u>Easy Steps: Activate/Deactivate Your Computer’s Touch Keyboard on Windows 10 Systems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/essential-strategies-to-recover-or-restore-missing-wpcpatdll-components/"><u>Essential Strategies to Recover or Restore Missing WPCPAT.DLL Components</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-the-functions-of-smartwatches-a-comprehensive-guide/"><u>Exploring the Functions of Smartwatches: A Comprehensive Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/fixing-haldll-not-found-errors-efficiently-on-windows-xp-machines/"><u>Fixing hal.dll Not Found Errors Efficiently on Windows XP Machines</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-retrieving-lost-texts-across-all-devices/"><u>Guide: Retrieving Lost Texts Across All Devices</u></a></li>
<li><a href="https://technical-tips.techidaily.com/has-nintendo-switch-online-crashed-again-tips-for-diagnosing-the-issue-correctly/"><u>Has Nintendo Switch Online Crashed Again? Tips for Diagnosing the Issue Correctly</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-nokia-c210mirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Nokia C210Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-fix-ssleay32dll-not-found-or-missing-errors/"><u>How to Fix Ssleay32.dll Not Found or Missing Errors</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-stop-terraria-from-continuously-crashing-2024-guide/"><u>How To Stop Terraria From Continuously Crashing: 2024 Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-successfully-overcome-instagram-story-upload-issues/"><u>How to Successfully Overcome Instagram Story Upload Issues</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-honor-90-lite-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Honor 90 Lite to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-samsung-galaxy-m54-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Samsung Galaxy M54 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-vivo-y27-5g-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Vivo Y27 5G</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/introducing-macos-15-sequoia-launch-date-approaching-and-a-look-at-its-revolutionary-features/"><u>Introducing MacOS 15 Sequoia: Launch Date Approaching and a Look at Its Revolutionary Features</u></a></li>
<li><a href="https://techtrends.techidaily.com/master-the-art-of-reviving-all-ipad-versions-with-these-simple-restart-techniques/"><u>Master the Art of Reviving All iPad Versions with These Simple Restart Techniques</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-iphone-night-light-feature-for-a-comfortable-reading-experience/"><u>Mastering iPhone Night Light Feature for a Comfortable Reading Experience</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/nintendo-switch-online-status-understanding-connection-issues-or-user-errors/"><u>Nintendo Switch Online Status: Understanding Connection Issues or User Errors?</u></a></li>
<li><a href="https://games-able.techidaily.com/optimal-monitors-gameplay-at-165hz/"><u>Optimal Monitors: Gameplay at 165Hz</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/overcoming-not-found-wmvcoredll-errors-step-by-step-solutions/"><u>Overcoming 'Not Found' wmvcore.dll Errors: Step-by-Step Solutions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/overcoming-the-challenge-of-the-absent-msstdfmtdll-file-expert-advice/"><u>Overcoming the Challenge of the Absent Msstdfmt.dll File: Expert Advice</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ps5-tips-how-to-broadcast-and-share-your-gaming-sessions/"><u>PS5 Tips: How to Broadcast and Share Your Gaming Sessions</u></a></li>
<li><a href="https://extra-hints.techidaily.com/quick-play-music-10-best-apps-phones/"><u>Quick Play Music  10 Best Apps, Phones</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/seamless-srt-to-text-transformation-a-modern-technique-for-2024/"><u>Seamless SRT-to-Text Transformation  A Modern Technique for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/smart-texting-strategies-keep-your-data-plan-intact/"><u>Smart Texting Strategies: Keep Your Data Plan Intact</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-linking-your-amazon-fire-tv-stick-with-wifi-through-a-smartphones-tethered-connection/"><u>Step-by-Step Guide: Linking Your Amazon Fire TV Stick with WiFi Through a Smartphone's Tethered Connection</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-tutorial-locating-personal-telephone-information-digitally/"><u>Step-by-Step Tutorial: Locating Personal Telephone Information Digitally</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-rate-of-heat-transfer-through-a-wall-is-directly-proportional-to-the-temperature-difference-across-it-and-its-thermal-conductivity/"><u>The Rate of Heat Transfer Through a Wall Is Directly Proportional to the Temperature Difference Across It and Its Thermal Conductivity.</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-guide-to-finding-out-whos-viewed-your-google-doc-documents/"><u>The Ultimate Guide to Finding Out Who's Viewed Your Google Doc Documents</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-trick-to-skip-logon-screen-enable-automatic-login-on-windows-machines/"><u>The Ultimate Trick to Skip Logon Screen: Enable Automatic Login on Windows Machines</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-honor-magic-v2-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Honor Magic V2? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/tips-and-tricks-share-your-screen-from-an-android-phone-onto-a-firestick/"><u>Tips & Tricks: Share Your Screen From an Android Phone Onto a Firestick</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-5-essential-factors-to-evaluate-when-purchasing-a-smartwatch/"><u>Top 5 Essential Factors to Evaluate When Purchasing a Smartwatch</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-crafting-the-perfect-awkward-potions-in-minecraft/"><u>Ultimate Guide: Crafting the Perfect Awkward Potions in Minecraft</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-musical-creativity-with-these-top-8-free-apple-device-tunes-tools/"><u>Unlocking Musical Creativity with These Top 8 Free Apple Device Tunes Tools</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/upcoming-tesla-robotaxi-insight-into-potential-costs-release-plans-features-and-circulating-speculations/"><u>Upcoming Tesla Robotaxi: Insight Into Potential Costs, Release Plans, Features and Circulating Speculations</u></a></li>
<li><a href="https://screen-recording.techidaily.com/windows-10-advanced-screen-recorder-software/"><u>Windows 10 Advanced Screen Recorder Software</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->