---
title: "Easy Guide: Identifying Your Motherboard's Model in Windows"
date: 2024-08-30T13:08:44.919Z
updated: 2024-08-31T13:08:44.919Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/94e07137a13ad182683de85211bfdf3891ed8a3953138abcae7ed2effebf679e.jpg
---

## Easy Guide: Identifying Your Motherboard's Model in Windows

### Quick Links

* [Why Do I Want To Find My Motherboard Model?](https://fox-http.techidaily.com/updated-in-2024-joyful-journeys-the-ultimate-list-of-familial-classics/)
* [Find Your Motherboard Model Number with CIM in PowerShell](https://fox-boxes.techidaily.com/2024-approved-editorsuite-ultimate-guide-in-depth-analysis-of-androvid/)
* [Check Your Model Number from the Command Prompt (or PowerShell) with WMIC](https://www.howtogeek.com/208420/how-to-check-your-motherboard-model-number-on-your-windows-pc/#check-your-model-number-from-the-command-prompt-or-powershell-with-wmic)
* [Check Your Model Number in System Information](https://facebook-video-footage.techidaily.com/updated-master-quick-youtube-video-rendering-and-efficient-uploading/)
* [Check Your Model Number with Speccy](https://win11-tips.techidaily.com/how-to-thrive-in-free-championship-football-simulator/)
* [Check Your Motherboard Model with HWiNFO64](https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/)

### Key Takeaways

 To get your motherboard model, run "wmic baseboard get product,Manufacturer,version,serialnumber" in Command Prompt or PowerShell. You can also search "System Information" in the Start Menu, then look for "BaseBoard Product" in your system details.

 Whether you need to update drivers, check hardware compatibility, or you're just curious, it's way easier to check your motherboard model number with these simple tricks than to crack open your case to check the board itself. Here's how to check your motherboard model number from the comfort of your keyboard.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
##  Why Do I Want To Find My Motherboard Model?

 Knowing your motherboard's model number is important if you're thinking of upgrading your drivers, buying new hardware (you'll need the proper expansion or memory slots, for example), or just checking the capabilities of your board if you're considering upgrading your whole rig.

 If you kept the paperwork that came with your computer (or the individual components, if you built it yourself), you can often times reference that. Even then, it's best to check to make sure the documentation is correct. Rather than open the case and search for the model number on the board itself, use tools within Windows to check things out instead.

##  Find Your Motherboard Model Number with CIM in PowerShell

 Common Information Model (CIM) cmdlets are commands you can run to get information about your PC's hardware or software from a command-line interface. If you've used WMIC in the past you'll feel right at home with CIM, and if you haven't, don't worry—it is easy to use. 

 First, open up a PowerShell or Command Prompt window. It doesn't need to be run as administrator, though that won't hurt either. 

![Search for "PowerShell" in the Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-open-powershell.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
 The run the following command to get information about your motherboard: 

Get-CimInstance -ClassName Win32_baseboard

![The information about your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2-baseboard-deets.png) 

 Depending on what information is available, you may or may not get an actual model number. However, you'll almost always get something in the "Product" field that will be enough to figure out what motherboard is in your PC. 

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Check Your Model Number from the Command Prompt (or PowerShell) with WMIC

 WMIC is technically deprecated but still works.

 If you're comfortable using the Command Prompt (or PowerShell, where these commands also work), you can easily check a variety of motherboard and hardware stats using the handy Windows Management Instrumentation Command-line (WMIC)—a command-line interface for Microsoft's powerful WMI tool.

 With the WMIC, you can entry the query baseboard to check motherboard stats, and then use additional modifiers like get Manufacturer, Model, Name, PartNumber, slotlayout, serialnumber, or poweredon to get more detailed information about the motherboard.

 As an example, let's check a motherboard's manufacturer, model number, and serial number using WMIC.

 Open up the command prompt in Windows via either the run dialog (Windows+R) or by searching for "cmd" on the Start menu—no need to run the Command Prompt as an administrator. And, as we mentioned, you could also use PowerShell here, if you prefer. The command works the same in both shells. At the command line, type the following text (noting that there are no spaces between the modifiers—just commas), and then hit Enter:

wmic baseboard get product,Manufacturer,version,serialnumber

![The Command Prompt will display your motherboard manufacturer and model.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/wmic_1.png) 

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The information returned checks out for the motherboard we're using: the manufacturer is Gigabyte, the board is the Z170X-Gaming 7, and while the WMIC tool tried to check the serial number, Gigabyte left that particular bit unfilled for whatever reason. Nonetheless, the WMIC tool functioned just as it should, and without opening the case or using any third party tools, we have the basic information we're looking for.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
##  Check Your Model Number in System Information

 System Information is a no-frills way to look up the details of your PC's hardware and software. There are two easy ways to launch it. Click the Start button, type "System Information" into the search bar, and then hit Enter or click "Open."

![Click the Start button, type "system information" into the search bar, then hit Enter or click "Open."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/click-system-information.png) 

 Alternatively, you can use the Run window. Hit Windows+R to open a run dialog, then type "msinfo32" into the Run prompt and hit Enter.

 The "System Summary" page will be open by default. Scroll down and look for the line named "BaseBoard Product"—that is your motherboard.

![Look for a line named "BaseBoard Product." That is your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/look-for-baseboard-product.png) 

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Check Your Model Number with Speccy

 If you want another GUI-based way to check your motherboard's model number (as well as a method that yields more information at a glance than the WMIC tool), you can grab the free tool [Speccy](https://www.piriform.com/speccy). It's a handy app to have around.

 After downloading and installing Speccy, go ahead and fire it up.

 You can see the motherboard model number right on the summary page, along with it's current operating temperature (assuming your board includes that). You can also see basic details about other system components.

![The &quot;Summary&quot; page will display your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/wmic_2.png) 

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
 Click over to the "Motherboard" tab on the left to see even more information about your motherboard, including details about the chipset and voltages, along with the types of slots included on the board and whether or not they're currently in use.

![The &quot;Motherboard&quot; tab has more specific information about your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/wmic_3.png) 

##  Check Your Motherboard Model with HWiNFO64

[HWiNFO64](https://www.fosshub.com/HWiNFO.html) displays most of the same information as Speccy, though it looks fairly different. Downlod and launch it to get started.

 Be careful that any "Download" link you click is actually for HWiNF64, not an advertisement.

 HWiNFO64 can display any of the information about your system, including all of the information available from the sensors. That isn't necessary in this case and will only add to the clutter, so launch HWiNFO64 in "Summary-Only" mode.

 Tick the box that says "Summary-Only," then click "Start."

![Tick the box that says "Summary-Only," then click "Start."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/tick-summary-only-then-click-start.png) 

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You'll see a window that displays everything about your PC's hardware. The left section gives you all of the details about your [CPU](https://facebook-clips.techidaily.com/echoes-of-now-strategies-for-downloading-current-events/), the middle section provides information about your [motherboard](https://tech-savvy.techidaily.com/uniting-giants-how-bzs-games-meet-microsofts-ai-visionaries-tech-dialogue/) and [RAM](https://youtube-web.techidaily.com/ed-2024-approved-unlocking-youtube-success-top-video-strategies-to-explode-views/), and the right-most section focuses on your [GPU](https://android-unlock.techidaily.com/unlock-vivo-s17-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/) and hard drives.

![The HWiNFO64 summary window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/the-summar-window.png) 

 The first few lines will tell you everything you need to know about your motherboard, including the model name, number, BIOS version, and manufacturer.

![The motherboard segment will be near the top-middle of the window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/motherboard-setting.png) 

 If none of those options work, you can always [boot into the BIOS or UEFI](https://apple-account.techidaily.com/in-2024-turning-off-two-factor-authentication-on-iphone-14-pro-max-5-tips-you-must-know-by-drfone-ios/). The motherboard model number and manufacturer are usually plainly displayed somewhere on the BIOS or UEFI main menu.

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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-tech-savvy-tips-for-recording-video-calls/"><u>[New] 2024 Approved  Tech-Savvy Tips for Recording Video Calls</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-a-comprehensive-dive-into-creating-inspiring-slow-mo-videos-on-ig/"><u>[New] A Comprehensive Dive Into Creating Inspiring Slow Mo Videos on IG</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-effective-ways-to-tweak-songs-playback-rate-on-spotify/"><u>[New] Effective Ways to Tweak Songs' Playback Rate on Spotify</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-mediamasher-suite/"><u>[New] MediaMasher Suite</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-charting-the-peak-1-shorter-videos-downloader-hub/"><u>[Updated] 2024 Approved  Charting the Peak  #1 Shorter Videos Downloader Hub</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elite-alternative-edits-skip-youtube-not-just-content-for-2024/"><u>[Updated] Elite Alternative Edits  Skip Youtube, Not Just Content for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-farm-management-mastery-for-stardews-ginger-isles-for-2024/"><u>[Updated] Farm Management Mastery for Stardew's Ginger Isles for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unlock-hidden-potential-boost-productivity-essential-multitasking-tips-for-podcast-lovers/"><u>[Updated] Unlock Hidden Potential, Boost Productivity  Essential Multitasking Tips for Podcast Lovers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-editors-pathway-for-diminishing-sound-levels/"><u>2024 Approved  The Editor's Pathway for Diminishing Sound Levels</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/2024s-leading-console-platforms-for-gamers/"><u>2024'S Leading Console Platforms for Gamers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/address-webview-compatibility-for-fb-streaming-for-2024/"><u>Address WebView Compatibility for FB Streaming for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/complete-walkthrough-on-how-to-permanently-remove-your-tiktok-profile/"><u>Complete Walkthrough on How to Permanently Remove Your TikTok Profile</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/demystifying-bsod-errors-on-pcs-what-you-need-to-know/"><u>Demystifying BSOD Errors on PCs – What You Need to Know</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/eero-pro-mesh-wi-fi-system-review-a-router-to-cover-your-entire-home/"><u>Eero Pro Mesh Wi-Fi System Review: A Router to Cover Your Entire Home</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/elevate-your-feed-with-these-507-killer-instagram-captions-of-2024/"><u>Elevate Your Feed with These 507 Killer Instagram Captions of 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-common-reasons-for-zoom-lag-and-how-to-address-them/"><u>Exploring Common Reasons for Zoom Lag and How to Address Them</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-safely-modify-your-password-on-the-updated-platform-x/"><u>How To Safely Modify Your Password on The Updated Platform, X</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-stop-receiving-emergency-and-amber-alerts-on-your-iphone-step-by-step-guide/"><u>How to Stop Receiving Emergency and Amber Alerts on Your iPhone: Step-by-Step Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-realme-c55-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Realme C55 Through Google Earth?</u></a></li>
<li><a href="https://driver-download.techidaily.com/latest-version-of-magicard-rio-driving-experience-now-available-download-for-windows-users/"><u>Latest Version of Magicard Rio Driving Experience Now Available: Download for Windows Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/master-the-process-of-flushing-and-restoring-your-systems-bios-configuration-with-cmos-clears/"><u>Master the Process of Flushing and Restoring Your System's BIOS Configuration with CMOS Clears</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-royal-match-a-step-by-step-guide/"><u>Mastering 'Royal Match': A Step-by-Step Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/new-release-get-the-latest-amd-radeon-r5-drivers-compatible-with-windows-111087/"><u>New Release: Get the Latest AMD Radeon R5 Drivers Compatible with Windows 11/10/8/7</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/questband-meta-series-latest-updates-on-features-pricing-and-launch-timeline/"><u>QuestBand Meta Series - Latest Updates on Features, Pricing & Launch Timeline</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/simplifying-email-management-how-to-automate-sorting-in-gmail-with-personalized-rules/"><u>Simplifying Email Management: How to Automate Sorting in Gmail With Personalized Rules</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/siris-speech-functionality-a-step-by-step-guide-to-screen-to-speech-conversion-for-iosmacos-users/"><u>Siri's Speech Functionality: A Step-by-Step Guide to Screen-to-Speech Conversion for iOS/macOS Users</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sound-seekers-free-beats-detection-tools-for-2024/"><u>Sound Seekers  Free Beats Detection Tools for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/stay-on-top-of-your-fitness-goals-with-these-10-essential-exercise-logging-tools-in-amelie2024/"><u>Stay on Top of Your Fitness Goals with These 10 Essential Exercise Logging Tools in Amelie_2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-downloading-fandango-app-onto-your-firestick/"><u>Step-by-Step Guide: Downloading Fandango App Onto Your Firestick</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-great-gopro-race-hero5-black-vs-hero4-silver-edition/"><u>The Great GoPro Race  Hero5 Black V/S Hero4 Silver Edition</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-5-preferred-iphone-gps-navigation-applications/"><u>Top 5 Preferred iPhone GPS Navigation Applications</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/top-fonts-to-amplify-your-tiktok-presence-in-23-for-2024/"><u>Top Fonts to Amplify Your TikTok Presence in '23 for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-picks-disneyplus-must-watch-films-of-the-moment/"><u>Top Picks: Disney+ Must-Watch Films of the Moment</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshoot-cant-be-opened-dev-cant-be-verified-solutions-for-mac-users/"><u>Troubleshoot 'Can’t Be Opened - Dev Can't Be Verified': Solutions for Mac Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-steps-if-amazon-echo-alexa-stops-responding/"><u>Troubleshooting Steps If Amazon Echo (Alexa) Stops Responding</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-combining-your-favorite-songs-into-one-master-spotify-list/"><u>Ultimate Guide: Combining Your Favorite Songs Into One Master Spotify List</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlock-the-power-of-google-gemini-with-these-tips/"><u>Unlock the Power of Google Gemini with These Tips</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-cost-savings-find-the-top-7-free-internet-fax-services/"><u>Unlocking Cost Savings: Find the Top 7 Free Internet Fax Services</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-magic-behind-internet-ready-television-sets/"><u>Unveiling the Magic Behind Internet-Ready Television Sets</u></a></li>
</ul></div>
