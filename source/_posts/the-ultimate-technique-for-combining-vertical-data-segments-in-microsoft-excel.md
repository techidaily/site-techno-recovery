---
title: The Ultimate Technique for Combining Vertical Data Segments in Microsoft Excel
date: 2024-09-25T16:33:14.255Z
updated: 2024-09-27T02:25:21.036Z
categories:
  - BestProducts
description: This Article Describes The Ultimate Technique for Combining Vertical Data Segments in Microsoft Excel
excerpt: This Article Describes The Ultimate Technique for Combining Vertical Data Segments in Microsoft Excel
thumbnail: https://www.lifewire.com/thmb/VpbzeB-Bk7zWyZLondiDdfVniDY=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/dean-pugh-C8NDn4xk9zs-unsplash-f0dd8299f92842af80b9013007ab8630.jpg
---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## The Ultimate Technique for Combining Vertical Data Segments in Microsoft Excel
### What to Know

* Using the concatenate formula in Microsoft Excel you can combine two or more columns of data into one without losing any data.
* Once you've created the CONCATENATE formula in the first cell,**drag the Fill Handle** to duplicate the formula for remaining cells.
* Once combined, you need to change the merged data to values using copy and paste so you can delete or change the original data.

 This article explains how to combine two columns of data in Microsoft Excel into a single column without losing that data.

![A windows laptop sitting on a window sill, displaying Microsoft Excel.](https://www.lifewire.com/thmb/En3iWwF7IcbNVtlTPxk03Lieyas=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/dean-pugh-C8NDn4xk9zs-unsplash-f0dd8299f92842af80b9013007ab8630.jpg)

Dean Pugh / Unsplash

## How to Combine Columns in Excel Without Losing Data

 If you just want to merge two empty columns in Excel, that's easy enough to do using the Merge option, but if those columns contain data, you'll lose all the data except what's in the uppermost left cell. If what you're actually trying to do is merge the data from two columns into a single column, the merge command won't work. Instead, you need to use the**CONCATENATE** formula to combine that data.

1. In the Excel worksheet where you want to combine two columns of data, first insert a new column near the data you want to combine. This is where your combined data will be displayed.  
 To insert a new column, right click a column to the right of where you want the new column to appear and select**Insert** from the menu that appears.
2. If your other columns have headers, give the new column a header name. In our example, it's**Full Name** .  
 You can use this same formula to combine the data from several columns. You just need to write it using the same syntax as above: **\=CONCATENATE (Cell1, "Separator", Cell2,"Separator", Cell 3...etc)**
3. Select the the first cell below the heading of the new column (C2 in this example) enter the following into the formula bar:  
**\=CONCATENATE(A2," ",B2)**  
 This tells excel you want to combine the data in cell A2 with the data in cell B2, with a space (" ") between them. In this example, the space between quotation marks is the separator, but if you choose, you can use any other separator you like.  
 For example, if a comma were between the quotation marks, like this:**\=CONCATENATE(A2,","B2)** then the data from cell A would be separated from the data in cell B by a comma.  
![The CONCATENATE formula in Microsoft Excel.](https://www.lifewire.com/thmb/nm_g5q7qFrqjiTG1U2qn2pioUDs=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_01-60e150b9f37a4835862036139397bc3f.jpg)
4. Once you've completed the formula, press**Enter** on your keyboard to activate it. The new data combination should appear in the cell.  
![The results of the CONCATENATE formula in Microsoft Excel.](https://www.lifewire.com/thmb/lrpZXUMOgKEYWsx163xnNjDFz6E=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_02-8b69ebb739dd4721a90babcd0465d135.jpg)
5. Now, you can copy the formula down the length of the column to combine all the desired entries. To do that, place your cursor bac in the previous cell (C2 in the example), grab the green dot (called the**Fill Handle** ) in the lower right corner of the screen and drag down the length of the column you want to use.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will apply the formula to all selected rows.  
![An illustration of how to use the Fill Handle in Microsoft Excel.](https://www.lifewire.com/thmb/jRYAhCFQTgZj888CujHR4w9QvUQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_03-674a233d08ec4ea0bcf80e3bec90d68b.jpg)
6. Now, the data in the new column is part of a formula, and as such, if you delete any of the data used in the formula (in this example, any data in columns A or B) it will cause the combined data in column C to disappear.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151882/7443" target="_top" id="2151882">
  <img src="//a.impactradius-go.com/display-ad/7443-2151882" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151882/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To prevent this, you need to save all the new entries as a value so they won't disappear. So first, highlight all the combined data you just created and use the keyboard shortcut**Ctrl + C** on Windows or**Command + C** on Mac to copy it.  
![Data selection in Microsoft Excel.](https://www.lifewire.com/thmb/dJvhnrsFHFqq9jYyuvPDvP6vD_8=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_04-0f81b1dc8ff5485cb2adf07a5f4262e3.jpg)
7. Then, in the first corresponding cell of the column you copied the data from, right click and select**Paste Value** .  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134229/18498" target="_top" id="2134229">
  <img src="//a.impactradius-go.com/display-ad/18498-2134229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134229/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Past Value option in Microsoft Excel.](https://www.lifewire.com/thmb/PZ3_xakgfZ_JtN1mmM00mCW8m7Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_05-054201d683a14effbdab321008554e88.jpg)
8. The combined data will be pasted into the column as a value and you can change or delete the data from the original columns without changing the new, combined data.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868590/19272" target="_top" id="1868590">
  <img src="//a.impactradius-go.com/display-ad/19272-1868590" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868590/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-the-ultimate-guide-to-media-player-replacements-for-vlc/"><u>[New] In 2024, The Ultimate Guide to Media Player Replacements for VLC</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-ultimate-soundscapes-for-visual-storytelling/"><u>[New] Ultimate Soundscapes for Visual Storytelling</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unraveling-the-film-reel-how-to-rewind-on-instagram/"><u>[New] Unraveling the Film Reel How to Rewind on Instagram</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-pro-level-phone-and-camera-gimbal-tracking-systems/"><u>2024 Approved Pro-Level Phone & Camera Gimbal Tracking Systems</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-transform-your-screen-with-webcam-creativity/"><u>2024 Approved Transform Your Screen with Webcam Creativity</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/dts-virtualx-explained-a-comprehensive-overview-of-next-gen-audio-formats/"><u>DTS Virtual:X Explained: A Comprehensive Overview of Next-Gen Audio Formats</u></a></li>
<li><a href="https://win-answers.techidaily.com/guide-to-resolving-nier-replicant-revived-version-boot-problems/"><u>Guide to Resolving NieR Replicant Revived Version Boot Problems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/insightful-critique-on-the-performance-of-western-digital-data-lifeguard-tools-for-hard-drive-health-checking/"><u>Insightful Critique on the Performance of Western Digital Data LifeGuard Tools for Hard Drive Health Checking</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/missing-facebook-marketplace-a-step-by-step-guide/"><u>Missing Facebook Marketplace? A Step-by-Step Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-missing-msvcrtdll-issues-step-by-step-guide/"><u>Resolving 'Missing msvcrt.dll' Issues: Step-by-Step Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/sharing-stories-that-resonate-with-crowds/"><u>Sharing Stories that Resonate with Crowds</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unstuck-apple-watch-discover-6-strategies-for-restoring-seamless-device-synchronization/"><u>Unstuck Apple Watch: Discover 6 Strategies for Restoring Seamless Device Synchronization</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-secrets-of-bass-management-in-audio-systems/"><u>Unveiling the Secrets of Bass Management in Audio Systems</u></a></li>
</ul></div>

