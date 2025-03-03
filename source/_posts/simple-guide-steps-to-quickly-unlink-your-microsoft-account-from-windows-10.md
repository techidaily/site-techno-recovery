---
title: "Simple Guide: Steps to Quickly Unlink Your Microsoft Account From Windows 10"
date: 2025-02-25T18:43:04.303Z
updated: 2025-03-02T23:01:14.687Z
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
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-preventing-virtual-reality-queasiness/"><u>[Updated] 2024 Approved Preventing Virtual Reality Queasiness</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-recording-your-games-in-hd-ps4-and-obs-studio-guide-for-2024/"><u>[Updated] Recording Your Games in HD PS4 & OBS Studio Guide for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-feast-your-eyes-on-9-whole-film-winter-wonders-no-charge/"><u>2024 Approved Feast Your Eyes on 9 Whole-Film Winter Wonders No Charge</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-finding-the-best-prices-on-vr-headsets-from-china/"><u>2024 Approved Finding the Best Prices on VR Headsets From China</u></a></li>
<li><a href="https://screen-recording.techidaily.com/comprehensive-iptv-accessibility-for-2024/"><u>Comprehensive IPTV Accessibility for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/connecting-disneyplus-to-chromecast-made-simple-seamless-streaming-tips-and-tricks/"><u>Connecting Disney+ to Chromecast Made Simple: Seamless Streaming Tips and Tricks</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ending-the-annoyance-how-to-stop-pesky-texts-on-iphone/"><u>Ending the Annoyance: How to Stop Pesky Texts on iPhone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/estrategia-paso-a-paso-para-instalar-y-usar-el-software-de-grabacion-de-dvd-con-winxdvd/"><u>Estrategia Paso a Paso Para Instalar Y Usar El Software De Grabación De DVD Con WinXDVD</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-update-chromecast/"><u>How to Update Chromecast</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-art-of-xbox-one-screenshots-a-comprehensive-tutorial/"><u>Mastering the Art of Xbox One Screenshots: A Comprehensive Tutorial</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-your-mobile-measuring-a-step-by-step-guide-to-using-measure-apps-on-android/"><u>Mastering Your Mobile Measuring: A Step-by-Step Guide to Using Measure Apps on Android</u></a></li>
<li><a href="https://review-topics.techidaily.com/mkv-playback-issues-on-sony-xperia-5-v-by-aiseesoft-video-converter-play-mkv-on-android/"><u>MKV playback issues on Sony Xperia 5 V</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/tactics-to-retrieve-someones-email-for-communication-purposes/"><u>Tactics to Retrieve Someone’s Email for Communication Purposes</u></a></li>
<li><a href="https://video-capture.techidaily.com/1726030065311-pc/"><u>ソフトウェア不必要でPCインスタストーリーを継承する方法</u></a></li>
</ul></div>

