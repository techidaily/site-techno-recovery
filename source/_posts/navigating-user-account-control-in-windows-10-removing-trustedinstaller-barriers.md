---
title: "Navigating User Account Control in Windows 10: Removing TrustedInstaller Barriers"
date: 2024-09-09T09:13:53.641Z
updated: 2024-09-10T09:13:53.641Z
categories:
  - BestProducts
description: "This Article Describes Navigating User Account Control in Windows 10: Removing TrustedInstaller Barriers"
excerpt: "This Article Describes Navigating User Account Control in Windows 10: Removing TrustedInstaller Barriers"
thumbnail: https://thmb.techidaily.com/bf4984e0ce61370d66d64dec7394dd5194f1497b8dcd59101ee95e0bac57c052.jpg
---

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Navigating User Account Control in Windows 10: Removing TrustedInstaller Barriers
### What to Know

* Use the**TAKEOWN** and**icacls** Command Prompt commands to take ownership of the file or folder.
* Or, right-click the item and go to**Properties** \>**Security** \>**Advanced** to add yourself to the list.
* TrustedInstaller is a built-in user account that owns lots of important system files.

 This article describes two ways to deal with the message in Windows 10 about needing permission from TrustedInstaller to make changes to a file or folder.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135403/19272" target="_top" id="2135403">
  <img src="//a.impactradius-go.com/display-ad/19272-2135403" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135403/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix the TrustedInstaller Error Using Command Prompt

 There are two really simple[Command Prompt commands](https://www.lifewire.com/list-of-command-prompt-commands-4092302) you can use to bypass the TrustedInstaller permissions prompt. Follow these steps to fix the TrustedInstaller "error" by granting your user account permission to make changes to the file or folder:

1. [Open an elevated Command Prompt](https://www.lifewire.com/how-to-open-an-elevated-command-prompt-2618088) . The quickest way there is to search for it from the Start menu, right-click the result, and choose**Run as administrator** .  
![The Run As Administrator option for the Windows 10 Command Prompt](https://www.lifewire.com/thmb/qK50_I4SdSJ98eEbO9R6yPSN1Vk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/command-prompt-admin-windows-10-45f7ecab69a442f489eaf6a499a353d4.png)
2. Enter**TAKEOWN /F** and then type the file or folder name. Here's an example:  
 `TAKEOWN /F C:\Windows\System32\fr-FR\fms.dll.mui`
3. Press**Enter** to take control of the file. You'll see a success message if the command executed correctly.  
![The TAKEOWN /F command in Windows 10 Command Prompt](https://www.lifewire.com/thmb/nOnoS4n34cd8C2EJEDT2_rLzdhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/takeown-command-trustsedinstaller-windows-10-267bfffb4f974a29940a0af233ef4a84.png)
4. Enter the following command (replacing our example file with your own) to immediately give your user account permission to delete or change the file or folder:  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115913/19272" target="_top" id="2115913">
  <img src="//a.impactradius-go.com/display-ad/19272-2115913" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115913/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 `icacls C:\Windows\System32\fr-FR\fms.dll.mui /grant Administrators:F /T`  
![icacls command executed in Windows 10 Command Prompt](https://www.lifewire.com/thmb/clN3CT0-H0V3QdOSRZWprDCigZ4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/icacls-command-windows-10-7f562cffaf424cd281b4e58c68b19e25.png)

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Edit the File's Security Options to Fix the TrustedInstaller Error

 If you don't feel comfortable using Command Prompt to take ownership of the folder or file, there is another way. Here's how to use File Explorer to edit the security settings for the data, which will let you delete or modify it as needed.

Make sure you are logged in as an administrator.

1. Locate the item you need permission to change and then right-click it and choose**Properties** .  
![The context menu for a Windows 10 folder ](https://www.lifewire.com/thmb/CSwAkry59uiW_sJ5GzqkO0QrOuk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/context-menu-folder-windows-10-0447423a01764cecad790f8dc6303c59.png)
2. Go to**Security** \>**Advanced** , then select**Change** next to**Owner: TrustedInstaller** .  
<!-- affiliate ads begin -->
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Properties and Advanced Security Settings options for a Windows 10 folder](https://www.lifewire.com/thmb/823H3LgLGW5GbhyNSwSn1HNUZlk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/advanced-security-settings-windows-10-folder-4eb4fed4cb134eb1ba00993a705f7175.png)
3. Type your username into the text box and then choose**Check Names** \>**OK** .  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows 10 Check Names box with a user account listed](https://www.lifewire.com/thmb/ESMv2bIcNtWxpryKYLlwZFwmyCA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-10-select-user-or-group-880cbe35a52348f19d11206db4d7a0b6.png)
4. Check the box next to**Replace owner on subcontainers and objects** .  
![The replace owner on subcontainers and objects checkbox in Windows 10](https://www.lifewire.com/thmb/n8OW45wPPq3HiSTrW4eQIT_Y0EU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-owner-windows-10-folder-885ef894881e4e21a60b1b09568ea020.png)
5. Select**OK** at the bottom and then**OK** on the Properties window you opened in Step 1.
<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Open**Properties** \>**Security** \>**Advanced** once more. This time, select**Add** .  
![The Advanced Security Settings for a Windows 10 folder](https://www.lifewire.com/thmb/fEVYPGbUtSiGdO8kZg1RZd6gtIE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/add-button-advanced-security-settings-3ffcde5bc8b942278219bbd9b4663921.png)
7. Choose**Select a principal** and then type your username in the box.
<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Press**Check Names** \>**OK** .  
![A user account listed in the Select User or Group box for a Windows 10 folder](https://www.lifewire.com/thmb/a8Ie_eyPviEwOjytgb9HHofaQgc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/select-user-group-windows-10-security-b2ffe7d116f2424e845a612090d4e932.png)
9. Check the box next to**Full control** , then select**OK** .  
![The Full Control permission selected for a folder in Windows 10](https://www.lifewire.com/thmb/cLa_4Jv8moyuFMZaNvHFNWAcllw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/full-control-folder-permissions-b0f31e6f8d7d418e91990e6c32476c30.png)
10. Check the box next to **Replace all child object permission entries with inheritable permission entries from this object** .  
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
<li><a href="https://youtube-blog.techidaily.com/conomical-audio-devices-for-vloggers-on-a-budget-for-2024/"><u>[New] Economical Audio Devices for Vloggers on a Budget for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-the-ultimate-guide-to-free2x-cam-recorders/"><u>[New] In 2024, The Ultimate Guide to Free2X Cam Recorders</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-a-streamlined-approach-simplifying-film-projects-with-movie-maker/"><u>[Updated] A Streamlined Approach  Simplifying Film Projects with Movie Maker</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-enhancing-content-with-youtube-tags-and-notes/"><u>[Updated] Enhancing Content with YouTube Tags & Notes</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/3-ways-to-export-contacts-from-apple-iphone-8-to-excel-csv-and-vcard-easily-drfone-by-drfone-transfer-from-ios/"><u>3 Ways to Export Contacts from Apple iPhone 8 to Excel CSV & vCard Easily | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/adherence-to-prescribed-medications-such-as-antibiotics-and-anti-inflammatory-eye-drops-is-essential-to-prevent-complications/"><u>Adherence to Prescribed Medications, Such as Antibiotics and Anti-Inflammatory Eye Drops, Is Essential to Prevent Complications</u></a></li>
<li><a href="https://discover-helper.techidaily.com/best-free-full-featured-windows-1110-dvd-ripper-tools-top-picks-no-cost-downloads/"><u>Best Free Full-Featured Windows 11/10 DVD Ripper Tools (Top Picks) – No Cost Downloads</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/digital-disguise-tactics-hiding-or-faking-location-data-on-smartphones/"><u>Digital Disguise Tactics: Hiding or Faking Location Data on Smartphones</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-advice-on-repairing-broken-email-functionality-on-your-iphone/"><u>Expert Advice on Repairing Broken Email Functionality on Your iPhone.</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-advice-how-to-permanently-remove-pictures-from-facebook/"><u>Expert Advice: How to Permanently Remove Pictures From Facebook</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-tips-to-prevent-adobe-premiere-pro-from-crashing-on-modern-windows-operating-systems/"><u>Expert Tips to Prevent Adobe Premiere Pro From Crashing on Modern Windows Operating Systems</u></a></li>
<li><a href="https://facebook.techidaily.com/exploring-subtextual-innuendoes-in-messenger-correspondence/"><u>Exploring Subtextual Innuendoes in Messenger Correspondence</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/fix-your-pc-the-ultimate-solution-to-shell32dll-errors/"><u>Fix Your PC: The Ultimate Solution to Shell32.dll Errors</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-vivo-y100-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-free-space-clearing-out-applications-from-your-samsung-4k-tv-setup/"><u>How to Free Space: Clearing Out Applications From Your Samsung 4K TV Setup</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-vivo-y17s-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Vivo Y17s Without Password | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-listen-to-spotify-with-friends/"><u>How to Listen to Spotify With Friends</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-navigating-networked-video-streaming-with-vlc/"><u>In 2024, Navigating Networked Video Streaming with VLC</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-design-review-and-rankings-of-top-17-graphic-software-choices/"><u>Mastering Design: Review & Rankings of Top 17 Graphic Software Choices</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-fix-detailed-instructions-on-handling-d3dx940-missing-dll-error/"><u>Mastering the Fix: Detailed Instructions on Handling 'D3dx9_40 Missing DLL' Error</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-the-world-of-stereo-speakers-key-considerations-for-savvy-shoppers/"><u>Navigating the World of Stereo Speakers: Key Considerations for Savvy Shoppers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-your-next-move-should-you-embrace-ios-17/"><u>Navigating Your Next Move: Should You Embrace iOS 17?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/pairing-disney-plus-with-chromecast-a-comprehensive-tutorial-on-smart-view-casting/"><u>Pairing Disney Plus with Chromecast – A Comprehensive Tutorial on Smart View Casting</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/simple-tips-how-to-switch-off-sticky-keys-in-windows-operating-system/"><u>Simple Tips: How To Switch Off Sticky Keys in Windows Operating System</u></a></li>
<li><a href="https://techtrends.techidaily.com/sneak-peek-into-the-future-with-samsungs-2025-unpacked-event-schedule-rumors-and-innovations/"><u>Sneak Peek Into the Future with Samsung's 2025 Unpacked Event - Schedule, Rumors & Innovations</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-correcting-windows-error-code-19-issues/"><u>Step-by-Step Guide: Correcting Windows Error Code 19 Issues</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-oneplus-nord-ce-3-lite-5g-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your OnePlus Nord CE 3 Lite 5G Phone Hassle-Free</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-tutorial-hp-laptop-screen-capture-techniques/"><u>The Ultimate Tutorial: HP Laptop Screen Capture Techniques</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-sound-problems-a-guide-to-solving-audio-glitches-in-powerpoint/"><u>Troubleshooting Sound Problems: A Guide to Solving Audio Glitches in PowerPoint</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-the-full-potential-of-your-lg-television-by-watching-espn-plus/"><u>Unlocking the Full Potential of Your LG Television by Watching ESPN Plus</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-new-m4-mac-mini-release-timeline-cost-estimates-and-tech-specs/"><u>Unveiling the New M4 Mac Mini - Release Timeline, Cost Estimates, and Tech Specs</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/why-does-my-car-battery-keep-going-dead-explore-these-6-reasons/"><u>Why Does My Car Battery Keep Going Dead? Explore These 6 Reasons</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/why-does-my-car-battery-keep-losing-charge-uncover-6-main-factors/"><u>Why Does My Car Battery Keep Losing Charge? Uncover 6 Main Factors</u></a></li>
</ul></div>
