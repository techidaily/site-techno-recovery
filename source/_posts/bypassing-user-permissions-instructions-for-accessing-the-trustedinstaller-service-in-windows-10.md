---
title: "Bypassing User Permissions: Instructions for Accessing the TrustedInstaller Service in Windows 10"
date: 2024-08-18T16:58:13.305Z
updated: 2024-08-19T16:58:13.305Z
categories:
  - BestProducts
description: "This Article Describes Bypassing User Permissions: Instructions for Accessing the TrustedInstaller Service in Windows 10"
excerpt: "This Article Describes Bypassing User Permissions: Instructions for Accessing the TrustedInstaller Service in Windows 10"
thumbnail: https://thmb.techidaily.com/1ea610ac45d115520a80068437a0213bae487d694f1953d795846826efa706f8.jpg
---

## Bypassing User Permissions: Instructions for Accessing the TrustedInstaller Service in Windows 10
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
### What to Know

* Use the**TAKEOWN** and**icacls** Command Prompt commands to take ownership of the file or folder.
* Or, right-click the item and go to**Properties** \>**Security** \>**Advanced** to add yourself to the list.
* TrustedInstaller is a built-in user account that owns lots of important system files.

 This article describes two ways to deal with the message in Windows 10 about needing permission from TrustedInstaller to make changes to a file or folder.

## How to Fix the TrustedInstaller Error Using Command Prompt

 There are two really simple[Command Prompt commands](https://www.lifewire.com/list-of-command-prompt-commands-4092302) you can use to bypass the TrustedInstaller permissions prompt. Follow these steps to fix the TrustedInstaller "error" by granting your user account permission to make changes to the file or folder:

1. [Open an elevated Command Prompt](https://www.lifewire.com/how-to-open-an-elevated-command-prompt-2618088) . The quickest way there is to search for it from the Start menu, right-click the result, and choose**Run as administrator** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
![The Run As Administrator option for the Windows 10 Command Prompt](https://www.lifewire.com/thmb/qK50_I4SdSJ98eEbO9R6yPSN1Vk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/command-prompt-admin-windows-10-45f7ecab69a442f489eaf6a499a353d4.png)
2. Enter**TAKEOWN /F** and then type the file or folder name. Here's an example:  
 `TAKEOWN /F C:\Windows\System32\fr-FR\fms.dll.mui`
3. Press**Enter** to take control of the file. You'll see a success message if the command executed correctly.  
![The TAKEOWN /F command in Windows 10 Command Prompt](https://www.lifewire.com/thmb/nOnoS4n34cd8C2EJEDT2_rLzdhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/takeown-command-trustsedinstaller-windows-10-267bfffb4f974a29940a0af233ef4a84.png)
4. Enter the following command (replacing our example file with your own) to immediately give your user account permission to delete or change the file or folder:  
 `icacls C:\Windows\System32\fr-FR\fms.dll.mui /grant Administrators:F /T`  
![icacls command executed in Windows 10 Command Prompt](https://www.lifewire.com/thmb/clN3CT0-H0V3QdOSRZWprDCigZ4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/icacls-command-windows-10-7f562cffaf424cd281b4e58c68b19e25.png)

## Edit the File's Security Options to Fix the TrustedInstaller Error

 If you don't feel comfortable using Command Prompt to take ownership of the folder or file, there is another way. Here's how to use File Explorer to edit the security settings for the data, which will let you delete or modify it as needed.

Make sure you are logged in as an administrator.

1. Locate the item you need permission to change and then right-click it and choose**Properties** .  
![The context menu for a Windows 10 folder ](https://www.lifewire.com/thmb/CSwAkry59uiW_sJ5GzqkO0QrOuk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/context-menu-folder-windows-10-0447423a01764cecad790f8dc6303c59.png)
2. Go to**Security** \>**Advanced** , then select**Change** next to**Owner: TrustedInstaller** .  
![The Properties and Advanced Security Settings options for a Windows 10 folder](https://www.lifewire.com/thmb/823H3LgLGW5GbhyNSwSn1HNUZlk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/advanced-security-settings-windows-10-folder-4eb4fed4cb134eb1ba00993a705f7175.png)
3. Type your username into the text box and then choose**Check Names** \>**OK** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows 10 Check Names box with a user account listed](https://www.lifewire.com/thmb/ESMv2bIcNtWxpryKYLlwZFwmyCA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-10-select-user-or-group-880cbe35a52348f19d11206db4d7a0b6.png)
4. Check the box next to**Replace owner on subcontainers and objects** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
![The replace owner on subcontainers and objects checkbox in Windows 10](https://www.lifewire.com/thmb/n8OW45wPPq3HiSTrW4eQIT_Y0EU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-owner-windows-10-folder-885ef894881e4e21a60b1b09568ea020.png)
5. Select**OK** at the bottom and then**OK** on the Properties window you opened in Step 1.
6. Open**Properties** \>**Security** \>**Advanced** once more. This time, select**Add** .  
![The Advanced Security Settings for a Windows 10 folder](https://www.lifewire.com/thmb/fEVYPGbUtSiGdO8kZg1RZd6gtIE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/add-button-advanced-security-settings-3ffcde5bc8b942278219bbd9b4663921.png)
7. Choose**Select a principal** and then type your username in the box.
8. Press**Check Names** \>**OK** .  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
![A user account listed in the Select User or Group box for a Windows 10 folder](https://www.lifewire.com/thmb/a8Ie_eyPviEwOjytgb9HHofaQgc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/select-user-group-windows-10-security-b2ffe7d116f2424e845a612090d4e932.png)
9. Check the box next to**Full control** , then select**OK** .  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Full Control permission selected for a folder in Windows 10](https://www.lifewire.com/thmb/cLa_4Jv8moyuFMZaNvHFNWAcllw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/full-control-folder-permissions-b0f31e6f8d7d418e91990e6c32476c30.png)
10. Check the box next to **Replace all child object permission entries with inheritable permission entries from this object** .  
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The checkbox called Replace all child object permission entries in Windows 10](https://www.lifewire.com/thmb/6T2vTKuuRj3ONEWEpCefVrYtszQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-all-child-object-permission-entries-windows-10-fc09040d1d8b4357b5866ced25b79262.png)
11. Select**OK** on the Advanced Security Settings window and then**Yes** on the confirmation prompts. You should now have full permission to make changes to the file or folder, and you can close any other windows you opened to make these changes.

## Why Do I Need Permission From TrustedInstaller?

 Provided you're the primary user of your home computer, you might be surprised to find out you need anyone’s permission to deal with files on your own PC.

 All Windows 10 PCs have an in-built Microsoft account known as the TrustedInstaller. This account exists to prevent accidental damage to important system files, so it's given ownership over many important operating system files. For you to be able to take control of these files, you need to make yourself the owner as described above.  

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[Subscribe](https://www.lifewire.com/#)

Tell us why!

 Other  Not enough details  Hard to understand

 Submit

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
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-masterclass-converting-twitter-vids-to-eye-catching-engaging-gifs/"><u>[New] In 2024, Masterclass  Converting Twitter Vids to Eye-Catching, Engaging GIFs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-mastering-digital-screen-capture-techniques-for-2024/"><u>[New] Mastering Digital Screen Capture Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-rethinking-recipes-squared-up-tutorials-for-youtube-and-facebook-success-for-2024/"><u>[Updated] Rethinking Recipes  Squared-Up Tutorials for YouTube and Facebook Success for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-sync-your-world-step-by-step-windows-pc-tutorial-for-live-tv-recording-for-2024/"><u>[Updated] Sync Your World  Step-by-Step Windows PC Tutorial for Live TV Recording for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-what-is-instagram-story-highlight-in-2024/"><u>[Updated] What Is Instagram Story Highlight, In 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-srt-to-sub-how-to-convert-srt-to-sub-with-3-actionable-ways/"><u>2024 Approved  SRT to SUB  How to Convert SRT to SUB with 3 Actionable Ways</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/a-guide-on-booking-an-expert-consultation-with-apples-geniuses/"><u>A Guide on Booking an Expert Consultation with Apple’s Geniuses</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comparing-roku-devices-express-and-stick-showdown-explained/"><u>Comparing Roku Devices: Express and Stick Showdown Explained</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-walkthrough-for-implementing-windows-telnet-client/"><u>Comprehensive Walkthrough for Implementing Windows Telnet Client</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/diagnosing-and-repairing-problems-when-tiktok-wont-load/"><u>Diagnosing and Repairing Problems When TikTok Won't Load</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-top-8-must-have-educational-apps-for-mastery/"><u>Discover Top 8 Must-Have Educational Apps for Mastery</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/diy-masterclass-building-and-programming-a-versatile-universal-remote/"><u>DIY Masterclass: Building & Programming a Versatile Universal Remote</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/efficiently-post-several-pictures-at-once-a-guide-to-bulk-images-on-facebook/"><u>Efficiently Post Several Pictures at Once: A Guide to Bulk Images on Facebook</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/facebook-live-cutting-edge-strategies-audiences/"><u>Facebook Live  Cutting-Edge Strategies Audiences</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/hitachi-ultra-hd-smart-tvs-enjoy-seamless-streaming-with-directly-embedded-roku-platforms/"><u>Hitachi Ultra HD Smart TVs: Enjoy Seamless Streaming with Directly Embedded Roku Platforms</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-exit-recovery-mode-on-iphone-11-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit Recovery Mode on iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-oppo-a2-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Oppo A2 To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-the-art-of-sounding-different-in-pubg/"><u>In 2024, Mastering the Art of Sounding Different in PUBG</u></a></li>
<li><a href="https://driver-install.techidaily.com/instantly-improve-win-7s-performance-new-gaming-mouse-driver/"><u>Instantly Improve Win 7'S Performance - New Gaming Mouse Driver</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/m3-macbook-pro-info-hub-unveiling-date-price-range-and-full-tech-specs-breakdown/"><u>M3 MacBook Pro Info Hub: Unveiling Date, Price Range & Full Tech Specs Breakdown</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-network-troubleshooting-a-guide-to-using-tracert-on-windows/"><u>Mastering Network Troubleshooting: A Guide to Using Tracert on Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-fix-effective-strategies-for-haldll-troubleshooting-across-windows-os/"><u>Mastering the Fix: Effective Strategies for Hal.dll Troubleshooting Across Windows OS</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/reversing-a-repot-a-step-by-step-guide-for-tiktok-users/"><u>Reversing a Repot: A Step-by-Step Guide for TikTok Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/seize-your-social-media-videos-top-extensions-and-downloaders-for-firefox/"><u>Seize Your Social Media Videos! Top Extensions and Downloaders for Firefox</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-selection-best-workout-journaling-apps-of-2024/"><u>The Ultimate Selection: Best Workout Journaling Apps of 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/things-you-must-know-for-screen-mirroring-apple-iphone-8-plus-drfone-by-drfone-ios/"><u>Things You Must Know for Screen Mirroring Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-chromecast-connection-issues-for-perfect-media-streaming/"><u>Troubleshooting Chromecast Connection Issues for Perfect Media Streaming</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-guide-what-to-do-when-your-tiktok-app-keeps-crashing/"><u>Troubleshooting Guide: What to Do When Your TikTok App Keeps Crashing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-the-haldll-file-not-found-error-for-windows-xp-users/"><u>Troubleshooting the 'hal.dll' File Not Found Error for Windows XP Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-create-trending-content-and-get-exploded-views-on-tiktok/"><u>Ultimate Guide: Create Trending Content & Get Exploded Views on TikTok!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-your-vehicles-secrets-a-step-by-step-guide-to-finding-the-car-radio-password/"><u>Unlocking Your Vehicle's Secrets: A Step-by-Step Guide to Finding the Car Radio Password</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/watching-hulu-on-lg-smart-tvs-a-step-by-step-tutorial/"><u>Watching Hulu on LG Smart TVs – A Step-by-Step Tutorial</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/what-to-know-about-apples-upcoming-m4-mac-mini-news-on-launch-schedule-pricing-forecasts-and-internal-features/"><u>What to Know About Apple's Upcoming M4 Mac Mini - News on Launch Schedule, Pricing Forecasts, and Internal Features</u></a></li>
</ul></div>
