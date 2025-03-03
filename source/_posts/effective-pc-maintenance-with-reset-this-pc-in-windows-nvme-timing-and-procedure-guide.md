---
title: "Effective PC Maintenance with Reset This PC in Windows Nvme: Timing and Procedure Guide"
date: 2025-03-01T00:12:44.422Z
updated: 2025-03-02T20:55:35.756Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Effective PC Maintenance with Reset This PC in Windows Nvme: Timing and Procedure Guide"
excerpt: "This Article Describes Effective PC Maintenance with Reset This PC in Windows Nvme: Timing and Procedure Guide"
thumbnail: https://thmb.techidaily.com/94f8101d81239e6d6c9b37987bd7d1eee4d5fe65d7ecceaaa89118b497471a4a.jpg
---

## Effective Winsxs Directory Management: Free Up Disk Space on Windows 11 in a Flash

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-elevate-your-editing-game-with-speed-control-skills/"><u>[New] 2024 Approved Elevate Your Editing Game with Speed Control Skills</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-elevate-your-youtube-presence-with-audio/"><u>[New] 2024 Approved Elevate Your Youtube Presence with Audio</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-quality-acoustics-at-an-accessible-price-point/"><u>[New] 2024 Approved Quality Acoustics at an Accessible Price Point</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-seamlessly-sharing-your-style-macootd-tiktoks/"><u>[New] In 2024, Seamlessly Sharing Your Style MacOOTD TikToks</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/laylist-extraction-made-simple-download-steps-revealed/"><u>[New] Playlist Extraction Made Simple Download Steps Revealed</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-effortless-mp3-downloads-from-youtube-videos/"><u>[Updated] In 2024, Free, Effortless MP3 Downloads From YouTube Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-craft-humor-for-giphy-network/"><u>2024 Approved Craft Humor for Giphy Network</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discovering-affordable-accessible-public-dns-solutions-top-picks-and-reviews/"><u>Discovering Affordable, Accessible Public DNS Solutions: Top Picks and Reviews</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/elevate-your-smart-tv-experience-with-these-exclusive-samsung-app-recommendations/"><u>Elevate Your Smart TV Experience with These Exclusive Samsung App Recommendations</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/fb-cover-videos-strategies-for-maximum-impact/"><u>FB Cover Videos Strategies for Maximum Impact</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-time-your-shots-with-an-iphones-built-in-stopwatch-feature/"><u>How to Time Your Shots with an iPhone's Built-In Stopwatch Feature</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/most-viewed-vids-worldwide-roundup-for-2024/"><u>Most Viewed Vids Worldwide Roundup for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-how-to-troubleshoot-and-repair-crackling-sound-from-your-pcs-speakers-in-windows-117/"><u>Solved! How to Troubleshoot and Repair Crackling Sound From Your PC's Speakers in Windows 11/7</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/sony-vr-tech-update-expected-debut-date-and-pricing-innovative-specs-and-rumored-insights/"><u>Sony VR Tech Update: Expected Debut Date & Pricing, Innovative Specs, and Rumored Insights</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-process-adding-new-titles-to-your-meta-oculus-quest-2-library/"><u>Step-by-Step Process: Adding New Titles to Your Meta Oculus Quest 2 Library</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-tutorial-on-integrating-a-subwoofer-into-your-samsung-home-theater-system/"><u>Step-by-Step Tutorial on Integrating a Subwoofer Into Your Samsung Home Theater System</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/steps-to-remove-on-screen-translations-from-amazon-prime-media-library/"><u>Steps to Remove On-Screen Translations From Amazon Prime Media Library</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-dragon-ball-narrative-flow-the-right-way-to-follow-the-shows-storyline/"><u>Unlocking Dragon Ball Narrative Flow: The Right Way to Follow the Show's Storyline</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/which-is-better-for-developers-ipad-app-store-or-androids-google-play-marketplace-analyzed/"><u>Which Is Better for Developers? IPad App Store or Android's Google Play Marketplace Analyzed</u></a></li>
</ul></div>

