---
title: A Comprehensive Guide to the Windows 11 Battery Report Functionality
date: 2024-10-12T22:37:17.136Z
updated: 2024-10-19T11:28:52.174Z
categories:
  - BestProducts
description: This Article Describes A Comprehensive Guide to the Windows 11 Battery Report Functionality
excerpt: This Article Describes A Comprehensive Guide to the Windows 11 Battery Report Functionality
thumbnail: https://www.lifewire.com/thmb/-ErWVirK-Kvqz_jdp6xfavPKXKY=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/panos-sakalakis-35NiG1dYjtM-unsplash-04ea0b8a952a4f028ff0c0f0dfd0ade8.jpg
---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## A Comprehensive Guide to the Windows 11 Battery Report Functionality
### What to Know

* To generate a report, press**Win** +**X** and select**Windows PowerShell (Admin)** \>**Yes** .
* Enter **powercfg /batteryreport /output "C:\\battery-report.html"** into PowerShell and press**Enter** .
* Open the exported file from the C drive to view the battery report.

 This article explains how to generate a Windows 10 battery report. The report includes information about the general health of the battery, usage history, battery life estimates, and other statistics.  

## How to Generate a Battery Report in Windows 10

 The battery on your laptop or tablet is one of its most critical pieces of[hardware](https://www.lifewire.com/computer-hardware-2625895) . Over time, a battery's life span shortens, and its ability to hold a charge decreases. If you suspect your battery's performance is fading, follow these steps to create a battery report:  

1. Press**Win** +**X** , then select**Windows PowerShell (Admin)** . Select**Yes** when the User Account Control box appears.  
![powershell](https://www.lifewire.com/thmb/jZNRO0ZChIXAj44Hj-Qk_Gv3c2E=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001-windows-10-battery-report-what-it-is-and-how-to-use-it-eb97a723495643429ee5af383ef33e35.jpg)
2. Enter this command into PowerShell, then press**Enter** :  
 `powercfg /batteryreport /output "C:\battery-report.html"`  
 Feel free to change the path (in quotes) to wherever you want to save the report. In our example, it will be exported to the[C drive](https://www.lifewire.com/what-is-a-c-drive-5222296) .
3. After you run the battery report command, you'll see a message indicating where the file was saved. Take note of the location.  
![battery life location](https://www.lifewire.com/thmb/eA3ZUvDsKSVHVe95zCIVzRKJvu4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002-windows-10-battery-report-what-it-is-and-how-to-use-it-fe885b3ec48e4d81bb081e819a2a972b.jpg)
4. Use Windows Explorer to find the file, then double-click or double-tap it to open the report in your web browser. In our example, since the battery report was saved in the[root](https://www.lifewire.com/what-is-a-root-folder-or-root-directory-2625989) of the C drive, we can type this into the browser's URL bar to open the report:  
 `file:///C:/battery-report.html`

[How to Get Your Windows 11 Battery Report](https://www.lifewire.com/generate-windows-11-battery-report-5209527)

## How to Read the Battery Report in Windows 10

 With the battery report generated and open, let's walk through each section to learn more about the battery's performance and estimated life expectancy.

 The first section, directly under**Battery report** , lists some primary system information such as your computer's name, BIOS version, OS build, and the date the report was created.

 The second section, below**Installed batteries** , lists key information about your laptop or tablet batteries, such as name, manufacturer, serial number, chemistry, and design capacity.

![A screenshot of the first two sections of a Windows 10 battery report.](https://www.lifewire.com/thmb/cdMl7F4TRFo-BwaNKuCqdGgWKko=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-6-5c74f03546e0fb0001a9825a.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151869/7443" target="_top" id="2151869">
  <img src="//a.impactradius-go.com/display-ad/7443-2151869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Recent Usage

 This section overviews when your device was running on battery or connected to AC power. Recent usage covers power states for three days and includes start time, state (active/suspended), source (battery/AC), and remaining capacity.

![A screenshot displaying recent usage on a Windows 10 battery report.](https://www.lifewire.com/thmb/gPFUNNrcOy5j_YDxwEdimde27d8=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-7-5c74fa37c9e77c0001e98d2b.jpg)

### Battery Usage

 This area lists any battery drains over the last three days. If your system ran for extended periods on battery alone, this section would break it down by start time or duration, as well as by energy drained.

[How to Make a Laptop Battery Last Longer](https://www.lifewire.com/make-laptop-battery-last-longer-5189983)

![A screenshot showing battery usage in a Windows 10 battery report.](https://www.lifewire.com/thmb/CcY183o8jUDRbhUehMCZBEedeo8=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-8-5c750187c9e77c000136a5f0.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137205/26400" target="_top" id="2137205">
  <img src="//a.impactradius-go.com/display-ad/26400-2137205" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137205/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Usage History

 Here, you'll see a complete history (including duration) of each time your device was running on battery or AC power. Reviewing your usage history is a great way to see how often and for how long you run your device on battery power.

![A screenshot showing battery and AC power usage in a Windows 10 battery report.](https://www.lifewire.com/thmb/mZEneBChOagqSVGktFCzwFEe-3U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-9-5c758254c9e77c0001e98d44.jpg)

### Battery Capacity History

 In this section of the report, you see the full charge capacity compared to your battery's design capacity for each period. Watching your full charge capacity is another helpful way to monitor the overall health and performance of your battery over time.

![A screenshot of the battery capacity history section of a Windows 10 battery report.](https://www.lifewire.com/thmb/6KUTn767xRch_BQSEj3JHzuI2fg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-10-5c75a643c9e77c00012f80ea.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100529/7443" target="_top" id="2100529">
  <img src="//a.impactradius-go.com/display-ad/7443-2100529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Battery Life Estimates

 The final section of the report displays battery life estimates at full charge, compared to the designed capacity. This gives you a clear outlook of how well your battery's life is holding up over time. At the very bottom of the report is an estimated battery lifetime value based on observed drains since the last OS installation.

![A screenshot showing battery life estimates on a Windows 10 laptop.](https://www.lifewire.com/thmb/GpXKBVh8c6oG-fA3KQUHuCXgksc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-11-5c76609b46e0fb0001a5ef6e.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[How Long Does a Laptop Battery Last?](https://www.lifewire.com/how-long-does-a-laptop-battery-last-5186206)

 FAQ

* Where does Windows save my battery report to?  
 Your battery report will be saved to a folder on your PC, which you'll see in the PowerShell window when you attempt to save a new report. You can also manually change the destination folder when running the command, to make the HTML file easier to find.
* What does "charge cycle" or "cycle count" mean in my Windows battery report?  
 Cycle counts and charge cycles refer to the number of times your battery used up 100 percent (cumulative) of its charge. This applies to both draining the battery to 0 percent and recharging it, as well as incremental drains. For example, using 30 percent of the battery, recharging to 100 percent, then using 70 percent counts as one cycle.
* How do I recalibrate a new battery in Windows?  
 Once you've installed a new battery, charge it to 100 percent, let it run down to zero, and then recharge it back to 100 percent. This will allow Windows to better keep track of the new battery's capacity (and other stats).

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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-prime-strategies-for-constructing-mcc-homes/"><u>[New] In 2024, Prime Strategies for Constructing MCC Homes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-play-mov-files-on-13t-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can't play .mov files on 13T</u></a></li>
<li><a href="https://extra-resources.techidaily.com/capture-the-moment-professional-techniques-in-hdr-portraiture/"><u>Capture the Moment Professional Techniques in HDR Portraiture</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722901189621-discover-the-leading-news-curators-our-ultimate-list/"><u>Discover the Leading News Curators : Our Ultimate List!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-installation-of-hp-deskjet-2600-printer-drivers-on-windows-7-8-and-10/"><u>Easy Installation of HP DeskJet 2600 Printer Drivers on Windows 7, 8 & 10</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-solutions-for-overcoming-error-code-19-in-windows-systems/"><u>Effective Solutions for Overcoming Error Code 19 in Windows Systems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effortless-email-management-connecting-gmail-to-apple-watch/"><u>Effortless Email Management: Connecting Gmail to Apple Watch</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/essential-criteria-to-examine-when-picking-out-a-fitness-band-or-watch/"><u>Essential Criteria to Examine When Picking Out a Fitness Band or Watch</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-vivo-v30-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Vivo V30</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-signing-up-for-chatgpt-plus-justifiable-discover-five-convincing-reasons-why/"><u>Is Signing up for ChatGPT Plus Justifiable? Discover Five Convincing Reasons Why!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/leading-autonomous-vehicle-producers-top-4-picks/"><u>Leading Autonomous Vehicle Producers : Top 4 Picks</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-cross-platform-use-a-step-by-step-guide-to-running-linux-on-xcode-with-an-ingenious-hack-exclusive/"><u>Mastering Cross-Platform Use: A Step-by-Step Guide to Running Linux on Xcode with an Ingenious Hack Exclusive</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/migrating-your-google-images-library-to-apples-icloud-storage-a-step-by-step-guide/"><u>Migrating Your Google Images Library to Apple's iCloud Storage: A Step-by-Step Guide</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/professional-grade-hd-video-editors-our-top-5-for-2024/"><u>Professional-Grade HD Video Editors Our Top 5 for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-unlocking-apple-watch-or-apple-iphone-xs-from-icloud-by-drfone-ios/"><u>The Ultimate Guide to Unlocking Apple Watch Or Apple iPhone XS from iCloud</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-when-cod-vanguards-voice-chat-wont-connect/"><u>Troubleshooting Guide: When COD: Vanguard's Voice Chat Won't Connect</u></a></li>
</ul></div>

