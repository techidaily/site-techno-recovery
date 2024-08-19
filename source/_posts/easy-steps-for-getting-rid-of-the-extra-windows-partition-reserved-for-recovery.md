---
title: Easy Steps for Getting Rid of the Extra Windows Partition Reserved for Recovery
date: 2024-08-18T17:50:14.394Z
updated: 2024-08-19T17:50:14.394Z
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## How to Format a Partition 

 Deleting a recovery partition will create a section of unallocated space on your drive. To use the unallocated space, you must format the partition:

1. Right-click the **Start** menu and select **Disk Management** .  
 If using Windows 7 or earlier, click the**Start** menu and type **diskmgmt.msc** in the search box to find the Disk Management tool.
2. Beside the disk number for your hard drive, you'll see several partitions, including one named**Unallocated** . Right-click the**Unallocated** partition and select**New Simple Volume** .  
![New volume](https://www.lifewire.com/thmb/vSV9HGlkrIuOGf57tgxOOWkYPSA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/011_delete-windows-recovery-partition-4128723-bbdbf03a107941c4b897dac28d81c481-12eafd51c56c4e309d480d3341906f0d.jpg)
3. Select**Next** to continue the wizard.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
4. Enter how much data the new partition should use out of the unallocated space, then select**Next** .  
![Size volume](https://www.lifewire.com/thmb/hTSzg-d-_iXMiKGEHivv-Y80bhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/013_delete-windows-recovery-partition-4128723-c3e7a897eaf74a2cbb07e5d3cd346d05-976944267d764fddb1dbc8486b288d8d.jpg)
5. Choose a letter from the drop-down menu to assign to the partition, then select**Next** .  
![drive letter](https://www.lifewire.com/thmb/t7Fd7PU9y95GJmLVpVgmIqFFpS0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/014_delete-windows-recovery-partition-4128723-bb8b69c95baf427da9438ec7ea8b00e1-2f87c151c02443b5be4f3054f734089e.jpg)
6. Enter a name for the partition in the**Volume label** field, then select**Next** .  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The default file system is[ NTFS](https://www.lifewire.com/ntfs-file-system-2625948) , but you can change it to[ FAT32](https://www.lifewire.com/what-is-file-allocation-table-fat-2625877) or another file system if you wish.  
![volume label](https://www.lifewire.com/thmb/b0FQo4mw5s7_yymf0Yz0bb57juc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/015_delete-windows-recovery-partition-4128723-3cd8c2d36a3046b7b44ee333928b82bb-634a4447146f4f4a874e1c72fd640b13.jpg)
7. Select**Finish** to close the wizard.
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  How to Expand a Partition to Use the Unallocated Space 

 If you want to expand another partition to use the extra space, then the unallocated space must appear to the immediate right of that partition in the Disk Management tool. To extend a partition:

1. Right-click the partition you want to expand and select**Extend Volume** .  
![extend volume](https://www.lifewire.com/thmb/I75j9u4O2PBCkkuxXXdF3ZWYk8U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/017_delete-windows-recovery-partition-4128723-189b97dc135a4975ab409bfa11c404af-869b027d5b8d4beeac0013e2e75b2fc2.jpg)
2. Select**Next** to continue the wizard.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Enter how much of the unallocated space you want to use, then select**Next** .  
![drive size](https://www.lifewire.com/thmb/mXgg3V0zWVClHPqDGqa-nsiA1OA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/019_delete-windows-recovery-partition-4128723-68d4465915374357af41a11672bc0857-d19bbede5e6346e6a1f1240d4a738789.jpg)
4. Select**Finish** to terminate the wizard. The Windows partition will be resized to include the extra space.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://extra-information.techidaily.com/new-brief-blueprints-iphone-content-for-desktop/"><u>[New] Brief Blueprints  IPhone Content for Desktop</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-boost-story-impact-with-customized-video-speed-settings/"><u>2024 Approved  Boost Story Impact with Customized Video Speed Settings</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-christian-hymnal-options-for-ringtone-customization/"><u>2024 Approved  Christian Hymnal Options for Ringtone Customization</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-the-ultimate-guide-to-cross-platform-movie-capture/"><u>2024 Approved  The Ultimate Guide to Cross-Platform Movie Capture</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/a-beginners-guide-to-communicating-with-emoji-on-an-iphone/"><u>A Beginner's Guide to Communicating with Emoji on an iPhone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/a-complete-walkthrough-on-securing-an-apple-tech-specialist-meeting/"><u>A Complete Walkthrough on Securing an Apple Tech Specialist Meeting</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-solutions-to-rectify-mscorwksdll-missing-on-your-computer/"><u>Comprehensive Solutions to Rectify mscorwks.dll Missing on Your Computer</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/connecting-desktop-and-television-using-googles-chromecast-a-comprehensive-tutorial/"><u>Connecting Desktop and Television Using Google's Chromecast: A Comprehensive Tutorial</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/cut-the-clutter-advanced-techniques-with-youtube-studio-editor/"><u>Cut the Clutter  Advanced Techniques with YouTube Studio Editor</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/emoji-mysteries-exposed-uncover-these-10-fascinating-factoids-about-your-favorite-digital-icons/"><u>Emoji Mysteries Exposed: Uncover These 10 Fascinating Factoids About Your Favorite Digital Icons</u></a></li>
<li><a href="https://buynow-info.techidaily.com/experience-cutting-edge-chic-with-the-latest-michael-kors-access-gen-5e-mkgo-collection-reviewed/"><u>Experience Cutting-Edge Chic with the Latest Michael Kors Access Gen 5E MKGO Collection Reviewed!</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlocking-apple-iphone-11-passcode-without-a-computer-drfone-by-drfone-ios/"><u>In 2024, Unlocking Apple iPhone 11 Passcode without a Computer | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-is-ipogo-not-working-on-realme-10t-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Realme 10T 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/iphone-tips-for-putting-a-stop-to-unwanted-texting/"><u>IPhone Tips for Putting a Stop to Unwanted Texting</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/leading-retailers-offering-exceptional-phones-shop-smart/"><u>Leading Retailers Offering Exceptional Phones - Shop Smart!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mac-users-manual-effective-methods-for-app-deletion/"><u>Mac User's Manual: Effective Methods for App Deletion</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/maximizing-ring-tone-clarity-and-volume-for-ios-devices/"><u>Maximizing Ring Tone Clarity and Volume for iOS Devices</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-through-details-tap-to-zoom-on-and-off-on-ios-gadgets/"><u>Navigating Through Details: Tap to Zoom On & Off on iOS Gadgets</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/overcoming-cygwin1dll-not-found-problems-with-these-easy-tips/"><u>Overcoming Cygwin1.dll Not Found Problems with These Easy Tips</u></a></li>
<li><a href="https://extra-support.techidaily.com/pro-tips-the-fastest-5-diy-filmmaking-tricks-at-home-for-2024/"><u>Pro Tips  The Fastest 5 DIY Filmmaking Tricks at Home for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-breakdown-of-every-ipados-update-cycle/"><u>Step-by-Step Breakdown of Every iPadOS Update Cycle</u></a></li>
<li><a href="https://extra-support.techidaily.com/step-by-step-guide-to-infectious-internet-memes-gifs-for-2024/"><u>Step-by-Step Guide to Infectious Internet Memes (GIFs) for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-mastering-split-screen-views-on-your-macbook-air/"><u>Step-by-Step Guide: Mastering Split Screen Views on Your MacBook Air</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-instructions-on-how-to-access-and-utilize-the-wayback-machine-for-historical-web-data/"><u>Step-by-Step Instructions on How to Access and Utilize the Wayback Machine for Historical Web Data</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722896037789-the-ultimate-guide-to-samsungs-new-z-flip-releasing-soon-price-range-and-feature-highlights-inside/"><u>The Ultimate Guide to Samsung's New Z Flip ✨: Releasing Soon? Price Range and Feature Highlights Inside!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-10-must-watch-80s-films-perfect-for-your-next-movie-night/"><u>Top 10 Must-Watch '80S Films Perfect for Your Next Movie Night</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-18-essential-shortcuts-every-iphone-user-should-know-in-the-ios-shortcuts-app/"><u>Top 18 Essential Shortcuts Every iPhone User Should Know in the iOS Shortcuts App</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-resolving-the-0x0000003d-blue-screen-of-death/"><u>Ultimate Guide: Resolving the 0X0000003D Blue Screen of Death</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/upcoming-apple-audio-innovation-detailed-breakdown-of-expected-pricing-launch-window-and-speculative-leaks/"><u>Upcoming Apple Audio Innovation: Detailed Breakdown of Expected Pricing, Launch Window, & Speculative Leaks</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/vocabverve-at-dubai-2020-pioneering-multilingualism/"><u>VocabVerve at Dubai 2020: Pioneering Multilingualism</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/watch-tv-shows-and-movies-for-free-stream-with-crackle/"><u>Watch TV Shows & Movies For Free - Stream with Crackle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719376441397-why-arent-window-11-thumbnail-images-displayed-solutions-available/"><u>Why Aren't Window 11 Thumbnail Images Displayed? Solutions Available</u></a></li>
</ul></div>
