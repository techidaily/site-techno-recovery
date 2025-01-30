---
title: Easy Steps for Getting Rid of the Extra Windows Partition Reserved for Recovery
date: 2025-01-25T16:52:00.203Z
updated: 2025-01-30T16:13:59.533Z
categories:
  - BestProducts
description: This Article Describes Easy Steps for Getting Rid of the Extra Windows Partition Reserved for Recovery
excerpt: This Article Describes Easy Steps for Getting Rid of the Extra Windows Partition Reserved for Recovery
thumbnail: https://www.lifewire.com/thmb/ALlLdPlK0nhyrSKTrZhz_J3x2vc=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/hard-drive-56a2cb273df78cf7727a0201.jpg
---

## Easy Steps for Getting Rid of the Extra Windows Partition Reserved for Recovery

Close 

###  What to Know

* In PowerShell or Command Prompt:**diskpart** \>**list disk** \>**select disk #** \>**list partition** \>**select partition #** \>**delete partition override** .
* To format partition: right-click**Start** \>**Disk Management** \> right-click**Unallocated** \>**New Simple Volume** \> follow wizard.

 This article explains how to delete a recovery partition in Windows 11, 10, 8, and 7\. It also explains how to format and expand a partition to use the unallocated space.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Delete a Recovery Partition in Windows 

 Because recovery partitions are protected, the steps for removing them differ from deleting a normal partition.

 When you[ create a recovery partition for Windows](https://www.lifewire.com/create-recovery-drive-all-versions-windows-2200650) , it's best to store it on an[ external drive](https://www.lifewire.com/what-is-an-external-drive-2625867) in case something happens to your computer. After saving it somewhere else, you can delete the recovery partition from your PC to free up space.

1. Right-click the Start menu and select**Terminal (Admin)** Windows 11,**Windows PowerShell (Admin)** , or**Command Prompt (Admin)** .  
 If you're using Windows 7 or earlier, you'll have to[ open Command Prompt](https://www.lifewire.com/how-to-open-command-prompt-2618089) another way, like through the Start menu or Run dialog box.
2. Type**diskpart** and press**Enter** , then type**list disk** and press**Enter** .
3. A list of disks displays. Type   **select disk _#_**  (where _#_ is the number of the disk with the recovery partition) and press **Enter** .  
 If you're unsure which one it's on, find out by opening the[ Disk Management tool](https://www.lifewire.com/disk-management-2625863) .  
![Select Disk](https://www.lifewire.com/thmb/1Mt2ZXpoT3G6vxjBufv-L3Ax_IM=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/005_delete-windows-recovery-partition-4128723-39d975e00e4342e4ab2690b442c55cc3-5a89be105dd942a0b63ac8b7daf23288.jpg)
4. Type **list partition**  and press **Enter** . A list of partitions displays. Type **select partition #**  (where _#_ is the number of the recovery partition) and press **Enter** .  
![select partition](https://www.lifewire.com/thmb/EWAsDd1kl5UkUHvxcACEQzBdvyw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/007_delete-windows-recovery-partition-4128723-fcdf0b8b44b84e00b08b0da8a89f5052-5befaed89aef4289bc842118b9c4dbfd.jpg)
5. Type **delete partition override** and press**Enter** .

 After you see a confirmation message, you can close the PowerShell/Command Prompt.

![partition override](https://www.lifewire.com/thmb/77odldkkcz9Dr2ifvItweMN-dSg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/009_delete-windows-recovery-partition-4128723-911baa68a0124e87b42297fc999ad2fa-b7cba53da27543f9a82eb6a6fd047464.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Format a Partition 

 Deleting a recovery partition will create a section of unallocated space on your drive. To use the unallocated space, you must format the partition:

1. Right-click the **Start** menu and select **Disk Management** .  
 If using Windows 7 or earlier, click the**Start** menu and type **diskmgmt.msc** in the search box to find the Disk Management tool.
2. Beside the disk number for your hard drive, you'll see several partitions, including one named**Unallocated** . Right-click the**Unallocated** partition and select**New Simple Volume** .  
![New volume](https://www.lifewire.com/thmb/vSV9HGlkrIuOGf57tgxOOWkYPSA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/011_delete-windows-recovery-partition-4128723-bbdbf03a107941c4b897dac28d81c481-12eafd51c56c4e309d480d3341906f0d.jpg)
3. Select**Next** to continue the wizard.
4. Enter how much data the new partition should use out of the unallocated space, then select**Next** .  
![Size volume](https://www.lifewire.com/thmb/hTSzg-d-_iXMiKGEHivv-Y80bhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/013_delete-windows-recovery-partition-4128723-c3e7a897eaf74a2cbb07e5d3cd346d05-976944267d764fddb1dbc8486b288d8d.jpg)
5. Choose a letter from the drop-down menu to assign to the partition, then select**Next** .  
![drive letter](https://www.lifewire.com/thmb/t7Fd7PU9y95GJmLVpVgmIqFFpS0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/014_delete-windows-recovery-partition-4128723-bb8b69c95baf427da9438ec7ea8b00e1-2f87c151c02443b5be4f3054f734089e.jpg)
6. Enter a name for the partition in the**Volume label** field, then select**Next** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The default file system is[ NTFS](https://www.lifewire.com/ntfs-file-system-2625948) , but you can change it to[ FAT32](https://www.lifewire.com/what-is-file-allocation-table-fat-2625877) or another file system if you wish.  
![volume label](https://www.lifewire.com/thmb/b0FQo4mw5s7_yymf0Yz0bb57juc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/015_delete-windows-recovery-partition-4128723-3cd8c2d36a3046b7b44ee333928b82bb-634a4447146f4f4a874e1c72fd640b13.jpg)
7. Select**Finish** to close the wizard.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Expand a Partition to Use the Unallocated Space 

 If you want to expand another partition to use the extra space, then the unallocated space must appear to the immediate right of that partition in the Disk Management tool. To extend a partition:

1. Right-click the partition you want to expand and select**Extend Volume** .  
![extend volume](https://www.lifewire.com/thmb/I75j9u4O2PBCkkuxXXdF3ZWYk8U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/017_delete-windows-recovery-partition-4128723-189b97dc135a4975ab409bfa11c404af-869b027d5b8d4beeac0013e2e75b2fc2.jpg)
2. Select**Next** to continue the wizard.
3. Enter how much of the unallocated space you want to use, then select**Next** .  
![drive size](https://www.lifewire.com/thmb/mXgg3V0zWVClHPqDGqa-nsiA1OA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/019_delete-windows-recovery-partition-4128723-68d4465915374357af41a11672bc0857-d19bbede5e6346e6a1f1240d4a738789.jpg)
4. Select**Finish** to terminate the wizard. The Windows partition will be resized to include the extra space.

 FAQ

* Is it safe to delete a recovery partition in Windows?  
 Yes. Removing a recovery partition will not affect the Windows operating system.
* How do I restore a deleted Windows recovery partition?  
 To restore deleted recovery partitions,[ rebuild the Windows Boot Configuration Drive](https://www.lifewire.com/how-to-rebuild-the-bcd-in-windows-2624508) , use a third-party tool, or reinstall Windows.
* How do I factory reset Windows without a recovery partition?  
 Use[ Reset This PC](https://www.lifewire.com/reset-this-pc-complete-walkthrough-2624538) to restore your Windows PC to factory settings. In Windows 8, use Refresh Your PC to back up your files first.
* How do I create a recovery drive in Windows?  
 In Windows 11 or 10, search for**Create a recovery drive** and check the box beside**Back up system files to the recovery drive** . Next, connect a USB drive, then select**Next** . You can also[ create a recovery drive in Windows 8](https://www.lifewire.com/how-to-create-a-windows-recovery-drive-2625164) .

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[ Subscribe ](https://www.lifewire.com/#) 

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
<li><a href="https://youtube-videos.techidaily.com/new-beat-buzzers-up-and-coming-background-scores-for-yt-shorts/"><u>[New] Beat Buzzers Up-and-Coming Background Scores For YT Shorts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-enhance-mobile-viewing-fb-videos-on-android/"><u>[New] Enhance Mobile Viewing FB Videos on Android</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/nblock-your-youtube-experience-easy-solutions-for-chromefirefox/"><u>[New] Unblock Your YouTube Experience Easy Solutions for Chrome/Firefox</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-5-steps-to-transform-your-photos-hues-right-away/"><u>[Updated] 5 Steps to Transform Your Photo's Hues Right Away</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/affordable-luxury-equivalent-value-to-a-vision-pro-in-top-tier-gadgets-iphone-ipad-watch-and-more-tech-insights-on-zdnet/"><u>Affordable Luxury! Equivalent Value to a Vision Pro in Top-Tier Gadgets: IPhone, iPad, Watch and More | Tech Insights on ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-tips-for-capturing-stunning-meta-quest-3-images-and-video-clips-zdnet-guide/"><u>Expert Tips for Capturing Stunning Meta Quest 3 Images & Video Clips - ZDNet Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-safe-zone-limits-how-apples-vision-pro-tracks-up-against-metas-quests-for-virtual-reality-experience/"><u>Exploring Safe Zone Limits: How Apple's Vision Pro Tracks Up Against Meta's Quests for Virtual Reality Experience</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-restore-metas-deleted-quest-gaming-headset-functionality-with-easy-hacks-techradar/"><u>How to Restore Meta’s Deleted Quest Gaming Headset Functionality with Easy Hacks | TechRadar</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-quick-guide-eluding-educational-videos-effectively/"><u>In 2024, Quick Guide Eluding Educational Videos Effectively</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/intense-competition-alert-for-apple-as-meta-and-lg-unveil-next-gen-quest-pro-virtual-reality-headset-tech-news-by-zdnet/"><u>Intense Competition Alert for Apple as Meta and LG Unveil Next-Gen Quest Pro Virtual Reality Headset | Tech News by ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/key-components-of-a-successful-digital-twin-strategy-incorporating-ai-zdnet-insights/"><u>Key Components of a Successful Digital Twin Strategy: Incorporating AI | ZDNet Insights</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-deployment-of-digital-twins-tackling-business-hurdles-effectively-zdnet/"><u>Mastering the Deployment of Digital Twins: Tackling Business Hurdles Effectively | ZDNet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-errors-in-ftddi-protecting-system-memory-when-incorrect-drivers-cause-interruptions/"><u>Resolving Errors in FTDDI: Protecting System Memory When Incorrect Drivers Cause Interruptions</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-the-ntoskrnlexe-blue-screen-issue-a-guide-for-windows-users/"><u>Resolving the ntoskrnl.exe Blue Screen Issue: A Guide for Windows Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/seamless-connectivity-tips-on-syncing-airpods-with-quest-3-wirelessly-the-courteous-guide/"><u>Seamless Connectivity: Tips on Syncing AirPods with Quest 3 Wirelessly – The Courteous Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-realme-10t-5g-by-drfone-android/"><u>Three Ways to Sim Unlock Realme 10T 5G</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/ultimate-top-11-list-excellent-audio-devices-for-2024/"><u>Ultimate Top 11 List Excellent Audio Devices for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/upcoming-apple-vision-pro-update-may-include-respiratory-pattern-analysis-says-zdnet-report/"><u>Upcoming Apple Vision Pro Update May Include 'Respiratory Pattern Analysis', Says ZDNet Report</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/wd-rescan-paused-fixes-and-solutions-for-non-responding-device-in-windows-11-10-8-and-7/"><u>WD Rescan Paused: Fixes and Solutions for Non-Responding Device in Windows 11, 10, 8, & 7</u></a></li>
</ul></div>

