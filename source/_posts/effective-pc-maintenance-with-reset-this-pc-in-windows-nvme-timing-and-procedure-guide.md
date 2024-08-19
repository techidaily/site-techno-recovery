---
title: "Effective PC Maintenance with Reset This PC in Windows Nvme: Timing and Procedure Guide"
date: 2024-08-18T16:41:38.803Z
updated: 2024-08-19T16:41:38.803Z
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
<li><a href="https://techno-recovery.techidaily.com/royal-match-exploring-its-multi-level-gameplay-dynamics/"><u>'Royal Match': Exploring Its Multi-Level Gameplay Dynamics</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-core-asmr-platforms-explored/"><u>[New] 2024 Approved  Core ASMR Platforms Explored</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-how-to-solve-delayed-or-failed-video-sending-in-facebooks-mobile-messaging-service/"><u>[New] How to Solve Delayed or Failed Video Sending in Facebook's Mobile Messaging Service</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-best-way-to-use-obs-live-stream-to-facebook/"><u>[New] In 2024, Best Way to Use OBS Live Stream to Facebook</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-gamer-friendly-video-capture-apps/"><u>[New] In 2024, Gamer-Friendly Video Capture Apps</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-definitive-manual-on-hand-based-tracking/"><u>[New] The Definitive Manual on Hand-Based Tracking</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-be-inspired-today-the-essentials-of-stunning-photos-on-ig/"><u>[Updated] 2024 Approved  Be Inspired Today! The Essentials of Stunning Photos on IG</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-design-best-practices-for-engaging-youtube-thumbnails/"><u>[Updated] 2024 Approved  Design Best Practices for Engaging YouTube Thumbnails</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-leveraging-social-influence-a-guide-to-biz-success-on-snap/"><u>[Updated] 2024 Approved  Leveraging Social Influence  A Guide to Biz Success on Snap</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-free-video-conferencing-solutions-for-windowsmac-users/"><u>2024 Approved  Free Video Conferencing Solutions for Windows/Mac Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premiere-visionary-film-glimpses/"><u>2024 Approved  Premiere Visionary Film Glimpses</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-professional-stability-essentials-for-youtube-videographers/"><u>2024 Approved  Professional Stability Essentials for YouTube Videographers</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-most-compelling-list-of-free-youtube-platforms-for-comic-book-illustrators/"><u>2024 Approved  The Most Compelling List of Free YouTube Platforms for Comic Book Illustrators</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722902038600-anticipating-the-future-of-tech-at-googles-forthcoming-showcase-stay-updated/"><u>Anticipating the Future of Tech at Google's Forthcoming Showcase - Stay Updated</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/best-no-cost-typing-courses-12-picks-for-users-of-any-age/"><u>Best No-Cost Typing Courses: 12 Picks for Users of Any Age</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/can-you-submerge-an-iphone-15-pro-max-in-water-is-it-water-resistant/"><u>Can You Submerge an iPhone 15 Pro Max in Water - Is It Water-Resistant?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-evaluation-of-snappy-driver-installer-version-113/"><u>Comprehensive Evaluation of Snappy Driver Installer Version 1.13</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-greatest-inspirational-films-of-all-time/"><u>Discover The Greatest Inspirational Films Of All Time</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-ultimate-collection-of-free-virtual-fax-services/"><u>Discover the Ultimate Collection of Free Virtual Fax Services</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-guide-navigating-through-the-502-bad-gateway-mishap/"><u>Expert Guide: Navigating Through the 502 Bad Gateway Mishap</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-low-speed-downloads-solutions-for-improving-your-utorrent-performance/"><u>Fixing Low-Speed Downloads: Solutions for Improving Your uTorrent Performance</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/from-smartphone-to-pc-how-to-enjoy-the-full-snapchat-features-on-desktop/"><u>From Smartphone to PC: How to Enjoy the Full Snapchat Features on Desktop</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-correctly-handle-mfc71dll-is-absent-or-not-detected-errors/"><u>How to Correctly Handle 'Mfc71.dll Is Absent or Not Detected' Errors</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-correctly-handle-msvcr70dll-missing-or-undetected-problems/"><u>How to Correctly Handle MSVCR70.dll Missing or Undetected Problems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-g22-by-fonelab-android-recover-music/"><u>How to retrieve erased music from G22</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-successfully-refresh-or-power-cycle-your-ipad-of-any-make-and-model/"><u>How to Successfully Refresh or Power Cycle Your iPad of Any Make and Model</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-tackle-netflixs-nw-1-19-error-and-get-back-to-watching-seamlessly/"><u>How to Tackle Netflix's NW- 1-19 Error and Get Back to Watching Seamlessly</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-4k-video-conversion-mastery-how-to-download-in-mp4-format/"><u>In 2024, 4K Video Conversion Mastery How to Download in MP4 Format</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-ai-driven-branding-the-top-10-podcast-name-makers/"><u>In 2024, AI-Driven Branding  The Top 10 Podcast Name Makers</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-apple-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On Apple iPhone 11 Pro Max</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-apple-iphone-7-plus-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On Apple iPhone 7 Plus</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-how-to-reverse-video-on-instagram-complete-guide/"><u>In 2024, How to Reverse Video on Instagram? [Complete Guide]</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-samsung-galaxy-a05-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Samsung Galaxy A05 to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-iphone-xs-max-drfone-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-unlocking-facebooks-secrets-an-introductory-guide/"><u>In 2024, Unlocking Facebook's Secrets  An Introductory Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/insta-influencing-techniques-for-scaling-your-following-quickly/"><u>Insta Influencing  Techniques for Scaling Your Following Quickly</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-the-nintendo-switch-online-network-unavailable-right-now-or-are-there-local-wi-fi-issues/"><u>Is the Nintendo Switch Online Network Unavailable Right Now, Or Are There Local Wi-Fi Issues?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/leading-contenders-the-premier-gaming-machines-of-2024/"><u>Leading Contenders: The Premier Gaming Machines of 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/methods-for-subtle-audio-softening-with-lumafusion/"><u>Methods for Subtle Audio Softening with Lumafusion</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/must-ask-9-queries-prior-to-investing-in-an-ev/"><u>Must-Ask 9 Queries Prior to Investing in an EV</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-the-web-how-to-access-and-enjoy-the-samsung-unpacked-presentation-from-home/"><u>Navigating the Web: How to Access and Enjoy the Samsung Unpacked Presentation From Home</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/newest-july-2024-microsoft-windows-update-service-pack-and-patches-overview/"><u>Newest July 2024 Microsoft Windows Update: Service Pack & Patches Overview</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-lag-in-your-chromecast-audio-streaming-a-step-by-step-guide/"><u>Resolving Lag in Your Chromecast Audio Streaming: A Step-by-Step Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-the-missing-comctl32dll-file-a-step-by-step-guide/"><u>Resolving the Missing Comctl32.dll File: A Step-by-Step Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-xinput13dll-errors-on-your-pc-a-comprehensive-guide/"><u>Resolving xinput1_3.dll Errors on Your PC - A Comprehensive Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/scoring-steep-tech-deals-finding-and-claiming-your-dell-student-discount/"><u>Scoring Steep Tech Deals: Finding and Claiming Your Dell Student Discount!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solutions-for-resolving-the-missing-mingwm10dll-file-warning/"><u>Solutions for Resolving the 'Missing Mingwm10.dll File' Warning</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-removing-your-personal-unlock-code-on-windows-11/"><u>Step-by-Step Guide: Removing Your Personal Unlock Code on Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-process-setup-and-sync-disneyplus-for-chromecast-viewing-comfortably-at-home/"><u>Step-by-Step Process: Setup and Sync Disney+ for Chromecast Viewing Comfortably at Home</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-tutorial-for-watching-hulu-on-an-lg-smart-tv-setup/"><u>Step-by-Step Tutorial for Watching Hulu on an LG Smart TV Setup</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-correct-sequence-to-experience-the-the-conjuring-series-a-step-by-step-guide/"><u>The Correct Sequence to Experience the 'The Conjuring' Series: A Step-by-Step Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-non-professionals-handbook-to-accessing-an-iphone-sim-tray-at-home/"><u>The Non-Professional's Handbook to Accessing an iPhone SIM Tray at Home</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/tips-for-resolving-hardware-failures-detected-during-power-on-self-test-post/"><u>Tips for Resolving Hardware Failures Detected During Power-On Self Test (POST)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-steps-reactivating-your-roku-devices-closed-captions/"><u>Troubleshooting Steps: Reactivating Your Roku Device’s Closed Captions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-steps-resolving-non-working-apps-on-your-samsung-television/"><u>Troubleshooting Steps: Resolving Non-Working Apps on Your Samsung Television</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-tips-resolving-code-800-on-clientserver-vpns/"><u>Troubleshooting Tips: Resolving Code 800 on Client/Server VPNs</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-to-gaming-ready-mini-computers/"><u>Ultimate Guide to Gaming-Ready Mini Computers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ultimate-tutorial-using-sony-dualshock-3-on-your-desktop-no-third-party-tools-required/"><u>Ultimate Tutorial: Using Sony DualShock 3 on Your Desktop (No Third-Party Tools Required)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722873027185-whats-new-in-july-2024-fresh-windows-update-roster-unveiled/"><u>What's New in July 2024: Fresh Windows Update Roster Unveiled</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->