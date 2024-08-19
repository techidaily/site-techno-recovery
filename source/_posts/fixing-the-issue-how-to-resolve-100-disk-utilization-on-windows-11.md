---
title: "Fixing the Issue: How to Resolve 100%% Disk Utilization on Windows 11"
date: 2024-08-18T16:41:43.139Z
updated: 2024-08-19T16:41:43.139Z
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-a-comprehensive-walkthrough-setting-up-your-first-wirecast-livestream-to-youtube/"><u>[New] 2024 Approved  A Comprehensive Walkthrough  Setting Up Your First WireCast Livestream to Youtube</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-dimming-down-beats-a-tutorial-for-premiere-pro-editors/"><u>[New] 2024 Approved  Dimming Down Beats  A Tutorial for Premiere Pro Editors</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-facebook-profile-transformation-top-11-online-image-makers-for-2024/"><u>[New] Facebook Profile Transformation  Top 11 Online Image Makers for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-gopro-hero5-black-vs-gopro-hero4-silver-for-2024/"><u>[New] GoPro Hero5 Black vs GoPro Hero4 Silver for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-a-deep-dive-into-youtube-writers-workshop-space/"><u>[New] In 2024, A Deep Dive Into YouTube’ Writers' Workshop Space</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-trek-through-the-territory-of-talkative-thoughts/"><u>[New] Trek Through the Territory of Talkative Thoughts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-fast-favorites-todays-highest-youtube-tracks/"><u>[Updated] 2024 Approved  Fast Favorites  Today's Highest Youtube Tracks</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-the-science-of-scaling-characters-in-digital-creativity/"><u>[Updated] 2024 Approved  The Science of Scaling Characters in Digital Creativity</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-excellent-phones-apps-for-masterful-gopro-edits/"><u>[Updated] Excellent Phones' Apps for Masterful GoPro Edits</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-how-to-use-luts-in-adobe-photoshop-cc-for-2024/"><u>[Updated] How to Use LUTs in Adobe PhotoShop CC for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-breaking-down-the-barriers-to-knowing-your-fans/"><u>[Updated] In 2024, Breaking Down the Barriers to Knowing Your Fans</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-building-a-reliable-routine-for-google-meet-sessions/"><u>[Updated] In 2024, Building a Reliable Routine for Google Meet Sessions</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-integrate-sound-and-filter-magic-into-your-windows-10-photos-app/"><u>[Updated] In 2024, Integrate Sound & Filter Magic Into Your Windows 10 Photos App</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-innovating-presentations-using-adobe-captivate-for-2024/"><u>[Updated] Innovating Presentations Using Adobe Captivate for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-pivotal-elements-in-designing-effective-product-praise-videos-for-2024/"><u>[Updated] Pivotal Elements in Designing Effective Product Praise Videos for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-pixels-to-power-top-photo-editing-strategies-unlocked/"><u>[Updated] Pixels to Power  Top Photo Editing Strategies Unlocked</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expressive-echoes-mastering-snapchats-cartoon-face-effects/"><u>2024 Approved  Expressive Echoes  Mastering Snapchat's Cartoon Face Effects</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-forge-funny-frameworks/"><u>2024 Approved  Forge Funny Frameworks</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-unlocking-viral-potential-creating-captivating-instagram-puzzles/"><u>2024 Approved  Unlocking Viral Potential  Creating Captivating Instagram Puzzles</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/a-home-theater-enthusiasts-guide-to-overcoming-hdcp-complications/"><u>A Home Theater Enthusiast's Guide to Overcoming HDCP Complications</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/achieve-learning-excellence-the-leading-6-homework-support-applications-for-students-and-parents-alike/"><u>Achieve Learning Excellence: The Leading 6 Homework Support Applications for Students and Parents Alike</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/alienware-aurora-r9-powerhouse-in-depth-review-of-dells-cutting-edge-gaming-desktop/"><u>Alienware Aurora R9 Powerhouse - In-Depth Review of Dell's Cutting-Edge Gaming Desktop</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/best-free-tools-for-hard-drive-testing-ranked-top-13-july-2024-edition/"><u>Best Free Tools for Hard Drive Testing - Ranked Top 13, July 2024 Edition</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/bid-farewell-to-twitch-the-ultimate-guide-for-account-termination/"><u>Bid Farewell to Twitch: The Ultimate Guide for Account Termination</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-leading-workout-management-applications-for-a-healthier-2024/"><u>Discover the Leading Workout Management Applications for a Healthier 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effortless-recipe-to-concoct-a-clumsy-brew-in-the-world-of-minecraft/"><u>Effortless Recipe to Concoct a Clumsy Brew in the World of Minecraft</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-advice-seamlessly-integrating-google-home-into-your-pc-routine/"><u>Expert Advice: Seamlessly Integrating Google Home Into Your PC Routine</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/expert-zoom-alternatives-in-remote-work-software/"><u>Expert Zoom Alternatives in Remote Work Software</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/first-steps-in-the-world-of-x-comprehensive-instructions-for-new-users/"><u>First Steps in the World of X: Comprehensive Instructions for New Users</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-address-and-correct-stop-code-0x0000001d-on-your-pc/"><u>How to Address and Correct Stop Code 0X0000001D on Your PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-tecno-spark-10-4g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Tecno Spark 10 4G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-get-your-iphone-email-setup-working-again/"><u>How to Get Your iPhone Email Setup Working Again</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-nubia-red-magic-8s-pro-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Nubia Red Magic 8S Pro Phones with/without a PC</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-access-your-apple-iphone-8-plus-when-you-forget-the-passcode-by-drfone-ios/"><u>In 2024, How to Access Your Apple iPhone 8 Plus When You Forget the Passcode?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-streaming-tweets-on-whatsapp-a-2023-guide/"><u>In 2024, Streaming Tweets on WhatsApp  A 2023 Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/inside-look-samsung-galaxy-rings-cost-availability-timeline-hardware-specs-and-latest-updates/"><u>Inside Look: Samsung Galaxy Ring's Cost, Availability Timeline, Hardware Specs & Latest Updates</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ipados-16-released-discover-the-new-functions-and-updates-for-free/"><u>IPadOS 16 Released! Discover the New Functions and Updates for Free</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mitigating-risks-gpt-modifications-and-your-data/"><u>Mitigating Risks: GPT Modifications & Your Data</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/navigating-facebooks-video-evolution/"><u>Navigating Facebook’s Video Evolution</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-permissions-in-windows-10-how-to-get-full-access-from-trustedinstaller/"><u>Navigating Permissions in Windows 10: How to Get Full Access From TrustedInstaller</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/optimizing-your-tweets-check-out-these-unbeatable-twitter-tool-choices/"><u>Optimizing Your Tweets? Check Out These Unbeatable Twitter Tool Choices!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resetting-passwords-for-other-users-in-windows-a-comprehensive-tutorial/"><u>Resetting Passwords for Other Users in Windows - A Comprehensive Tutorial</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-osetupdll-file-absent-a-comprehensive-guide/"><u>Resolving 'oSetup.dll' File Absent: A Comprehensive Guide</u></a></li>
<li><a href="https://fox-that.techidaily.com/say-goodbye-to-fluctuating-screens-uncover-these-7-remedies-for-your-flickering-smartphone-display/"><u>Say Goodbye to Fluctuating Screens: Uncover These 7 Remedies for Your Flickering Smartphone Display</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/scholarly-savings-on-tech-the-definitive-guide-to-dell-student-deals/"><u>Scholarly Savings on Tech: The Definitive Guide to Dell Student Deals</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/securing-your-twitch-presence-how-to-enable-and-utilize-dual-authentication-for-added-protection/"><u>Securing Your Twitch Presence: How to Enable and Utilize Dual Authentication for Added Protection</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/simplifying-your-email-life-a-comprehensive-guide-to-categorization-with-gmail-labels/"><u>Simplifying Your Email Life: A Comprehensive Guide to Categorization with Gmail Labels</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-the-mystery-a-guide-on-addressing-msvcr80dll-file-missing-issues/"><u>Solving the Mystery: A Guide on Addressing msvcr80.dll File Missing Issues</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/step-by-step-snagging-stunning-pexels-pictures/"><u>Step-by-Step  Snagging Stunning Pexels Pictures</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-linking-your-laptop-and-television-with-an-hdmi-cable/"><u>Step-by-Step Guide: Linking Your Laptop and Television with an HDMI Cable</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-solutions-to-correcting-ntdlldll-errors-in-windows-systems/"><u>Step-by-Step Solutions to Correcting ntdll.dll Errors in Windows Systems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-complete-guide-to-fixing-missing-physxloaderdll-errors-on-your-pc/"><u>The Complete Guide to Fixing Missing PhysXLoader.dll Errors on Your PC</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-secret-techniques-for-seamless-background-blur-while-using-google-meet/"><u>The Secret Techniques for Seamless Background Blur While Using Google Meet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-list-of-2024s-most-effective-study-apps/"><u>The Ultimate List of 2024'S Most Effective Study Apps</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-walkthrough-how-to-turn-off-copilot-in-microsoft-edge-and-windows-11/"><u>The Ultimate Walkthrough: How to Turn Off Copilot in Microsoft Edge and Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-rated-compact-gaming-pcs-your-ultimate-buying-guide/"><u>Top-Rated Compact Gaming PCs: Your Ultimate Buying Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-bootmgr-is-not-found-expert-solutions/"><u>Troubleshooting 'BOOTMGR Is Not Found': Expert Solutions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-when-xlivedll-cant-be-located-on-your-pc-step-by-step-solutions/"><u>Troubleshooting When xlive.dll Can't Be Located on Your PC: Step-by-Step Solutions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlock-collaborative-gaming-learn-to-share-your-playstation-5-experiences-with-friends-easily/"><u>Unlock Collaborative Gaming: Learn to Share Your PlayStation 5 Experiences with Friends Easily</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlock-the-mystery-how-to-repair-your-androids-suddenly-blackened-screen/"><u>Unlock the Mystery: How to Repair Your Android's Suddenly Blackened Screen</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->