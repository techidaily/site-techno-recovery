---
title: "Easy Instructions: How to Refresh the Vocabulary Tools on Your Amazon Kindle Fire Device"
date: 2024-08-20T09:53:26.555Z
updated: 2024-08-21T09:53:26.555Z
categories:
  - epubor
thumbnail: https://thmb.techidaily.com/d308f7cbef44fc72492251644b94fc820af3415416f540b09fcf25e37cb1c7dd.jpg
---

## Easy Instructions: How to Refresh the Vocabulary Tools on Your Amazon Kindle Fire Device

## How to Replace Kindle Fire Dictionary

Posted by [Jonny Greenwood](https://plus.google.com/u/0/+JonnyGreenwood999) on 11/30/2018 10:26:27 AM.

4.5 [(6 comments)](http://www.epubor.com/#comment-area) 



![follow](http://www.epubor.com/images/follow.png)

Kindle Fire is not only a great e-book reader but also a good tool for learning English. By tapping any words in the book, we can easily learn its detailed meaning and related expression. But it's a bit pity that you can't switch from one dictionary to another when looking up a word which you can do on Kindle and Kindle Paperwhite. This is because the Kindle Fire has only one dictionary by default and it has no options for you to add or change any dictionaries. Although the built-in New Oxford American Dictionary is enough for some degrees, some people want to use a more professional or specialized dictionary, especially those who want to learn a foreign language like Chinese, but not English. So we need to replace Kindle Fire dictionary.

As we mentioned above, Amazon doesn't want us to change the Kindle Fire default dictionary. So we need some hackings to modify the system files. Yes, you may have realized it – You need root your Kindle Fire. If you haven't rooted your device, check out these two rooting tutorials:

1\. [How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

2\. [Root Kindle Fire with one click](http://ebookconverter.blogspot.com/2013/07/root-kindle-fire-with-one-click.html)

PS: Our tutorial can only replace the default dictionary as Kindle Fire only supports one dictionary. You can't choose an alternative dictionary.

1 Get your dictionaries 

We can purchase dictionaries from Amazon Kindle Store. But most of them are paid ones. Actually there are many free dictionaries on the Internet. Download a dictionary with a suffix "**mobi**" or "**prc**". Rename it as "**B003ODIZL6**" and change its file extension to "**prc**". Then transfer the dictionary to your Kindle Fire. Here I choose the **Oxford English-Chinese Dictionary** for example. 

2 Modify system file 

Reboot your Kindle Fire and then open ES File Explorer. Find the new dictionary file you get in step1 and long tap to copy it. 

![copy-dictionary-file](https://www.epubor.com/images/uppic/1-copy-dictionary-file.jpg)

Then navigate to this path: **/system/etc/labdictionary**. You can find two files here: B003ODIZL6.prc and Kindle\_User\_Guide.prc. Tap the Fast Access icon and choose "**Tools**" – "**Root Explorer**" – "**Mount R/W**" and set all the paths to "**RW**" permission. Then rename the "**B003ODIZL6.prc**" as "**B003ODIZL6.prc.bak**".

![find-default-dictionary](https://www.epubor.com/images/uppic/2-find-default-dictionary.jpg)

![modify-system-permission](https://www.epubor.com/images/uppic/3-modify-system-permission.jpg)

![rename-default-dicionary-file](https://www.epubor.com/images/uppic/4-rename-default-dicionary-file.jpg)

Tap the Clipboard icon and choose "Paste". Long tap the new "B003ODIZL6.prc" file and choose "**More**" – "**Properties**" – "**Permissions**: **Change**". Set the permissions like this and click "OK" to confirm.

![paste-new-dictionary-here](https://www.epubor.com/images/uppic/5-paste-new-dictionary-here.jpg)

![change-permission](https://www.epubor.com/images/uppic/6-change-permission.jpg)

3 Test new dictionary 

Now open an e-book and tap any words, you can find its explaining has changed into Chinese, that means the new dictionary works! 

![replace-kindle-fire-dictionary](https://www.epubor.com/images/uppic/7-new-dictionary-works.jpg)

If you want to change back to the default dictionary, just delete the "B003ODIZL6.prc" at the directory: **/system/etc/labdictionary** and rename the "B003ODIZL6.prc.bak" as "B003ODIZL6.prc". Then reboot the Kindle Fire and you can find the Oxford dictionary comes back.

![author](https://www.epubor.com/images/uppic/jonny.png)

[Jonny Greenwood](https://plus.google.com/u/0/+JonnyGreenwood999) joined Epubor since 2011, loves everything about eBooks and eReaders. He seeks the methods to read eBooks more freely and wants to share all he has got with you.

SHARING IS GREAT!

[Tweet](https://twitter.com/share) 

[SAVE PAGE AS PDF](https://tools.techidaily.com/epubor/products/) 



6 Comments

[reply](https://tools.techidaily.com/epubor/products/) 

[reply](https://tools.techidaily.com/epubor/products/) 

Kt

[Re:How to replace Kindle Fire dictionary](https://tools.techidaily.com/epubor/products/)

11/24/2013 16:24:46

I rooted the device and changed the dictionary but at the end of step 2 you say to change the file properties to this: and then there is no photo explaining. when i try to use the dictionary it is blank and i don't know if it's because of the file properties or because of the dictionary file itself. please write the properties or take a picture :) thank you

[reply](https://tools.techidaily.com/epubor/products/) 

jose luis

[Re:How to replace Kindle Fire dictionary](https://tools.techidaily.com/epubor/products/)

02/28/2014 22:15:34

hi, thanks for your tutorial, but i have a problem, i do it evething like images and change the dictionary but when i boot it eraseand no appears any definition, like no dictionary

 "Properties" – "Permissions: Change". Set the permissions like this which one exactly are the options we have to put

 thank you again for the tutorial really helps alot!!!

[reply](https://tools.techidaily.com/epubor/products/) 

Alex

[Re:How to replace Kindle Fire dictionary](https://tools.techidaily.com/epubor/products/)

07/11/2014 14:06:07

Thanks for tutorial it helped a lot.  
 P.S  
 I have set the new dictionary's permissions similar to old one's and it worked for me.  
 you should check "read" for 'owner', 'group' and 'other', and you should check "write" for 'owner'.  
 everything besides these options should be unchecked.   
 If you didn't understand what i wrote, you can simply check for the permissions for old dictionary  
 and copy them to new dictionary's permissions.  
 Hope it helped, sorry for bad english

[reply](https://tools.techidaily.com/epubor/products/) 

William Sanderson

[Re:How to Replace Kindle Fire Dictionary](https://tools.techidaily.com/epubor/products/)

02/5/2015 01:20:10

An amazing tutorial. I have followed all the steps with no problem.

 All went well until I arrived at /system/etc/labdictionary section. The two files mentioned do not exist! The only items there were dcp.dat, dcp.db and ODE\_KCP.mobi. None the less I pasted my "new" dictionary into the folder and reset the permissions. But with no effect. It does not recognise my new dictionary. Should this "new" dictionary be placed in an alternative directory?

 Any assistance you can give will be of a great help  
 For your information I own a Kindle Fire HD 7  
 Kindest regards

 Wm Sanderson 

[reply](https://tools.techidaily.com/epubor/products/) 

George

[Re:How to Replace Kindle Fire Dictionary](https://tools.techidaily.com/epubor/products/)

03/21/2015 09:07:34

I followed this to the end and now no dictionaries work! Help!

[reply](https://tools.techidaily.com/epubor/products/) 

lanfeng

[Re:How to Replace Kindle Fire Dictionary](https://tools.techidaily.com/epubor/products/)

03/25/2015 01:37:09

my kindle fire is 1st,I followed this to the end and now no dictionaries work! Help!

[reply](https://tools.techidaily.com/epubor/products/) 

Leave a comment

| Rating |  |
| ------ |  |

| YourName | \*  1 to 50 chars |
| -------- | ----------------- |

| email | Internet Email |
| ----- | -------------- |

| Comments | UBB Editor |
| -------- | ---------- |

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-top-money-making-techniques-for-short-videos/"><u>[New] 2024 Approved  Top Money-Making Techniques for Short Videos</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-bridging-the-gap-audio-to-text-in-powerpoint-slides/"><u>[New] Bridging the Gap  Audio to Text in PowerPoint Slides</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-navigating-melody-rights-on-instagram-a-full-breakdown-for-2024/"><u>[New] Navigating Melody Rights on Instagram  A Full Breakdown for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solved-how-to-install-epson-printer-step-by-step/"><u>[Solved] How To Install Epson Printer Step-by-Step</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-enhancing-outdoor-vision-with-gopro-and-live-streaming-platforms/"><u>[Updated] 2024 Approved  Enhancing Outdoor Vision with GoPro and Live Streaming Platforms</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-how-can-i-stream-in-hd-1080p-on-facebook/"><u>[Updated] 2024 Approved  How Can I Stream in HD 1080P on Facebook?</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-advanced-ai-for-professional-photography/"><u>[Updated] In 2024, Advanced AI for Professional Photography</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/acer-laptop-visual-capture-guide-screenshots-simplified/"><u>Acer Laptop Visual Capture Guide: Screenshots Simplified</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808135079-best-virtual-private-networks-for-google-chrome-quick-setup-steps-inside/"><u>Best Virtual Private Networks for Google Chrome - Quick Setup Steps Inside</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/demystifying-vmware-improved-input-device-drivers-comprehensive-installation-steps-and-features-explained/"><u>Demystifying VMware Improved Input Device Drivers: Comprehensive Installation Steps & Features Explained</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808348085-disable-driver-signature-enforcement-on-windows-11-easily/"><u>Disable Driver Signature Enforcement on Windows 11 Easily</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-solutions-for-asus-trackpad-malfunctions-on-windows-1110-pcs/"><u>Effective Solutions for ASUS TrackPad Malfunctions on Windows 11/10 PCs</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effortless-methods-to-find-out-what-bios-version-youre-running-on-windows-11/"><u>Effortless Methods to Find Out What BIOS Version You're Running on Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808193530-enhanced-visibility-of-icons-and-graphical-user-interface-elements-making-navigation-more-intuitive-for-users-with-limited-vision/"><u>Enhanced Visibility of Icons and Graphical User Interface Elements, Making Navigation More Intuitive for Users with Limited Vision.</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expanding-ps4-storage-with-an-external-hdd-essential-tips-and-tricks/"><u>Expanding PS4 Storage with an External HDD - Essential Tips and Tricks</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/free-download-compatible-dell-bluetooth-software-and-drivers-for-windows-8/"><u>Free Download: Compatible Dell Bluetooth Software & Drivers for Windows 8</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/graphics-card-capability/"><u>Graphics Card Capability</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-to-retrieving-accidentally-overlooked-facebook-login-information/"><u>Guide to Retrieving Accidentally Overlooked Facebook Login Information</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-allow-unverified-drivers-in-windows-pressure-a-simple-guide-for-windows-10-users/"><u>How to Allow Unverified Drivers in Windows Pressure: A Simple Guide for Windows 10 Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-download-epson-scanner-drivers-for-windows-11/"><u>How to Download Epson Scanner Drivers for Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-factory-reset-acer-laptop-step-by-step/"><u>How to Factory Reset Acer Laptop - Step by Step</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-format-sd-card-on-windows-1087xp-solved/"><u>How to Format SD Card on Windows 10/8/7/XP [Solved]</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-get-windows-10-updates-faster-effective-strategies-inside/"><u>How to Get Windows 10 Updates Faster - Effective Strategies Inside</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-integrate-a-computer-printer-with-windows-11-a-comprehensive-guide/"><u>How to Integrate a Computer Printer with Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-link-two-displays-with-a-single-laptop-unit/"><u>How to Link Two Displays with a Single Laptop Unit</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-seamlessly-change-pictures-into-fun-animated-gif-files/"><u>How To Seamlessly Change Pictures Into Fun Animated GIF Files</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808164826-how-to-uninstall-windows-11-and-downgrade-to-windows-7-or-windows-81-quickly-and-easily/"><u>How to Uninstall Windows 11 and Downgrade to Windows 7 or Windows 8.1, Quickly and Easily</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/humor-hacks-simplifying-the-process-of-meme-creation-for-2024/"><u>Humor Hacks  Simplifying the Process of Meme Creation for 2024</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-complete-tutorial-sending-photos-from-apple-iphone-15-to-ipad-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Complete Tutorial Sending Photos From Apple iPhone 15 to iPad | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-mastering-remote-conferences-with-5-elite-recorders/"><u>In 2024, Mastering Remote Conferences with 5 Elite Recorders</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/legally-spying-on-mobile-phones-your-step-by-step-guide/"><u>Legally Spying on Mobile Phones - Your Step-by-Step Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-kodi-streaming-a-complete-resource-for-all-your-questions-answered/"><u>Mastering Kodi Streaming: A Complete Resource for All Your Questions Answered</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723807936474-mastering-pubg-mobile-a-comprehensive-walkthrough-for-players/"><u>Mastering PUBG Mobile: A Comprehensive Walkthrough for Players!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-solo-adventures-a-players-guide-to-steam-offline-mode/"><u>Mastering Solo Adventures: A Player's Guide to Steam Offline Mode</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-stealth-mode-tips-for-secret-internet-exploration/"><u>Mastering Stealth Mode: Tips for Secret Internet Exploration</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-the-ultimate-list-10-free-online-video-compressors-without-downloads/"><u>New The Ultimate List 10 Free Online Video Compressors Without Downloads</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/pc-survival-tactics-a-beginners-handbook-to-jump-into-fortnite-action/"><u>PC Survival Tactics: A Beginner’s Handbook to Jump Into Fortnite Action!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/quick-and-easy-guide-mastering-the-clean-installation-of-windows-11-in-no-time/"><u>Quick & Easy Guide: Mastering the Clean Installation of Windows 11 in No Time</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/revive-your-pcs-speakers-a-complete-tutorial-to-reinstall-realtek-hd-audio-driver-in-windows-11/"><u>Revive Your PC's Speakers: A Complete Tutorial to Reinstall Realtek HD Audio Driver in Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/seamless-ad-blocking-in-firefox-unlock-a-cleaner-faster-web-experience-today/"><u>Seamless Ad Blocking in Firefox: Unlock a Cleaner, Faster Web Experience Today</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-successfully-uninstalling-a-printer-from-your-windows-pc/"><u>Step-by-Step Guide: Successfully Uninstalling a Printer From Your Windows PC</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-updating-drivers-in-windows-11/"><u>Step-by-Step Guide: Updating Drivers in Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-instructions-for-installing-a-racing-steering-wheel-into-your-computer-setup/"><u>Step-by-Step Instructions for Installing a Racing Steering Wheel Into Your Computer Setup</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-hub-your-ultimate-guide-to-cutting-edge-hardware/"><u>Tom's Tech Hub: Your Ultimate Guide to Cutting-Edge Hardware</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/what-is-hxtsrexe-in-windows-11-detailed-explanation-and-solutions-to-common-issues/"><u>What Is HxTsr.exe in Windows 11? Detailed Explanation and Solutions to Common Issues</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/windows-10-tablet-mode-everything-you-need-to-know/"><u>Windows 10 Tablet Mode: Everything You Need to Know</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808068092-windows-11-wont-boot-or-start-try-easy-fixes/"><u>Windows 11 Won't Boot or Start? Try Easy Fixes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/windows-intel-raid-recovery-fixing-a-malfunctioned-raid-controller/"><u>Windows Intel RAID Recovery: Fixing a Malfunctioned RAID Controller</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/wireless-and-wired-connection-procedures-for-integrating-a-laptop-with-a-printer/"><u>Wireless & Wired Connection Procedures for Integrating a Laptop With a Printer</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/wireless-playstation-3-controller-setup-for-windows-computers-without-motioninjoy/"><u>Wireless PlayStation 3 Controller Setup for Windows Computers - Without MotionINJoy</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->