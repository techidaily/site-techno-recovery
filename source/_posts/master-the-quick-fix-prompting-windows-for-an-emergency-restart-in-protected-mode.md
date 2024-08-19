---
title: "Master the Quick Fix: Prompting Windows for an Emergency Restart in Protected Mode"
date: 2024-08-18T17:37:49.711Z
updated: 2024-08-19T17:37:49.711Z
categories:
  - BestProducts
description: "This Article Describes Master the Quick Fix: Prompting Windows for an Emergency Restart in Protected Mode"
excerpt: "This Article Describes Master the Quick Fix: Prompting Windows for an Emergency Restart in Protected Mode"
thumbnail: https://thmb.techidaily.com/700877a9102ebfac6b027a9da8135a8597355f7b411786ceebe675ffa9f20381.jpg
---

## Master the Quick Fix: Prompting Windows for an Emergency Restart in Protected Mode
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### What to Know

* To force Windows to restart in Safe Mode, access Advanced Startup Options or System Recovery Options.
* Then, use a**bcdedit** command to open Safe Mode from Command Prompt.

 This article describes how to use the bcdedit command to boot into Safe Mode when[the normal method doesn't work](https://www.lifewire.com/fix-a-computer-that-always-stops-at-startup-settings-or-abo-2624445) .  

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Use 'bcdedit' to Start in Safe Mode

 Forcing Windows to restart to this special mode (or making it_stop_ starting in Safe Mode) is moderately difficult and will probably take several minutes, at most. These directions will start Safe Mode from[Command Prompt](https://www.lifewire.com/command-prompt-2625840) :

1. [Open Advanced Startup Options](https://www.lifewire.com/how-to-access-advanced-startup-options-in-windows-10-or-8-2626229) if you're on Windows 11, Windows 10, or Windows 8\. Since you can't start Windows properly, use methods 4, 5, or 6 outlined in that tutorial.  
 With Windows 7 or Vista, start System Recovery Options using your installation media or a system repair disc. Unfortunately, this process doesn't work with Windows XP.  
 If you want to force or stop Safe Mode from starting, and you actually_can_ access Windows properly, you don't need to follow the procedure below. See the much easier[How to Start Windows in Safe Mode Using System Configuration](https://www.lifewire.com/how-to-start-windows-in-safe-mode-using-system-configuration-2626115) process.
2. Open Command Prompt. If you're using Windows 7 or newer, it's located here:**Troubleshoot** \>**Advanced options** \>**Command Prompt** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![Advanced Startup Options for Windows 10](https://www.lifewire.com/thmb/FvRv0xdSCo8UanPmD9Vp0mBddjE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/aso-windows-10-5c5c3bde46e0fb000127c6d7.png)
3. Execute the correct bcdedit[command](https://www.lifewire.com/what-is-a-command-2625828) as shown below based on which Safe Mode option you'd like to start:  
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
!["bcdedit /set {default} safeboot network" command in Command Prompt](https://www.lifewire.com/thmb/tnUE5VabXIlDNfK2S4UhcOKHG9c=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_how-to-force-windows-to-restart-in-safe-mode-2625163-5c77678446e0fb0001d83cb3.jpg)  
 Be sure to type whatever command you choose_exactly_ as shown and then execute it using the**Enter** key. Spaces are very important! The { and } brackets are the ones above the \[ and \] keys on your keyboard. Two separate commands are required to start_Safe Mode with Command Prompt_ , so be sure to execute them both.  
 Safe Mode:  
 `bcdedit /set {default} safeboot minimal`  
 Safe Mode with Networking:  
 `bcdedit /set {default} safeboot network`  
 Safe Mode with Command Prompt:  
 `bcdedit /set {default} safeboot minimal bcdedit /set {default} safebootalternateshell yes`
4. A properly executed bcdedit command should return the message**The operation completed successfully** .  
 If you see one of these messages or something similar, check Step 3 again and make sure you executed the Safe Mode command properly:  
   * **The parameter is incorrect**  
   * **The set command specified is not valid**  
   * **...is not recognized as an internal or external command...**
5. Close the Command Prompt window.
6. In Windows 11, 10, and 8, select**Continue** .  
 In Windows 7 and Vista, select**Restart** .  
![ASO menu Windows](https://www.lifewire.com/thmb/s1Q2N-22YKjJTAP7l4M9BJzkNXE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_how-to-force-windows-to-restart-in-safe-mode-2625163-5c7767ddc9e77c0001f57b8c.jpg)
7. Wait while your computer or device restarts.
8. Once Windows starts, log in as you normally do and use Safe Mode however you were planning.

 Windows will continue to start in Safe Mode every time you reboot unless you undo what you did in Step 3\. The easiest way to do that is not by executing more commands but[via System Configuration](https://www.lifewire.com/how-to-start-windows-in-safe-mode-using-system-configuration-2626115) (uncheck**Safe boot** ).

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stop a Safe Mode Loop

 Try this if Windows is stuck in a sort of Safe Mode loop, preventing you from starting in normal mode again, and you've already tried the instructions in the_Important_ call-out above:

1. Start Command Prompt from_outside_ of Windows, the process outlined in Steps 1 and 2 above.
2. Execute this command once Command Prompt is open:  
 `bcdedit /deletevalue {default} safeboot`  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
!["bcdedit /deletevalue {default} safeboot" command in Command Prompt on Windows](https://www.lifewire.com/thmb/iw73ubzOfXo2zuWO1YLBafnst2A=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/004_how-to-force-windows-to-restart-in-safe-mode-2625163-5c7768a5c9e77c000136a6ae.jpg)
3. Assuming it was successfully executed (see Step 4 above),[restart your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) . Windows should start normally.

[8 Things to Consider Before Buying a Desktop PC](https://www.lifewire.com/desktop-pc-buyers-guide-832343)

 FAQ

* How do I exit Safe Mode in Windows 10?  
 Exiting Windows 10 Safe Mode is typically just a matter of[restarting your PC](https://www.lifewire.com/how-to-reboot-a-computer-2624568) . Another method is to press the**Windows key + R** , then type in "**msconfig** " and select**OK** \>**Boot** and turn off**Safe boot** under Boot Options.
* How do I enter Safe Mode in Windows XP if F8 isn't working?  
 Normally restarting Windows XP in Safe Mode is just a matter of pressing F8 during startup. If the F8 key isn't working, check your keyboard for an F-Lock key that could have turned off your F keys. Otherwise,[open your PC's BIOS menu](https://www.lifewire.com/how-to-enter-bios-2624481) and make sure**Keyboard Support USB** is turned on.

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-affluent-streaming-stars/"><u>[New] 2024 Approved  Affluent Streaming Stars</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-learn-how-to-redesign-twitters-video-display-settings/"><u>[New] In 2024, Learn How to Redesign Twitter's Video Display Settings</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-the-social-media-gurus-handbook-accelerating-your-path-to-viral-success-on-instagram/"><u>[New] In 2024, The Social Media Guru's Handbook  Accelerating Your Path to Viral Success on Instagram</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-snap-and-share-smoothly-androids-most-reliable-screen-capture-tools-of-the-eight-best/"><u>[New] Snap & Share Smoothly - Android's Most Reliable Screen Capture Tools of the Eight Best</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-blueprint-for-selecting-exceptional-hdr-cameras/"><u>[New] The Blueprint for Selecting Exceptional HDR Cameras</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-a-step-by-step-process-to-upgrade-and-update-video-covers-on-social-media/"><u>[Updated] 2024 Approved  A Step-by-Step Process to Upgrade and Update Video Covers on Social Media</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-acclaimed-vehicle-monitoring-systems-explained-for-2024/"><u>[Updated] Acclaimed Vehicle Monitoring Systems Explained for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-cutting-edge-tactics-for-sharing-video-content-from-twitter-and-whatsapp-for-2024/"><u>[Updated] Cutting-Edge Tactics for Sharing Video Content From Twitter and WhatsApp for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-complete-igtv-user-manual/"><u>[Updated] In 2024, The Complete IGTV User Manual</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-meme-ology-the-science-of-popularizing-video-laughs-on-social-platforms/"><u>[Updated] Meme-Ology  The Science of Popularizing Video Laughs on Social Platforms</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-redesigned-look-at-s3700-sony-entertainment/"><u>[Updated] Redesigned Look at S3700 Sony Entertainment</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/19-effective-solutions-how-to-troubleshoot-netflix-issues-on-your-lg-television/"><u>19 Effective Solutions: How to Troubleshoot Netflix Issues on Your LG Television</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/bypass-the-box-embrace-entertainment-viewing-roku-content-on-different-platforms/"><u>Bypass the Box, Embrace Entertainment: Viewing Roku Content on Different Platforms</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/decoding-rcs-texts-understanding-rich-communication-services/"><u>Decoding RCS Texts: Understanding Rich Communication Services</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-ultimate-list-10-amazing-chefs-shows-streaming-on-netflix/"><u>Discover the Ultimate List: 10 Amazing Chef's Shows Streaming on Netflix</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-fixes-for-addressing-the-winhttpdll-component-missing-problem/"><u>Effective Fixes for Addressing The Winhttp.dll Component Missing Problem</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effortless-disneyplus-streaming-on-chromecast-the-ultimate-connection-guide/"><u>Effortless Disney+ Streaming on Chromecast: The Ultimate Connection Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-for-reconnecting-an-unresponsive-ipad-to-wi-fi-networks/"><u>Guide for Reconnecting an Unresponsive iPad to Wi-Fi Networks</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-do-ipads-distinguish-themselves-from-other-tablets/"><u>How Do iPads Distinguish Themselves From Other Tablets?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-engage-in-cooperative-play-with-your-buddy-using-pokemon-go/"><u>How To Engage In Cooperative Play With Your Buddy Using Pokémon GO</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-make-the-most-of-live-photo-upgrades-on-ios-16-devices/"><u>How to Make the Most of Live Photo Upgrades on iOS 16 Devices</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-itel-a60-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Itel A60</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-repair-missing-steamdll-error-effective-strategies-explored/"><u>How to Repair 'Missing Steam.dll Error': Effective Strategies Explored</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Samsung Galaxy A05? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-use-special-features-virtual-location-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Honor X50i? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>In 2024, Methods to Change GPS Location On Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-the-excellent-church-streaming-services/"><u>In 2024, Navigating the Excellent Church Streaming Services</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/incorporating-scripts-into-word-docs-a-comprehensive-walkthrough/"><u>Incorporating Scripts Into Word Docs: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/leading-small-form-factor-systems-for-gamers/"><u>Leading Small Form-Factor Systems for Gamers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/leveraging-meta-ai-tools-for-enhanced-engagement-on-instagram/"><u>Leveraging Meta AI Tools for Enhanced Engagement on Instagram</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/microsoft-365-setup-masterclass-for-windows-users-installation-and-configuration/"><u>Microsoft 365 Setup Masterclass for Windows Users: Installation and Configuration</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/microsoft-surface-go-evaluation-a-budget-friendly-device-with-an-unclear-role/"><u>Microsoft Surface Go Evaluation: A Budget-Friendly Device with an Unclear Role</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/perfecting-instagram-story-soundtracks-tips-and-tricks/"><u>Perfecting Instagram Story Soundtracks: Tips and Tricks</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/reactivating-closed-captions-on-your-roku-device-a-comprehensive-guide/"><u>Reactivating Closed Captions on Your Roku Device - A Comprehensive Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-smart-8-pro-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Smart 8 Pro</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722889164468-resolving-the-netflix-issue-understanding-and-repairing-error-code-ui-800-3/"><u>Resolving the Netflix Issue: Understanding and Repairing Error Code UI-800-3</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/revealed-apples-next-gen-audio-wearable-pricing-launch-and-features-uncovered/"><u>Revealed: Apple's Next-Gen Audio Wearable - Pricing, Launch & Features Uncovered!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/reverse-your-snaps-like-a-pro-a-comprehensive-tutorial/"><u>Reverse Your Snaps Like a Pro: A Comprehensive Tutorial</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/samsung-smart-tv-app-management-how-to-download-and-enjoy-new-apps/"><u>Samsung Smart TV App Management: How to Download and Enjoy New Apps</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-tutorial-how-to-effectively-take-screenshots-with-a-logitech-keyboard/"><u>Step-by-Step Tutorial: How to Effectively Take Screenshots with a Logitech Keyboard</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/steps-for-monitoring-monthly-internet-consumption/"><u>Steps for Monitoring Monthly Internet Consumption</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-complete-breakdown-of-modern-wireless-technologies-from-802nbgwi-fi-protocols-to-the-latest-80211ax-series/"><u>The Complete Breakdown of Modern Wireless Technologies: From 802.nB/gWi-Fi Protocols to the Latest 802.11Ax Series</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-future-of-google-events-breaking-down-buzz-and-upcoming-announcements/"><u>The Future of Google Events: Breaking Down Buzz and Upcoming Announcements</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-next-leap-in-audio-tech-google-pixel-buds-pro-2-revealed-explore-price-predictions-release-timing-and-rumored-features/"><u>The Next Leap in Audio Tech – Google Pixel Buds Pro 2 Revealed! Explore Price Predictions, Release Timing & Rumored Features</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-guide-achieving-verification-badge-on-the-revamped-social-platform-formerly-known-as-twitter/"><u>The Ultimate Guide: Achieving Verification Badge on the Revamped Social Platform, Formerly Known as Twitter</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/this-title-suggests-an-upgrade-in-skills-that-will-unlock-more-capabilities-on-your-pc-appealing-to-power-users-and-enthusiasts-looking-for-deeper-insights.53/"><u>This Title Suggests an Upgrade in Skills that Will Unlock More Capabilities on Your PC, Appealing to Power Users and Enthusiasts Looking for Deeper Insights.</u></a></li>
<li><a href="https://os-tips.techidaily.com/top-3-effective-ways-to-securely-backup-your-android-device/"><u>Top 3 Effective Ways to Securely Backup Your Android Device</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-to-keeping-your-files-safe-with-these-5-steps/"><u>Ultimate Guide to Keeping Your Files Safe with These 5 Steps</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-list-of-free-film-streamers-top-12-picks/"><u>Ultimate List of Free Film Streamers: Top 12 Picks</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-efficiency-a-guide-to-activating-and-leveraging-the-secret-sidebar/"><u>Unlocking Efficiency: A Guide to Activating & Leveraging The Secret Sidebar</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-tips-for-microsoft-windows-11-removing-your-personal-identification-number-pin/"><u>Unlocking Tips for Microsoft Windows 11: Removing Your Personal Identification Number (PIN)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-your-pcs-power-a-guide-to-activating-the-stealthy-find-bar/"><u>Unlocking Your PC's Power: A Guide to Activating the Stealthy Find Bar</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-true-eco-friendliness-of-electric-cars/"><u>Unveiling the True Eco-Friendliness of Electric Cars</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/what-does-it-mean-when-your-pc-turns-blue-insights-into-the-causes-and-implications-of-bsod-errors/"><u>What Does It Mean When Your PC Turns Blue? Insights Into the Causes and Implications of BSOD Errors</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/whats-new-with-meta-quest-3-dive-into-pricing-info-release-timeline-and-hardware-specs/"><u>What's New with Meta Quest 3? Dive Into Pricing Info, Release Timeline & Hardware Specs</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-vivo-v27e-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Vivo V27e Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/xbox-one-display-problems-solved-a-step-by-step-guide-to-restoring-the-connection/"><u>Xbox One Display Problems Solved - A Step-by-Step Guide to Restoring The Connection</u></a></li>
</ul></div>
