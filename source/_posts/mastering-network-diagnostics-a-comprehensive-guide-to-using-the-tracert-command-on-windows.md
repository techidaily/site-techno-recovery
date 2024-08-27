---
title: "Mastering Network Diagnostics: A Comprehensive Guide to Using the Tracert Command on Windows"
date: 2024-08-26T06:09:32.200Z
updated: 2024-08-27T06:09:32.200Z
categories:
  - BestProducts
description: "This Article Describes Mastering Network Diagnostics: A Comprehensive Guide to Using the Tracert Command on Windows"
excerpt: "This Article Describes Mastering Network Diagnostics: A Comprehensive Guide to Using the Tracert Command on Windows"
thumbnail: https://thmb.techidaily.com/8408c21b7cbd2d9f3e166f2aa500c9f7130f2d3b305b1fab49ef5afa3945895c.jpg
---

## Mastering Network Diagnostics: A Comprehensive Guide to Using the Tracert Command on Windows
### What to Know

* The tracert command details the path a packet takes from your computer to the destination you specify.
* For example, enter**tracert google.com** into Command Prompt. IP addresses work, too:**tracert 192.168.1.1** .

 This article details how to use the Windows tracert[command](https://www.lifewire.com/what-is-a-command-2625828) . It includes all the switches that work with tracert and some examples that show how to write it. You might sometimes see this command referred to as_trace route_ or_traceroute_ ; it's all the same command.  

## Tracert Command Syntax

 If you know[how to read command syntax](https://www.lifewire.com/how-to-read-command-syntax-2618082) , the syntax for tracert is pretty straightforward:

**tracert** \[**\-d** \] \[**\-h** _MaxHops_ \] \[**\-w** _TimeOut_ \] \[**\-4** \] \[**\-6** \]_target_ \[**/?** \]

 The availability of certain tracert command switches and other tracert command[syntax](https://www.lifewire.com/what-is-syntax-2626014) may differ from operating system to operating system. Tracert, as it's explained below, applies to Windows only, but the command is also available for Linux.

![The tracert help command in Windows 11 Command Prompt](https://www.lifewire.com/thmb/t0M4UG3ExHKZWPdn20Q_f905i5w=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/tracert-command-51d73acf91b5468fbbec76d21719ea22.png)

| Tracert Command Options |                                                                                                                                                                                                                                                                |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Option**              | **Explanation**                                                                                                                                                                                                                                                |
| **\-d**                 | This option prevents tracert from resolving[IP addresses](https://www.lifewire.com/what-is-an-ip-address-2625920) to[hostnames](https://www.lifewire.com/what-is-a-hostname-2625906) , often resulting in much faster results.                               |
| **\-h** _MaxHops_       | This tracert option specifies the maximum number of[hops](https://www.lifewire.com/what-are-hops-hop-counts-2625905) in the search for the_target_ . If you do not specify_MaxHops_ , and a_target_ has not been found by 30 hops, tracert will stop looking. |
| **\-w** _TimeOut_       | You can specify the time, in milliseconds, to allow each reply before timeout using this tracert option.                                                                                                                                                       |
| **\-4**                 | This option forces tracert to use IPv4 only.                                                                                                                                                                                                                   |
| **\-6**                 | This option forces tracert to use IPv6 only.                                                                                                                                                                                                                   |
| _target_                | This is the destination, either an IP address or hostname.                                                                                                                                                                                                     |
| **/?**                  | Use the[help switch](https://www.lifewire.com/help-switch-2625896) with the tracert command to show detailed help about the command's several options.                                                                                                        |

 Other less commonly used options for the tracert command also exist, including \[**\-j** _HostList_ \], \[**\-R** \], and \[**\-S** _SourceAddress_ \]. Use the help switch with the Windows tracert command for more information on these options.

 Save the lengthy results of a tracert command by[redirecting the command output to a file](https://www.lifewire.com/how-to-redirect-command-output-to-a-file-2618084) with a[redirection operator](https://www.lifewire.com/redirection-operator-2625979) .

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Tracert Command Examples

 Here are some examples of the various ways you might use this command:

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Tracert to a Router

 `tracert 192.168.1.1`

 In the above example, the tracert command is used to show the path from the networked computer on which the tracert command is being executed by a network device, in this case, a router on a local network, that's assigned the _192.168.1.1_ IP address.

 The result displayed on the screen will look something like this:

 `Tracing route to 192.168.1.1 over a maximum of 30 hops`
`1 <1 ms <1 ms <1 ms 192.168.1.254`
`2 <1 ms <1 ms <1 ms 192.168.1.1`
`Trace complete.`

 In this example, you can see that tracert found a network device using the IP address of _192.168.1.254_ , let's say a network switch, followed by the destination, _192.168.1.1_ , the router.

[How to Tell What Devices Are on Your Network](https://www.lifewire.com/identify-network-hardware-ip-addresses-on-a-local-network-2624498)

### Tracert to a Website

 `tracert www.google.com`

 With the tracert command shown above, we're asking tracert to show us the path from the local computer all the way to the network device with the hostname _<www.google.com>_ .

 `Tracing route to www.l.google.com [209.85.225.104]`
`over a maximum of 30 hops:`
`1 <1 ms <1 ms <1 ms 10.1.0.1`
`2 35 ms 19 ms 29 ms 98.245.140.1`
`3 11 ms 27 ms 9 ms te-0-3.dnv.comcast.net [68.85.105.201]`
`...`
`13 81 ms 76 ms 75 ms 209.85.241.37`
`14 84 ms 91 ms 87 ms 209.85.248.102`
`15 76 ms 112 ms 76 ms iy-f104.1e100.net [209.85.225.104]`
`Trace complete.`

 In this example, we can see that tracert identified fifteen network devices including our router at _10.1.0.1_ and all the way through to the _target_ of _<www.google.com>_ , which we now know uses the public IP address of _209.85.225.104_ , one of Google's many IP addresses.

 Hops 4 through 12 were excluded above just to keep the example simple. If you were executing a real tracert, those results would all show up on screen.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
### Tracert Without Resolving Hostnames

 `tracert -d www.yahoo.com`

 With this tracert command example, we're again requesting the path to a website, this time _<www.yahoo.com>_ , but now we're preventing tracert from resolving hostnames by using the _\-d_ option.

 `Tracing route to any-fp.wa1.b.yahoo.com [209.191.122.70]`
`over a maximum of 30 hops:`
`1 <1 ms <1 ms <1 ms 10.1.0.1`
`2 29 ms 23 ms 20 ms 98.245.140.1`
`3 9 ms 16 ms 14 ms 68.85.105.201`
`...`
`13 98 ms 77 ms 79 ms 209.191.78.131`
`14 80 ms 88 ms 89 ms 68.142.193.11`
`15 77 ms 79 ms 78 ms 209.191.122.70`
`Trace complete.`

 We can see that tracert again identified fifteen network devices including our router at _10.1.0.1_ and through to the _target_ of _<www.yahoo.com>_ , which we can assume uses the public IP address of _209.191.122.70_ .

 As you can see, tracert didn't resolve any hostnames this time, which significantly sped up the process.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Save Tracert Results to a File

 `tracert -h 3 lifewire.com > z:\tracertresults.txt`

 In this last example of the tracert command in Windows, we're using _\-h_ to limit the hop count to _3_ , but instead of displaying the results in Command Prompt, we'll use the _\>_  redirection operator to send it all to a TXT file located on _Z:_ , an external hard drive.

[21 Best Command Prompt Tricks](https://www.lifewire.com/command-prompt-tricks-and-hacks-2618104)

 Here are some example results of this last command:

 `Tracing route to lifewire.com [151.101.66.114]`
`over a maximum of 3 hops:`
`1  <1 ms  <1 ms  <1 ms testwifi.here [192.168.86.1]`
`2   1 ms   1 ms  <1 ms 192.168.1.1`
`3  17 ms  16 ms  17 ms giantwls-64-71-222-1.giantcomm.net [64.71.222.1]`
`Trace complete.`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## Tracert Command Availability

 The tracert command is available from within the Command Prompt in all Windows operating systems including Windows 11, Windows 10, Windows 8, Windows 7, Windows Vista, Windows XP, and older versions of Windows as well.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Tracert Related Commands

 The tracert command is often used with other networking-related Command Prompt commands like ping,[ipconfig](https://www.lifewire.com/ip-config-818377) , netstat,[nslookup](https://www.lifewire.com/what-is-nslookup-817516) , and others. The pathping command is similar to tracert but also shows network latency and loss information.

[The Complete List of Command Prompt (CMD) Commands](https://www.lifewire.com/list-of-command-prompt-commands-4092302)

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-seamless-social-media-execution-with-the-top-8-iphone-and-android-apps/"><u>[New] 2024 Approved  Seamless Social Media Execution with The Top 8 iPhone & Android Apps</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-streamlining-your-youtube-video-logging-process/"><u>[New] 2024 Approved  Streamlining Your YouTube Video Logging Process</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-visualize-your-movies-with-best-grabbers/"><u>[New] 2024 Approved  Visualize Your Movies with Best Grabbers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solved-itunes-could-not-connect-to-the-iphone-because-an-invalid-response-was-received-from-the-device/"><u>[Solved] iTunes Could Not Connect to the iPhone because an Invalid Response Was Received From the Device</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-strategy-revealed-a-box-opening-narrative/"><u>[Updated] 2024 Approved  Strategy Revealed  A Box-Opening Narrative</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-humor-hubbub-top-7-cheeky-content-concepts-for-laughter-lovers/"><u>[Updated] Humor Hubbub  Top 7 Cheeky Content Concepts for Laughter Lovers</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-t5-thievery-full-review-of-the-action-gem/"><u>[Updated] T5 Thievery - Full Review of the Action Gem</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-tactics-to-maximize-vimeo-viewership-for-2024/"><u>[Updated] Tactics to Maximize Vimeo Viewership for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gratitude-freepaid-outro-template-selections/"><u>2024 Approved  Gratitude  Free/Paid Outro Template Selections</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-optimal-method-for-integrating-gopro-footage-into-360-degree-films/"><u>2024 Approved  Optimal Method for Integrating GoPro Footage Into 360-Degree Films</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/acer-laptop-visual-capture-guide-screenshots-simplified/"><u>Acer Laptop Visual Capture Guide: Screenshots Simplified</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808135079-best-virtual-private-networks-for-google-chrome-quick-setup-steps-inside/"><u>Best Virtual Private Networks for Google Chrome - Quick Setup Steps Inside</u></a></li>
<li><a href="https://tech-hub.techidaily.com/between-bing-chat-and-chatgpt-what-freelancers-need-to-know-before-deciding-top-8-considerations/"><u>Between Bing Chat & ChatGPT: What Freelancers Need to Know Before Deciding (Top 8 Considerations)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/demystifying-vmware-improved-input-device-drivers-comprehensive-installation-steps-and-features-explained/"><u>Demystifying VMware Improved Input Device Drivers: Comprehensive Installation Steps & Features Explained</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808348085-disable-driver-signature-enforcement-on-windows-11-easily/"><u>Disable Driver Signature Enforcement on Windows 11 Easily</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-solutions-for-asus-trackpad-malfunctions-on-windows-1110-pcs/"><u>Effective Solutions for ASUS TrackPad Malfunctions on Windows 11/10 PCs</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effortless-methods-to-find-out-what-bios-version-youre-running-on-windows-11/"><u>Effortless Methods to Find Out What BIOS Version You're Running on Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808193530-enhanced-visibility-of-icons-and-graphical-user-interface-elements-making-navigation-more-intuitive-for-users-with-limited-vision/"><u>Enhanced Visibility of Icons and Graphical User Interface Elements, Making Navigation More Intuitive for Users with Limited Vision.</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expanding-ps4-storage-with-an-external-hdd-essential-tips-and-tricks/"><u>Expanding PS4 Storage with an External HDD - Essential Tips and Tricks</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/free-download-compatible-dell-bluetooth-software-and-drivers-for-windows-8/"><u>Free Download: Compatible Dell Bluetooth Software & Drivers for Windows 8</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/graphics-card-capability/"><u>Graphics Card Capability</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-to-retrieving-accidentally-overlooked-facebook-login-information/"><u>Guide to Retrieving Accidentally Overlooked Facebook Login Information</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-address-the-sudden-kernel-error-leading-to-bsods-on-your-windows-10-machine/"><u>How to Address the Sudden Kernel Error Leading to BSODs on Your Windows 10 Machine</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-allow-unverified-drivers-in-windows-pressure-a-simple-guide-for-windows-10-users/"><u>How to Allow Unverified Drivers in Windows Pressure: A Simple Guide for Windows 10 Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-download-epson-scanner-drivers-for-windows-11/"><u>How to Download Epson Scanner Drivers for Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-download-hp-drivers-for-windows-7/"><u>How to Download HP Drivers for Windows 7</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-enter-bios-on-windows-11-and-windows-7/"><u>How to Enter BIOS on Windows 11 & Windows 7?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-fix-a-non-detectable-external-hard-drive-on-windows-10-solutions-inside/"><u>How to Fix a Non-Detectable External Hard Drive on Windows 10 - Solutions Inside</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-get-ps4-out-of-safe-mode/"><u>How to Get PS4 Out of Safe Mode</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-install-inf-drivers-windows-1078xpvista/"><u>How to Install Inf Drivers (Windows 10/7/8/XP/Vista)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808164826-how-to-uninstall-windows-11-and-downgrade-to-windows-7-or-windows-81-quickly-and-easily/"><u>How to Uninstall Windows 11 and Downgrade to Windows 7 or Windows 8.1, Quickly and Easily</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-perfect-pitch-perfection-the-top-7-apps-to-change-your-voice-online/"><u>In 2024, Perfect Pitch Perfection  The Top 7 Apps to Change Your Voice Online</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-analysis-of-the-cyberpower-685avrg-ups-effective-and-efficient-protection-for-your-devices/"><u>In-Depth Analysis of the Cyberpower 685AVRG UPS: Effective and Efficient Protection for Your Devices</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/install-windows-11-from-usb-with-pictures/"><u>Install Windows 11 From USB (With Pictures)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/logitech-mouse-not-working-in-windows-11-solved/"><u>Logitech Mouse Not Working in Windows 11 [Solved]</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723807936474-mastering-pubg-mobile-a-comprehensive-walkthrough-for-players/"><u>Mastering PUBG Mobile: A Comprehensive Walkthrough for Players!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-voice-memos-app-on-windows-11-a-comprehensive-guide/"><u>Mastering the Voice Memos App on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-windows-10s-gpeditmsc-a-comprehensive-guide-in-5-steps-for-the-open-group-policy-editor/"><u>Navigating Windows 10'S gpedit.msc: A Comprehensive Guide in 5 Steps for the Open Group Policy Editor</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/seamless-slaying-with-higher-frames-and-lower-lag-expert-tips-for-genshin-impact-gamers-in-202n/"><u>Seamless Slaying with Higher Frames & Lower Lag - Expert Tips for Genshin Impact Gamers in 202N</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/simple-methods-for-checking-bios-version-on-windows-11-a-comprehensive-guide/"><u>Simple Methods for Checking BIOS Version on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/step-beyond-reality-reviewing-lgs-virtual-vision-for-2024/"><u>Step Beyond Reality  Reviewing LG's Virtual Vision for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-update-your-drivers-in-windows-1011/"><u>Step-by-Step Guide: Update Your Drivers in Windows 10/11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-solutions-for-when-your-logitech-c922-webcam-wont-connect-or-record/"><u>Step-by-Step Solutions for When Your Logitech C922 Webcam Won't Connect or Record</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-tutorial-effortlessly-identifying-the-refresh-rate-of-your-display-screen/"><u>Step-by-Step Tutorial: Effortlessly Identifying the Refresh Rate of Your Display Screen</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/stop-automatic-updates-on-your-windows-11-pc-with-these-easy-tricks/"><u>Stop Automatic Updates on Your Windows 11 PC with These Easy Tricks</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-video-editing-software-adobe-premiere-rush-alternatives-revealed/"><u>Top Video Editing Software Adobe Premiere Rush Alternatives Revealed</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-exodus-on-kodi-solutions-after-the-july-202-update/"><u>Troubleshooting Exodus on Kodi: Solutions After the July 202# Update</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/ultimate-ios-simulators-for-virtual-playstation-experience/"><u>Ultimate iOS Simulators for Virtual PlayStation Experience</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-troubleshooting-tips-for-connecting-your-logitech-kb/"><u>Ultimate Troubleshooting Tips for Connecting Your Logitech KB</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/what-is-hxtsrexe-in-windows-11-detailed-explanation-and-solutions-to-common-issues/"><u>What Is HxTsr.exe in Windows 11? Detailed Explanation and Solutions to Common Issues</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/windows-10-tablet-mode-everything-you-need-to-know/"><u>Windows 10 Tablet Mode: Everything You Need to Know</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808068092-windows-11-wont-boot-or-start-try-easy-fixes/"><u>Windows 11 Won't Boot or Start? Try Easy Fixes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/windows-intel-raid-recovery-fixing-a-malfunctioned-raid-controller/"><u>Windows Intel RAID Recovery: Fixing a Malfunctioned RAID Controller</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/wireless-and-wired-connection-procedures-for-integrating-a-laptop-with-a-printer/"><u>Wireless & Wired Connection Procedures for Integrating a Laptop With a Printer</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/wireless-playstation-3-controller-setup-for-windows-computers-without-motioninjoy/"><u>Wireless PlayStation 3 Controller Setup for Windows Computers - Without MotionINJoy</u></a></li>
</ul></div>
