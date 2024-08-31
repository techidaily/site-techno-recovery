---
title: How to Resolve a Non-Detected New External Storage Device on Your PC - A Step-by-Step Guide
date: 2024-08-30T13:09:08.763Z
updated: 2024-08-31T13:09:08.763Z
tags:
  - deals
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/52974816639_7b4544fc8a_o-1.jpg
---

## How to Resolve a Non-Detected New External Storage Device on Your PC - A Step-by-Step Guide

### Quick Links

* [The Most Common Reason Your Disk Is Missing](https://fox-links.techidaily.com/new-2024-approved-essential-steps-to-prep-your-oculus-rift-zone/)
* [How to Bring Your Missing Drive Online](https://apple-account.techidaily.com/in-2024-your-account-has-been-disabled-in-the-app-store-and-itunes-from-iphone-13-by-drfone-ios/)

### Key Takeaways

* Hard drives you purchase aren't usually preformatted, so Windows waits for you to decide what to do with the drive.
* Open the Disk Management tool, identify your new (unformatted) drive, then right-click it and select "Initialize."
* After you initialize the drive, you must format it before you can store anything on it. Use NTFS if the drive will only be used in a Windows PC.

 You installed a new hard drive in your computer and, to your dismay, it's nowhere to be found. Don't panic, you just need to give Windows a little nudge to bring it online.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
##  The Most Common Reason Your Disk Is Missing

 You grabbed a nice big hard disk on sale, you cracked open your computer case, plugged the drive into the motherboard and power supply with the appropriate cables (no? better double check that before you keep reading), and when you booted your computer back up the new hard drive was nowhere to be found.

 Or maybe you followed along with [our external hard drive tutorial](https://video-screen-grab.techidaily.com/new-diving-deep-into-minecraft-playback-secrets-from-the-pros/) and can't figure out why, even though you can hear the disk whirring away in the enclosure, you don't see the disk in Windows. What's the deal?

 Unlike the hard drive that ships with an off-the-shelf computer or external drive, extra hard drives you purchase aren't always shipped formatted and ready to use. Instead, they're in a totally blank state—the idea is that the end user will do what they wish with the drive, so there is no benefit to preformatting or otherwise changing the drive at the factory.

 As such, when you put the drive in your system, Windows simply waits for you to decide what to do with the drive instead of automatically formatting and adding it to the drive list. If you've never added a hard drive to your computer before, however, it can be pretty disconcerting when it appears like the drive is missing (or, worse, dead). Have no fear, though! It's easy to bring your hard drive out of hiding.

##  How to Bring Your Missing Drive Online

 Assuming that the hard drive is installed properly, and is not, (by some horrible dumb luck) defective out of the gate, bringing it online is a very simple process. To do so, you first need to pull up the Windows Disk Management tool.

 Press Windows+R on your keyboard to launch the Run dialog box. Type **diskmgmt.msc** into the box and press Enter.

![img_57c452aa264cd](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c452aa264cd.png) 

 Before we proceed, we want to appropriately warn you: Do not play around in Disk Management. Although the task we're about to perform is very straightforward and simple to do, if you muck around with this tool you will have a very bad time. Double check every step. Make sure you're selecting the correct disk, or you can lose lots of data.

 Disk Management will likely detect that you have a new drive and prompt you to initialize it. You should pick GPT if this option appears, then click "OK." 

![Select 'GPT (GUID Partition Table),' then click 'OK.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/1-hdd-auto-detected.png) 

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If it doesn't show up, you just need to initialize it manually. In Disk Management, scroll down through the list of disks in the bottom pane. These disks will be labeled "Disk 1" through however many disks you have. Windows assigns a number to all hard disks, solid state disks, USB drives, and card readers, so don't be surprised if you have to scroll down a bit—in our case the new drive was "Disk 10" as seen below.

![img_57c45698e20bd](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45698e20bd.png) 

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 There are four bits of information here that indicate we're looking at the right disk. First, the disk is marked as "unknown" and "Not initialized" on the left, which a brand-new disk introduced to the system would be flagged as. Second, the drive size matches the size of the drive we just installed (around 1 TB), and the drive is flagged as unallocated, which means none of the hard drive space has been formatted or assigned a partition.

 Right click on the name portion of the disk entry, where it says "Disk \[#\]", and select "Initialize Disk" from the right-click context menu.

![img_57c457c7c1208](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c457c7c1208.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 In the first step of the initilization process, you'll be prompted to choose whether you want to use a Master Boot Record (MBR) or a GUID Partition Table (GPT) for the partition style of your disk. If you want to do some in depth reading before making a choice, you can [check out our explainer here](https://instagram-videos.techidaily.com/2024-approved-exclusive-guide-ranking-most-effective-ig-money-makers/). In short, unless you have a pressing reason to use MBR, use GPT instead—it's newer, more efficient, and offers more robust protection against corruptions of the boot record.

![img_57c45b8a5fff8](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45b8a5fff8.png) 

 Click "OK" and you'll be returned to the main Disk Management window. There you'll find that your disk is now labeled "Basic" and "Online" on the left, but the contents are still "unallocated". Right click on the striped box presenting the unallocated drive space. Select "New Simple Volume".

![img_57c45c0ad925a](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45c0ad925a.png) 

 This will launch the New Simple Volume Wizard to guide you through the process of setting up the disk. In the first step, select how much space you want to include in the volume. By default the number is the full amount of available disk space--unless you're planning on reserving space for additional partitions, there's no reason to change this. Click "Next".

![img_57c45c8fc3c3e](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45c8fc3c3e.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
 In the second step, assign a drive letter. The default is probably fine.

![img_57c45d02176de](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45d02176de.png) 

 Finally, format the volume. If you're using the volume for routine computing tasks (storing photos, video games, etc.) there's no real need to deviate from the default NTFS file system and settings. Curious about the differences between file systems and why you might use the different options? We've [got you covered](https://extra-approaches.techidaily.com/seamless-multi-screen-browsing-in-chrome-using-pip-for-2024/). Give your volume a name, click "Next", and wait for the format process to finish.

![img_57c45d3ae14d7](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45d3ae14d7.png) 

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When the process is complete, you'll see your new drive--allocated, formatted, and ready for action--in the Disk Management disk list.

![img_57c45e2278bff](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45e2278bff.png) 

 You can now use the disk like any other on your system for media storage, games, and other purposes.

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
<li><a href="https://techno-recovery.techidaily.com/12-must-try-gratis-typing-tutorials-that-cater-to-people-young-and-old/"><u>12 Must-Try Gratis Typing Tutorials That Cater to People Young and Old</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/add-the-numerator-1-to-the-result-to-get-a-new-numerator-of-7/"><u>Add the Numerator 1 to the Result to Get a New Numerator of 7</u></a></li>
<li><a href="https://extra-resources.techidaily.com/chip-efficiency-exposed-unleashing-top-notch-editing-performance/"><u>Chip Efficiency Exposed  Unleashing Top-Notch Editing Performance</u></a></li>
<li><a href="https://apple-account.techidaily.com/choosing-your-next-smartphone-iphone-vs-samsung-a-comprehensive-guide/"><u>Choosing Your Next Smartphone: IPhone Vs. Samsung - A Comprehensive Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comparing-signal-and-whatsapp-key-features-that-set-them-apart/"><u>Comparing Signal and WhatsApp: Key Features That Set Them Apart</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/complete-guide-restoring-lost-or-deleted-messages-on-your-gmail-account/"><u>Complete Guide: Restoring Lost or Deleted Messages on Your Gmail Account</u></a></li>
<li><a href="https://win-blog.techidaily.com/destiny-2-pc-version-error-resolved-now-running-smoothly/"><u>Destiny 2 PC Version Error Resolved - Now Running Smoothly</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effortless-ways-to-correct-magic-mouse-movement-errors/"><u>Effortless Ways to Correct Magic Mouse Movement Errors</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/eliminating-msvbvm50dll-errors-a-detailed-guide-to-restoring-your-systems-stability/"><u>Eliminating MSVBVM50.DLL Errors: A Detailed Guide to Restoring Your System's Stability</u></a></li>
<li><a href="https://media-tips.techidaily.com/get-more-bang-for-your-buck-with-these-5-tips-for-effective-peacock-care/"><u>Get More Bang for Your Buck with These 5 Tips for Effective Peacock Care</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-activation-lock-on-apple-iphone-12-pro-or-ipad-by-drfone-ios/"><u>How to Bypass Activation Lock on Apple iPhone 12 Pro or iPad?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-diagnose-and-repair-ntdlldll-glitches-on-windows-10-8-7-etc/"><u>How to Diagnose and Repair ntdll.dll Glitches on Windows 10, 8, 7, Etc.</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-free-up-space-by-removing-cache-on-your-android-device/"><u>How to Free Up Space by Removing Cache on Your Android Device</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-getting-fcp-on-the-house-simple-steps/"><u>In 2024, Getting FCP on the House - Simple Steps</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-do-you-unlock-your-iphone-14-pro-learn-all-4-methods-by-drfone-ios/"><u>In 2024, How Do You Unlock your iPhone 14 Pro? Learn All 4 Methods</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/macos-15-sequoia-detailed-overview-of-release-plans-enhancements-and-rumors/"><u>MacOS 15 (Sequoia) – Detailed Overview of Release Plans, Enhancements, and Rumors</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-top-10-free-online-tools-for-creating-stunning-glitch-effects-for-2024/"><u>New Top 10 Free Online Tools for Creating Stunning Glitch Effects for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/professional-grade-handguns-for-ultimate-video-stability/"><u>Professional Grade Handguns for Ultimate Video Stability</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/removing-gadgets-comprehensive-tips-on-disconnecting-from-google-home/"><u>Removing Gadgets: Comprehensive Tips on Disconnecting From Google Home</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/setting-up-two-step-verification-in-gmail-a-step-by-step-guide/"><u>Setting Up Two-Step Verification in Gmail: A Step-by-Step Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solve-your-amazon-prime-caption-problems-easily-and-effectively/"><u>Solve Your Amazon Prime Caption Problems Easily and Effectively</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-fixes-for-the-common-haldll-error-in-windows-versions/"><u>Step-by-Step Fixes for the Common hal.dll Error in Windows Versions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-linking-your-laptop-and-tv-using-an-hdmi-cable/"><u>Step-by-Step Guide: Linking Your Laptop and TV Using an HDMI Cable</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/time-adjustment-for-amazon-kindle-paperwhite-instructions-and-tips/"><u>Time Adjustment for Amazon Kindle Paperwhite - Instructions & Tips</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/trade-shows-and-events/"><u>Trade Shows & Events</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-steps-what-to-do-if-alexa-indicates-your-echo-device-is-not-connected/"><u>Troubleshooting Steps: What to Do If Alexa Indicates Your Echo Device Is Not Connected</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/twitter-jokes-unveiled-3-pc-based-methods-for-2024/"><u>Twitter Jokes Unveiled  3 PC-Based Methods for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/uber-vs-taxi-a-cost-comparison-analysis/"><u>Uber Vs. Taxi: A Cost Comparison Analysis</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-the-503-service-unavailable-error-causes-solutions-and-prevention/"><u>Understanding the 503 Service Unavailable Error – Causes, Solutions & Prevention</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unraveling-device-confusion-identifying-key-differences-between-ipads-and-general-tablets/"><u>Unraveling Device Confusion: Identifying Key Differences Between iPads and General Tablets</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unraveling-the-history-of-netflixs-original-dvd-service/"><u>Unraveling the History of Netflix's Original DVD Service</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/upcoming-google-pixel-10-unveiling-the-latest-rumors-on-release-dates-pricing-and-specifications/"><u>Upcoming Google Pixel 10: Unveiling the Latest Rumors on Release Dates, Pricing & Specifications</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/water-resistance-levels-of-the-new-iphone-15-pro-max-explained/"><u>Water Resistance Levels of the New iPhone 15 Pro Max Explained</u></a></li>
</ul></div>
