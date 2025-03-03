---
title: "Solving the Windows Update Error: Code 0X80070005 - Access Denied"
date: 2025-02-25T20:11:51.733Z
updated: 2025-03-02T23:57:50.909Z
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
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-transform-your-videography-effortless-recording-and-editing-via-adobe-connect/"><u>[Updated] 2024 Approved Transform Your Videography Effortless Recording and Editing via Adobe Connect</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-best-buy-on-cloud-storage-pricing-a-comparative-study/"><u>[Updated] Best Buy on Cloud Storage Pricing A Comparative Study</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/coming-soon-explore-the-projected-details-of-oneplus-10-news-costs-and-leaked-features/"><u>Coming Soon? Explore the Projected Details of OnePlus 10 - News, Costs & Leaked Features</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/easy-methods-to-determine-the-temperature-of-your-macbook-computer/"><u>Easy Methods to Determine the Temperature of Your MacBook Computer</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/fix-missing-d3dx928dll-error-on-your-pc-effective-solutions/"><u>Fix Missing d3dx9_28.dll Error on Your PC - Effective Solutions</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-can-we-unlock-our-vivo-x100-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Vivo X100 Phone Screen?</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tactics-for-integrating-multimedia-into-lessons/"><u>In 2024, Tactics for Integrating Multimedia Into Lessons</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-ultimate-guide-on-iphone-15-plus-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Ultimate Guide on iPhone 15 Plus iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/online-m4v-and-m4a/"><u>Online M4V & M4A 비디오 무료 전환 방법 - 모바이비</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/revive-your-music-streaming-top-13-fixes-when-spotify-fails-on-android-auto/"><u>Revive Your Music Streaming: Top 13 Fixes When Spotify Fails on Android Auto</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-507-unique-instagram-caption-ideas/"><u>Top 507 Unique Instagram Caption Ideas</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-from-sideways-to-straight-quick-video-flipping-solutions/"><u>Updated 2024 Approved From Sideways to Straight Quick Video Flipping Solutions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/who-owns-chatgpt/"><u>Who Owns ChatGPT?</u></a></li>
</ul></div>

