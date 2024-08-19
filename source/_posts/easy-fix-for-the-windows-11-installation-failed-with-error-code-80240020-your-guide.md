---
title: Easy Fix for the Windows 11 Installation Failed with Error Code 80240020 - Your Guide
date: 2024-08-18T16:39:16.228Z
updated: 2024-08-19T16:39:16.228Z
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-mastering-instagrams-music-stickers-integration/"><u>[New] 2024 Approved  Mastering Instagram's Music Stickers Integration</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-how-to-successfully-record-and-manage-internet-radio/"><u>[New] In 2024, How to Successfully Record and Manage Internet Radio</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-timing-and-frequency-what-is-the-best-day-to-release-a-podcast/"><u>[New] Timing & Frequency  What Is the Best Day to Release a Podcast?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-five-trailblazers-shaping-the-webs-audiovideo-landscape/"><u>[Updated] Five Trailblazers Shaping the Web's Audio/Video Landscape</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-headset-havens-weighing-google-cardboard-against-samsung-gear/"><u>[Updated] Headset Havens  Weighing Google Cardboard Against Samsung Gear</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-photo-framing-made-easy-leading-apps-and-sites-reviewed/"><u>[Updated] Photo Framing Made Easy  Leading Apps and Sites Reviewed</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-visual-mastery-redefined-the-z32x-dreamcolor-edition-for-2024/"><u>[Updated] Visual Mastery Redefined  The Z32X DreamColor Edition for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-inside-look-how-youtube-funds-are-transforming-content-creation/"><u>2024 Approved  Inside Look  How YouTube Funds Are Transforming Content Creation</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ving-a-million-on-the-map-a-strategic-view-to-sub-guide/"><u>Achieving a Million on the Map  A Strategic View-to-Sub Guide</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/advanced-photo-enhancement-applications-for-flawless-image-restoration/"><u>Advanced Photo Enhancement Applications for Flawless Image Restoration</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/can-you-submerge-your-iphone-13-without-damage-water-resistance-explained/"><u>Can You Submerge Your iPhone 13 Without Damage – Water Resistance Explained</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/create-your-own-musical-party-at-home-a-comprehensive-guide-to-hosting-karaoke-night/"><u>Create Your Own Musical Party at Home: A Comprehensive Guide to Hosting Karaoke Night</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/decode-the-meaning-of-a-503-error-and-learn-quick-fix-steps/"><u>Decode the Meaning of a 503 Error & Learn Quick Fix Steps</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-12-no-cost-mobile-apps-for-endless-movie-entertainment/"><u>Discover 12 No-Cost Mobile Apps for Endless Movie Entertainment</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/diy-guide-building-your-own-projector-screen-at-home/"><u>DIY Guide: Building Your Own Projector Screen at Home</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/dual-display-tutorial-activating-split-screen-mode-on-macbook-air/"><u>Dual Display Tutorial: Activating Split Screen Mode on MacBook Air</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/essential-80s-movie-marathon-list-gems-from-a-retro-era/"><u>Essential '80S Movie Marathon List: Gems From a Retro Era</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/experiencing-connectivity-problems-with-roblox-heres-how-to-check-if-its-a-global-outage-or-local-issue/"><u>Experiencing Connectivity Problems with Roblox? Here's How to Check if It’s a Global Outage or Local Issue</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-variations-comparing-ipads-with-conventional-tablets/"><u>Exploring Variations: Comparing iPads with Conventional Tablets</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/get-ready-for-a-revolution-in-wearable-tech-expert-predictions-on-the-google-pixel-watch-release-and-specs/"><u>Get Ready for a Revolution in Wearable Tech: Expert Predictions on the Google Pixel Watch Release and Specs</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-livestream-lifters-for-modern-audiences/"><u>In 2024, Livestream Lifters for Modern Audiences</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-essential-guide-to-youtube-thumbnail-crafting-mac/"><u>In 2024, The Essential Guide to YouTube Thumbnail Crafting (Mac)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Xiaomi Redmi A2+ | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/instant-impressions-fast-forwarding-ppt-slide-showtimes-for-2024/"><u>Instant Impressions  Fast-Forwarding PPT Slide Showtimes for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-art-of-seamless-instagram-story-sharing-troubleshooting-tips/"><u>Mastering the Art of Seamless Instagram Story Sharing - Troubleshooting Tips!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/maximize-performance-installing-the-newest-amd-radeon-v2410-video-card-drivers/"><u>Maximize Performance: Installing the Newest AMD Radeon V24.10 Video Card Drivers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/most-innovative-voice-altering-mobile-apps-for-2024/"><u>Most Innovative Voice-Altering Mobile Apps for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-top-16-best-free-avi-video-rotators-windows-mac-android-iphone-and-online/"><u>New 2024 Approved Top 16 Best Free AVI Video Rotators Windows, MAC, Android, iPhone, and Online</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-zlibdll-error-a-step-by-step-guide/"><u>Resolving zlib.dll Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/restoring-erased-phone-details-on-android-devices-techniques-and-tips/"><u>Restoring Erased Phone Details on Android Devices - Techniques and Tips</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/samsung-galaxy-z-fold-edition-6-dive-into-the-specifications-market-price-and-upcoming-launch/"><u>Samsung Galaxy Z Fold Edition 6: Dive Into the Specifications, Market Price & Upcoming Launch</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solutions-for-resolving-propsysdll-file-absent-errors/"><u>Solutions for Resolving 'propsys.dll' File Absent Errors</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-the-mystery-of-your-darkened-android-device-a-step-by-step-guide/"><u>Solving the Mystery of Your Darkened Android Device: A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/soundscapes-in-hd-techniques-for-precision-recording-for-2024/"><u>Soundscapes in HD  Techniques for Precision Recording for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/streaming-essentials-the-ultimate-movie-list-by-lifewire/"><u>Streaming Essentials: The Ultimate Movie List by Lifewire</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-etiquette-of-twitter-shares-retweet-vs-re-tweet-explained/"><u>The Etiquette of Twitter Shares: Retweet Vs. Re-Tweet Explained</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-future-is-here-rumors-and-projections-for-the-google-pixel-watch-3s-market-entry/"><u>The Future Is Here: Rumors & Projections for the Google Pixel Watch 3'S Market Entry</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-tutorial-for-placing-multiple-geo-tags-on-google-maps-easily/"><u>The Ultimate Tutorial for Placing Multiple Geo-Tags on Google Maps Easily</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-10-beginner-friendly-tweaks-and-tricks-on-formerly-twitter-now-x-platform/"><u>Top 10 Beginner-Friendly Tweaks and Tricks on Formerly Twitter Now 'X' Platform</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-tips-and-essentials-choosing-the-right-projector/"><u>Top Tips and Essentials: Choosing the Right Projector</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-expert-tips-on-deep-cleaning-home-audio-speakers/"><u>Ultimate Guide: Expert Tips on Deep-Cleaning Home Audio Speakers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-linking-your-nintendo-switch-console-to-the-television/"><u>Ultimate Guide: Linking Your Nintendo Switch Console to the Television</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-solutions-to-the-missing-d3dx9asteriskdll-dilemma/"><u>Ultimate Solutions to the Missing d3dx9_asterisk.dll Dilemma</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-tomorrows-tech-at-googles-upcoming-showcase-insider-information-and-rumors/"><u>Unveiling Tomorrow's Tech at Google's Upcoming Showcase - Insider Information & Rumors</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->