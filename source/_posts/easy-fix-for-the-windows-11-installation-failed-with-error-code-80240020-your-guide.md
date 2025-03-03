---
title: Easy Fix for the Windows 11 Installation Failed with Error Code 80240020 - Your Guide
date: 2025-02-27T22:16:58.096Z
updated: 2025-03-02T23:42:27.553Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Easy Fix for the Windows 11 Installation Failed with Error Code 80240020 - Your Guide
excerpt: This Article Describes Easy Fix for the Windows 11 Installation Failed with Error Code 80240020 - Your Guide
thumbnail: https://thmb.techidaily.com/721844d81a2674aaafe28cc93fa85dbee744a7d0e151c9e44399471e099cac39.jpg
---

## Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved

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
<li><a href="https://article-files.techidaily.com/new-navigating-macos-to-optimize-mixer-streams-for-2024/"><u>[New] Navigating MacOS to Optimize Mixer Streams for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-easily-share-your-camera-roll-in-a-snap-tips-and-tricks/"><u>[Updated] In 2024, Easily Share Your Camera Roll in a Snap - Tips & Tricks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-unveiling-the-secrets-of-dark-sky-photography-for-2024/"><u>[Updated] Unveiling the Secrets of Dark Sky Photography for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/decode-and-repair-netflix-glitch-code-nw-30-19-for-hassle-free-watching/"><u>Decode and Repair Netflix Glitch Code NW-30-19 for Hassle-Free Watching</u></a></li>
<li><a href="https://tech-haven.techidaily.com/decoding-generative-mastery-notion-against-gpt-3-showdown/"><u>Decoding Generative Mastery: Notion Against GPT-3 Showdown</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/decoding-the-details-of-lg-communication-pathways/"><u>Decoding the Details of LG Communication Pathways</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/vering-the-ultimate-10-vr-video-experience-on-youtube/"><u>Discovering the Ultimate 10-VR Video Experience on YouTube</u></a></li>
<li><a href="https://win-data.techidaily.com/effective-methods-for-identifying-and-fixing-motherboard-problems-yl-computing-solutions/"><u>Effective Methods for Identifying & Fixing Motherboard Problems - YL Computing Solutions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/enjoy-sports-with-ease-setting-up-espn-plus-on-an-lg-smart-tv/"><u>Enjoy Sports with Ease: Setting Up ESPN Plus on an LG Smart TV</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-enhance-productivity-through-using-slack-at-work/"><u>How To Enhance Productivity Through Using Slack at Work</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-switch-off-accessibility-settings-sticky-keys-tutorial-for-windows-users/"><u>How to Switch Off Accessibility Settings: Sticky Keys Tutorial for Windows Users</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-honor-magic-5-pro-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-from-novice-to-pro-the-funimate-guide/"><u>In 2024, From Novice to Pro - The Funimate Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-meizu-21-pro-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Meizu 21 Pro to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/iphone-15-pro-max-vs-samsung-s24-ultra-whats-the-difference/"><u>IPhone 15 Pro Max Vs. Samsung S24 Ultra: What's the Difference?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/list-of-ipad-versions-with-integrated-gps-capabilities/"><u>List of iPad Versions with Integrated GPS Capabilities</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-solutions-to-stabilize-and-restore-your-surface-pros-display-quality/"><u>Step-by-Step Solutions to Stabilize and Restore Your Surface Pro's Display Quality</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-connecting-your-roku-tv-step-by-step-instructions/"><u>Ultimate Guide: Connecting Your Roku TV - Step-by-Step Instructions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-creating-your-personalized-email-signature-on-godaddys-web-mail-platform/"><u>Ultimate Guide: Creating Your Personalized Email Signature on GoDaddy's Web Mail Platform</u></a></li>
</ul></div>

