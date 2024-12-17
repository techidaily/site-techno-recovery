---
title: "Combine Power: Techniques for Joining Two Excel Columns Effectively"
date: 2024-12-13T09:34:50.670Z
updated: 2024-12-17T07:00:01.971Z
categories:
  - BestProducts
description: "This Article Describes Combine Power: Techniques for Joining Two Excel Columns Effectively"
excerpt: "This Article Describes Combine Power: Techniques for Joining Two Excel Columns Effectively"
thumbnail: https://thmb.techidaily.com/cb9e2ddf28e5428496f53b353379d173f81be07c333aa30876bace061b3bea41.jpg
---

## Combine Power: Techniques for Joining Two Excel Columns Effectively

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will apply the formula to all selected rows.  
![An illustration of how to use the Fill Handle in Microsoft Excel.](https://www.lifewire.com/thmb/jRYAhCFQTgZj888CujHR4w9QvUQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_03-674a233d08ec4ea0bcf80e3bec90d68b.jpg)
6. Now, the data in the new column is part of a formula, and as such, if you delete any of the data used in the formula (in this example, any data in columns A or B) it will cause the combined data in column C to disappear.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To prevent this, you need to save all the new entries as a value so they won't disappear. So first, highlight all the combined data you just created and use the keyboard shortcut**Ctrl + C** on Windows or**Command + C** on Mac to copy it.  
![Data selection in Microsoft Excel.](https://www.lifewire.com/thmb/dJvhnrsFHFqq9jYyuvPDvP6vD_8=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_04-0f81b1dc8ff5485cb2adf07a5f4262e3.jpg)
7. Then, in the first corresponding cell of the column you copied the data from, right click and select**Paste Value** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Past Value option in Microsoft Excel.](https://www.lifewire.com/thmb/PZ3_xakgfZ_JtN1mmM00mCW8m7Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Excel_05-054201d683a14effbdab321008554e88.jpg)
8. The combined data will be pasted into the column as a value and you can change or delete the data from the original columns without changing the new, combined data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-restore-shadows-in-iphone-hdr-footage-using-premiere-pro-techniques/"><u>[New] 2024 Approved Restore Shadows in iPhone HDR Footage Using Premiere Pro Techniques</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-boost-your-storytelling-on-instagram-with-loops/"><u>[New] Boost Your Storytelling on Instagram With Loops</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-joke-factory-imgur-edition/"><u>[Updated] In 2024, Joke Factory Imgur Edition</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-kinemaster-focus-mastery-a-filmmakers-guide-to-sharper-images-for-2024/"><u>[Updated] Kinemaster Focus Mastery A Filmmaker's Guide to Sharper Images for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-uncovering-notable-versions-within-microsofts-movie-maker/"><u>[Updated] Uncovering Notable Versions Within Microsoft's Movie Maker</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/boosting-performance-top-tips-for-gamers-using-windows-11/"><u>Boosting Performance: Top Tips for Gamers Using Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/complete-tutorial-how-to-easily-delete-applications-in-windows-10-environment/"><u>Complete Tutorial: How to Easily Delete Applications in Windows 10 Environment</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/connecting-your-ps3-controller-to-a-pc-a-guide-that-doesnt-involve-motioninjoy-software/"><u>Connecting Your PS3 Controller to a PC: A Guide That Doesn't Involve MotionInJoy Software</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-whats-fresh-with-windows-10-creators-edition-building-1503-preview-guide/"><u>Discover What’s Fresh with Windows 10 Creator's Edition - Building 1503 Preview Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-your-running-windows-os-quick-guide-in-a-single-step/"><u>Discover Your Running Windows OS: Quick Guide in a Single Step</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/easy-guide-resetting-a-forgotten-skype-password-in-minutes/"><u>Easy Guide: Resetting a Forgotten Skype Password in Minutes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/easy-ways-to-swap-video-games-with-peers-via-steam-network/"><u>Easy Ways to Swap Video Games with Peers via Steam Network</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-locked-apple-iphone-13-pro-max-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>Forgot Locked Apple iPhone 13 Pro Max Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-poco-x6-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Poco X6 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-soft-onset-visual-effects/"><u>In 2024, Soft Onset Visual Effects</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-smooth-gameplay-fix-your-ping-and-lag-in-chivalry-2-using-modern-techniques-2024-insights/"><u>Mastering Smooth Gameplay: Fix Your Ping and Lag in Chivalry 2 Using Modern Techniques (2024 Insights)</u></a></li>
</ul></div>

