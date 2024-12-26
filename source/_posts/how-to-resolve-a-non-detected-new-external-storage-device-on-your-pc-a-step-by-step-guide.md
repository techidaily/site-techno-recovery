---
title: How to Resolve a Non-Detected New External Storage Device on Your PC - A Step-by-Step Guide
date: 2024-12-20T04:42:48.081Z
updated: 2024-12-26T07:56:13.880Z
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

##  The Most Common Reason Your Disk Is Missing

 You grabbed a nice big hard disk on sale, you cracked open your computer case, plugged the drive into the motherboard and power supply with the appropriate cables (no? better double check that before you keep reading), and when you booted your computer back up the new hard drive was nowhere to be found.

 Or maybe you followed along with [our external hard drive tutorial](https://video-screen-grab.techidaily.com/new-diving-deep-into-minecraft-playback-secrets-from-the-pros/) and can't figure out why, even though you can hear the disk whirring away in the enclosure, you don't see the disk in Windows. What's the deal?

 Unlike the hard drive that ships with an off-the-shelf computer or external drive, extra hard drives you purchase aren't always shipped formatted and ready to use. Instead, they're in a totally blank state—the idea is that the end user will do what they wish with the drive, so there is no benefit to preformatting or otherwise changing the drive at the factory.

 As such, when you put the drive in your system, Windows simply waits for you to decide what to do with the drive instead of automatically formatting and adding it to the drive list. If you've never added a hard drive to your computer before, however, it can be pretty disconcerting when it appears like the drive is missing (or, worse, dead). Have no fear, though! It's easy to bring your hard drive out of hiding.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Bring Your Missing Drive Online

 Assuming that the hard drive is installed properly, and is not, (by some horrible dumb luck) defective out of the gate, bringing it online is a very simple process. To do so, you first need to pull up the Windows Disk Management tool.

 Press Windows+R on your keyboard to launch the Run dialog box. Type **diskmgmt.msc** into the box and press Enter.

![img_57c452aa264cd](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c452aa264cd.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Before we proceed, we want to appropriately warn you: Do not play around in Disk Management. Although the task we're about to perform is very straightforward and simple to do, if you muck around with this tool you will have a very bad time. Double check every step. Make sure you're selecting the correct disk, or you can lose lots of data.

 Disk Management will likely detect that you have a new drive and prompt you to initialize it. You should pick GPT if this option appears, then click "OK." 

![Select 'GPT (GUID Partition Table),' then click 'OK.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/1-hdd-auto-detected.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If it doesn't show up, you just need to initialize it manually. In Disk Management, scroll down through the list of disks in the bottom pane. These disks will be labeled "Disk 1" through however many disks you have. Windows assigns a number to all hard disks, solid state disks, USB drives, and card readers, so don't be surprised if you have to scroll down a bit—in our case the new drive was "Disk 10" as seen below.

![img_57c45698e20bd](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45698e20bd.png) 

 There are four bits of information here that indicate we're looking at the right disk. First, the disk is marked as "unknown" and "Not initialized" on the left, which a brand-new disk introduced to the system would be flagged as. Second, the drive size matches the size of the drive we just installed (around 1 TB), and the drive is flagged as unallocated, which means none of the hard drive space has been formatted or assigned a partition.

 Right click on the name portion of the disk entry, where it says "Disk \[#\]", and select "Initialize Disk" from the right-click context menu.

![img_57c457c7c1208](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c457c7c1208.png) 

 In the first step of the initilization process, you'll be prompted to choose whether you want to use a Master Boot Record (MBR) or a GUID Partition Table (GPT) for the partition style of your disk. If you want to do some in depth reading before making a choice, you can [check out our explainer here](https://instagram-videos.techidaily.com/2024-approved-exclusive-guide-ranking-most-effective-ig-money-makers/). In short, unless you have a pressing reason to use MBR, use GPT instead—it's newer, more efficient, and offers more robust protection against corruptions of the boot record.

![img_57c45b8a5fff8](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45b8a5fff8.png) 

 Click "OK" and you'll be returned to the main Disk Management window. There you'll find that your disk is now labeled "Basic" and "Online" on the left, but the contents are still "unallocated". Right click on the striped box presenting the unallocated drive space. Select "New Simple Volume".

![img_57c45c0ad925a](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45c0ad925a.png) 

 This will launch the New Simple Volume Wizard to guide you through the process of setting up the disk. In the first step, select how much space you want to include in the volume. By default the number is the full amount of available disk space--unless you're planning on reserving space for additional partitions, there's no reason to change this. Click "Next".

![img_57c45c8fc3c3e](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45c8fc3c3e.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the second step, assign a drive letter. The default is probably fine.

![img_57c45d02176de](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45d02176de.png) 

 Finally, format the volume. If you're using the volume for routine computing tasks (storing photos, video games, etc.) there's no real need to deviate from the default NTFS file system and settings. Curious about the differences between file systems and why you might use the different options? We've [got you covered](https://extra-approaches.techidaily.com/seamless-multi-screen-browsing-in-chrome-using-pip-for-2024/). Give your volume a name, click "Next", and wait for the format process to finish.

![img_57c45d3ae14d7](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/08/img_57c45d3ae14d7.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-lab.techidaily.com/ntegrate-youtube-content-into-google-slides-effectively/"><u>[New] Integrate YouTube Content Into Google Slides Effectively</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-an-experts-guide-to-accumulating-mass-tiktok-videos-effortlessly-for-2024/"><u>[Updated] An Expert's Guide to Accumulating Mass TikTok Videos Effortlessly for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-radial-magic-transforming-ordinary-photos-into-art/"><u>[Updated] Radial Magic Transforming Ordinary Photos Into Art</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/best-flashlights-you-need-professional-advice-and-choices-gadget-guide-zdnet/"><u>Best Flashlights You Need : Professional Advice and Choices | Gadget Guide, ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/cost-effective-power-solutions-for-adventurers-the-top-rated-economical-station-reviewed-by-zdnet/"><u>Cost-Effective Power Solutions for Adventurers: The Top Rated, Economical Station Reviewed by ZDNET</u></a></li>
<li><a href="https://program-issues.techidaily.com/debunking-rumors-diablo-immortals-upcoming-arrival-on-pc-platforms/"><u>Debunking Rumors: Diablo Immortal's Upcoming Arrival on PC Platforms</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-the-latest-tools-to-spot-chatgpt-in-your-classroom-or-workplace/"><u>Discover the Latest Tools to Spot ChatGPT in Your Classroom or Workplace</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/grok-ventures-secures-majority-ownership-in-agl-by-acquiring-11-share-thwarting-de-merge-strategy/"><u>Grok Ventures Secures Majority Ownership in AGL by Acquiring 11% Share, Thwarting De-Merge Strategy</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>In 2024, Will iSpoofer update On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/must-haves-buying-a-refurbished-laptop-guide/"><u>Must Haves: Buying a Refurbished Laptop Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-prime-day-deals-securing-the-budget-friendly-smart-plug-for-just-349-tech-insights-with-zdnet/"><u>Navigating Prime Day Deals: Securing the Budget-Friendly Smart Plug for Just $3.49 | Tech Insights with ZDNet</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-the-uses-of-chatgpt-as-a-student-what-to-watch-out-for/"><u>Navigating the Uses of ChatGPT as a Student: What to Watch Out For</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-issue-reactivating-your-devices-disabled-wi-fi-feature/"><u>Resolving the Issue: Reactivating Your Device's Disabled Wi-Fi Feature</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/tired-of-teslas-powerwall-explore-an-alternative-with-ankers-solix-x1-battery-pack-zdnet/"><u>Tired of Tesla's Powerwall? Explore an Alternative with Anker's Solix X1 Battery Pack - ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-rated-portable-solar-power-banks-expert-reviews-and-comparisons/"><u>Top Rated Portable Solar Power Banks - Expert Reviews & Comparisons</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-rated-high-intensity-led-torches-professional-picks-techradar/"><u>Top-Rated High-Intensity LED Torches : Professional Picks | TechRadar</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-rated-led-flashlight-picks-comprehensive-reviews-by-tech-experts-zdnet/"><u>Top-Rated LED Flashlight Picks - Comprehensive Reviews by Tech Experts | ZDNet</u></a></li>
</ul></div>

