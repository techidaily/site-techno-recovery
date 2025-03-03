---
title: "Fixing the Issue: How to Resolve 100%% Disk Utilization on Windows 11"
date: 2025-02-28T23:43:16.663Z
updated: 2025-03-02T16:04:51.982Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Fixing the Issue: How to Resolve 100%% Disk Utilization on Windows 11"
excerpt: "This Article Describes Fixing the Issue: How to Resolve 100%% Disk Utilization on Windows 11"
thumbnail: https://thmb.techidaily.com/c8505bae3e314a2b381005e22ef6317da32419f0b4525c4f54b2150317447813.jpg
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
<li><a href="https://remote-screen-capture.techidaily.com/updated-professional-streaming-best-devices-to-record-live-sessions/"><u>[Updated] Professional Streaming Best Devices to Record Live Sessions</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-navigate-to-exciting-windows-11-gaming-world/"><u>2024 Approved Navigate to Exciting Windows 11 Gaming World</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-professional-filmmakers-plug-in-picks-for-final-cut/"><u>2024 Approved Professional Filmmaker's Plug-In Picks for Final Cut</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-taking-the-first-steps-towards-vr-technology-mobile-based-headsets-vs-cabled-gear/"><u>2024 Approved Taking the First Steps Towards VR Technology Mobile-Based Headsets Vs. Cabled Gear</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Honor X9a | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-ultimate-list-of-free-driver-refresher-programs-for-july-2e/"><u>Discover the Ultimate List of Free Driver Refresher Programs for July 2E</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/free-typing-lessons-for-everyone-explore-our-12-top-choices-across-age-groups/"><u>Free Typing Lessons For Everyone: Explore Our 12 Top Choices Across Age Groups</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-fix-shell32dll-is-missing-or-not-found-errors/"><u>How to Fix Shell32.dll Is Missing or Not Found Errors</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-system-issues-of-apple-iphone-12-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System Issues of Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-safely-update-your-facebook-login-credentials-step-by-step/"><u>How To: Safely Update Your Facebook Login Credentials Step-by-Step</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-elite-top-10-4k-monitors-list/"><u>In 2024, Elite Top 10 4K Monitors List</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-cover-letters-a-step-by-step-guide-with-chatgpt/"><u>Mastering Cover Letters: A Step-by-Step Guide with ChatGPT</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-eliminating-your-recommended-posts-on-insta/"><u>Step-by-Step Guide: Eliminating Your 'Recommended Posts' On Insta</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/stepping-into-the-era-of-ultra-fast-internet-with-verizon-n-5g/"><u>Stepping Into the Era of Ultra-Fast Internet with Verizon N 5G</u></a></li>
<li><a href="https://fox-useful.techidaily.com/unveiling-the-capabilities-and-uses-of-yls-complimentary-web-based-ai-journal-creation-tool/"><u>Unveiling the Capabilities & Uses of YL's Complimentary Web-Based AI Journal Creation Tool</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/your-ultimate-guide-to-successfully-installing-microsoft-365-for-windows-users/"><u>Your Ultimate Guide to Successfully Installing Microsoft 365 for Windows Users</u></a></li>
</ul></div>

