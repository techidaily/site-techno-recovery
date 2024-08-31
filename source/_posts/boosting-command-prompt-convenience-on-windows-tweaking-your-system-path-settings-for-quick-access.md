---
title: "Boosting Command Prompt Convenience on Windows: Tweaking Your System PATH Settings for Quick Access"
date: 2024-08-30T13:08:40.982Z
updated: 2024-08-31T13:08:40.982Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/9986a0298b6ed41baf9ff52abd2373f4874f20858ec27b5c29bc07659651b716.jpg
---

## Boosting Command Prompt Convenience on Windows: Tweaking Your System PATH Settings for Quick Access

### Quick Links

* [What Is the Windows System PATH?](https://facebook-record-videos.techidaily.com/updated-harmonizing-youtube-content-a-guide-to-blending-files/)
* [How to Add a Folder to Your PATH](https://fox-cloud.techidaily.com/new-quirky-creations-your-guide-to-no-cost-memes/)

### Key Takeaways

 The PATH tells Windows where it should look for executables, making them accessible via command-line interfaces or scripts. To add a new folder to PATH, navigate to Advanced System Settings > Environment Variables, select PATH, click "Edit" and then "New."

 Have you ever wondered why you can just type ipconfig into a command prompt and it works, but when you want to use a command line program you downloaded you have to navigate to its directory first? Here's how to fix that using the Windows System PATH on Windows 10 and Windows 11.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
##  What Is the Windows System PATH?

 The Windows System PATH tells your PC where it can find specific directories that contain executable files. Ipconfig.exe, for example, is found in the C:\\Windows\\System32 directory, which is a part of the system PATH by default. When you type ipconfig into a Command Prompt, Windows doesn't need to know where that EXE is—it'll check all the folders in its PATH until it finds the right one.

 If you've downloaded a program that uses a command-line interface—like ADB, the [Android Debug Bridge](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/)—you can't just type adb in the Command Prompt or PowerShell to run it, like you can with Windows' built-in commands (e.g.ipconfig). Instead, you have to tell Command Prompt where to find that file, by typing in the full path of the EXE:

C:\Android\platform-tools\adb.exe

 If you don't, you'll get an error message like this.

![ADB is not recognized since it is not on the system PATH.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/adb-error.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 That's a lot of typing, especially for something you have to run often.

 If you want the same convenience with a program you downloaded (like ADB), you need to add its folder to Windows' system PATH. That way, when you need to run adb, you can just run:

adb

 No extra typing necessary.

##  How to Add a Folder to Your PATH

 These steps are basically the same on Windows 10 and Windows 11\. There are just some minor differences in the user interface.

 Start by pressing the Windows key to open up the Start Menu, then search for "advanced system settings." You can alternatively browse through Control Panel to System and Security > System and click on the "Advanced system settings" hyperlink in the left-hand pane.

![Search for and open "Advanced System Settings."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/advanced-system.png) 

 Once the System Properties window opens, click on the "Environment Variables" button.

![Click &quot;Environment Variables.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/environmental-variables.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In the "System Variables" box, look for a variable called _Path._ Select that and click on the "Edit" button.

 You can modify the PATH for only the current user by changing the PATH variable under "User Variables." It won't affect other users, however. In many cases, it is better and more convenient to add something to the system PATH, so it is universally accessible on your PC.

![Select &quot;PATH&quot; under &quot;System Variables,&quot; then click &quot;Edit.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/system-variables.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
 This process is both easier and less confusing in Windows 10 and Windows 11 than it was in earlier versions of Windows. Once you've clicked the edit button, a new dialog box will appear with each location in the PATH on a separate line. This is a dramatic improvement over the way previous versions of Windows handled PATH locations and makes easy work of adding a new one.

![The current PATH.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/PATH-Stuff.png) 

 First, click the 'new' button, which will add a line at the end of the list. Add your location—"C:\\AndroidSDK" in our example—and hit Enter. Click the "OK" button and you're finished.

 Older versions of Windows required each line end with a semi-colon, but Windows 10 and 11 do not if you use the user interface like we are here. If you use a command-line interface to edit the PATH, you'll still find them there.

![Click &quot;New,&quot; enter the path to ADB, then click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/android-SD.png) 

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The Android Debugging Bridge should now be accessible from any Command Prompt, PowerShell, or Windows Terminal, with no need to specify its directory.

![ADB now works in PowerShell without specifying the path manually.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/adb-on-path.png) 

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
 You can add as many locations as you like to PATH. However, convention and best practice dictate that you try to avoid cluttering up your PATH with unnecessary executables.

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-advanced-capture-strategies-for-roblox-games-mac-edition/"><u>[New] 2024 Approved  Advanced Capture Strategies for Roblox Games (Mac Edition)</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-unlocking-potential-an-in-depth-look-at-vivocut-editing/"><u>[New] Unlocking Potential  An In-Depth Look at VivoCut Editing</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-easy-to-follow-guide-leveraging-mobizen-screensaver/"><u>[Updated] In 2024, Easy-to-Follow Guide  Leveraging Mobizen Screensaver</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-invisible-riches-the-online-auction-exclusive-to-the-elusive-2023-edition/"><u>[Updated] Invisible Riches  The Online Auction Exclusive to the Elusive, 2023 Edition</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitters-videography-policy-including-aspect-ratios-is-crucial/"><u>[Updated] Twitter's Videography Policy  Including Aspect Ratios Is Crucial</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-ultimate-budget-free-fb-visual-media-maker/"><u>[Updated] Ultimate Budget-Free FB Visual Media Maker</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-vivo-y27-5g-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Vivo Y27 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/6-reasons-your-car-battery-keeps-dying/"><u>6 Reasons Your Car Battery Keeps Dying</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ace-your-selfies-expert-tips-on-harnessing-the-power-of-selfie-lights/"><u>Ace Your Selfies: Expert Tips on Harnessing the Power of Selfie Lights</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/best-alternatives-to-chatgpt-a-guide-to-the-10-leading-conversational-ai-platforms/"><u>Best Alternatives to ChatGPT: A Guide to the 10 Leading Conversational AI Platforms</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722878544362-best-free-tools-and-apps-for-students-get-ready-for-back-to-school/"><u>Best Free Tools & Apps for Students: Get Ready for Back-to-School!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brilliant-obsidian-structure-for-clear-notes/"><u>Brilliant Obsidian Structure for Clear Notes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/build-a-stronger-twitter-network-insider-tips-and-tricks-for-growing-your-following-fast/"><u>Build a Stronger Twitter Network: Insider Tips and Tricks for Growing Your Following Fast!</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723013531313-chrome-not-loading-pages-heres-how-to-get-it-fixed/"><u>Chrome Not Loading Pages? Here's How to Get It Fixed</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/creating-an-oculus-questquest-2-user-profile-tutorial/"><u>Creating an Oculus Quest/Quest 2 User Profile Tutorial</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/decoding-the-mystery-how-to-successfully-reconnect-with-unidentified-callers/"><u>Decoding the Mystery: How To Successfully Reconnect with Unidentified Callers</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/dependable-app-for-retrieving-missing-iphone-data-get-peace-of-mind-today/"><u>Dependable App for Retrieving Missing iPhone Data: Get Peace of Mind Today</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-latest-macos-a-comprehensive-version-list/"><u>Discover the Latest macOS: A Comprehensive Version List</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-steps-for-background-blurring-on-google-meet-sessions/"><u>Effective Steps for Background Blurring on Google Meet Sessions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/elevate-your-insta-game-ultimate-techniques-for-accumulating-more-followers/"><u>Elevate Your Insta Game: Ultimate Techniques for Accumulating More Followers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exciting-childrens-movie-selection-on-disneyplus-for-july-2024-our-curated-list/"><u>Exciting Children’s Movie Selection on Disney+ for July 2024 – Our Curated List</u></a></li>
<li><a href="https://fox-http.techidaily.com/explore-the-most-reliable-photo-background-alternation-apps-for-2024/"><u>Explore the Most Reliable Photo-Background Alternation Apps for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-the-best-news-curators-of-2024-the-ultimate-list/"><u>Exploring the Best News Curators of 2024 – The Ultimate List!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/family-planning-simplified-discover-the-7-shared-digital-calendars-that-work-wonders/"><u>Family Planning Simplified: Discover the 7 Shared Digital Calendars That Work Wonders</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/getting-going-right-5-must-do-steps-when-you-get-fresh-tech-gear/"><u>Getting Going Right: 5 Must-Do Steps When You Get Fresh Tech Gear</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-to-turning-off-government-alert-systems-in-android-settings/"><u>Guide to Turning Off Government Alert Systems in Android Settings</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-streaming-your-android-device-content-on-amazon-fire-tv/"><u>Guide: Streaming Your Android Device Content on Amazon Fire TV</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-correctly-handle-dbghelpdll-is-missing-errors-and-get-back-online/"><u>How to Correctly Handle 'dBghelp.dll Is Missing Errors' & Get Back Online</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-find-someones-email-address/"><u>How to Find Someone's Email Address</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-realme-narzo-n55-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Realme Narzo N55 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-infinix-note-30-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/master-the-solution-to-restore-ocidll-errors-and-ensure-smooth-system-performance/"><u>Master the Solution to Restore oci.dll Errors and Ensure Smooth System Performance</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-network-diagnostics-a-comprehensive-guide-to-using-the-tracert-command-on-windows/"><u>Mastering Network Diagnostics: A Comprehensive Guide to Using the Tracert Command on Windows</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-online-interaction-with-leading-networks-facebook-twitter-instagram-and-youtube/"><u>Mastering Online Interaction with Leading Networks: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/maximizing-mobile-use-timely-decisions-for-phone-upgrades/"><u>Maximizing Mobile Use: Timely Decisions for Phone Upgrades</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ps4-screen-capture-guide-simple-steps-to-taking-perfect-screenshots/"><u>PS4 Screen Capture Guide: Simple Steps to Taking Perfect Screenshots</u></a></li>
<li><a href="https://hardware-help.techidaily.com/steelseries-gaming-mouse-drivers-free-downloads-available/"><u>SteelSeries Gaming Mouse Drivers - Free Downloads Available</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-eliminating-suggested-users-from-your-instagram-feed/"><u>Step-by-Step Guide: Eliminating 'Suggested Users' From Your Instagram Feed</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/tesla-smartphone-unveiled-latest-updates-on-cost-launch-timeline-and-features-full-rumor-rundown/"><u>Tesla Smartphone Unveiled: Latest Updates on Cost, Launch Timeline & Features – Full Rumor Rundown</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-comprehensive-insight-into-meta-ai-technologies/"><u>The Comprehensive Insight Into Meta AI Technologies</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-docu-series-featuring-maximillian-what-were-watching-in-july-2024/"><u>Top Docu-Series Featuring Maximillian: What We're Watching in July 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-microsoft-teams-when-is-downtime-user-error/"><u>Troubleshooting Microsoft Teams – When Is Downtime User Error?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-trick-taking-screenshots-with-your-logitech-keyboard-easily/"><u>Ultimate Trick: Taking Screenshots with Your Logitech Keyboard Easily</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlock-the-potential-of-your-ipad-free-ipados-18-update-available-with-new-innovations-and-pricing-insights/"><u>Unlock the Potential of Your iPad: Free IPadOS 18 Update Available with New Innovations and Pricing Insights!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-success-in-royal-match-essential-techniques-revealed/"><u>Unlocking Success in ‘Royal Match’: Essential Techniques Revealed</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/zoom-update-tutorial-for-pcs-and-mac-computers-a-comprehensive-approach/"><u>Zoom Update Tutorial for PCs & Mac Computers - A Comprehensive Approach</u></a></li>
</ul></div>
