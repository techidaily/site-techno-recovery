---
title: "Boosting Command Prompt Convenience on Windows: Tweaking Your System PATH Settings for Quick Access"
date: 2024-12-20T01:15:27.229Z
updated: 2024-12-25T18:20:48.084Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/9986a0298b6ed41baf9ff52abd2373f4874f20858ec27b5c29bc07659651b716.jpg
---

## Boosting Command Prompt Convenience on Windows: Tweaking Your System PATH Settings for Quick Access

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What Is the Windows System PATH?](https://facebook-record-videos.techidaily.com/updated-harmonizing-youtube-content-a-guide-to-blending-files/)
* [How to Add a Folder to Your PATH](https://fox-cloud.techidaily.com/new-quirky-creations-your-guide-to-no-cost-memes/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

 The PATH tells Windows where it should look for executables, making them accessible via command-line interfaces or scripts. To add a new folder to PATH, navigate to Advanced System Settings > Environment Variables, select PATH, click "Edit" and then "New."

 Have you ever wondered why you can just type ipconfig into a command prompt and it works, but when you want to use a command line program you downloaded you have to navigate to its directory first? Here's how to fix that using the Windows System PATH on Windows 10 and Windows 11.

##  What Is the Windows System PATH?

 The Windows System PATH tells your PC where it can find specific directories that contain executable files. Ipconfig.exe, for example, is found in the C:\\Windows\\System32 directory, which is a part of the system PATH by default. When you type ipconfig into a Command Prompt, Windows doesn't need to know where that EXE is—it'll check all the folders in its PATH until it finds the right one.

 If you've downloaded a program that uses a command-line interface—like ADB, the [Android Debug Bridge](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/)—you can't just type adb in the Command Prompt or PowerShell to run it, like you can with Windows' built-in commands (e.g.ipconfig). Instead, you have to tell Command Prompt where to find that file, by typing in the full path of the EXE:

C:\Android\platform-tools\adb.exe

 If you don't, you'll get an error message like this.

![ADB is not recognized since it is not on the system PATH.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/adb-error.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That's a lot of typing, especially for something you have to run often.

 If you want the same convenience with a program you downloaded (like ADB), you need to add its folder to Windows' system PATH. That way, when you need to run adb, you can just run:

adb

 No extra typing necessary.

##  How to Add a Folder to Your PATH

 These steps are basically the same on Windows 10 and Windows 11\. There are just some minor differences in the user interface.

 Start by pressing the Windows key to open up the Start Menu, then search for "advanced system settings." You can alternatively browse through Control Panel to System and Security > System and click on the "Advanced system settings" hyperlink in the left-hand pane.

![Search for and open "Advanced System Settings."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/advanced-system.png) 

 Once the System Properties window opens, click on the "Environment Variables" button.

![Click &quot;Environment Variables.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/environmental-variables.png) 

 In the "System Variables" box, look for a variable called _Path._ Select that and click on the "Edit" button.

 You can modify the PATH for only the current user by changing the PATH variable under "User Variables." It won't affect other users, however. In many cases, it is better and more convenient to add something to the system PATH, so it is universally accessible on your PC.

![Select &quot;PATH&quot; under &quot;System Variables,&quot; then click &quot;Edit.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/system-variables.png) 

 This process is both easier and less confusing in Windows 10 and Windows 11 than it was in earlier versions of Windows. Once you've clicked the edit button, a new dialog box will appear with each location in the PATH on a separate line. This is a dramatic improvement over the way previous versions of Windows handled PATH locations and makes easy work of adding a new one.

![The current PATH.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/PATH-Stuff.png) 

 First, click the 'new' button, which will add a line at the end of the list. Add your location—"C:\\AndroidSDK" in our example—and hit Enter. Click the "OK" button and you're finished.

 Older versions of Windows required each line end with a semi-colon, but Windows 10 and 11 do not if you use the user interface like we are here. If you use a command-line interface to edit the PATH, you'll still find them there.

![Click &quot;New,&quot; enter the path to ADB, then click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/android-SD.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The Android Debugging Bridge should now be accessible from any Command Prompt, PowerShell, or Windows Terminal, with no need to specify its directory.

![ADB now works in PowerShell without specifying the path manually.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/adb-on-path.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can add as many locations as you like to PATH. However, convention and best practice dictate that you try to avoid cluttering up your PATH with unnecessary executables.

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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-transforming-standard-calls-into-visual-masterpieces-with-zoom/"><u>[New] 2024 Approved Transforming Standard Calls Into Visual Masterpieces with Zoom</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-new-to-vector-art-dive-into-basics-forms-and-software/"><u>[New] New to Vector Art? Dive Into Basics, Forms, and Software</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-dissecting-shake-control-does-it-truly-enhance-editing-results/"><u>[Updated] 2024 Approved Dissecting Shake Control Does It Truly Enhance Editing Results?</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-nubia-red-magic-9-pro-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Nubia Red Magic 9 Pro FRP Bypass Instantly</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/anker-737-battery-savings-claim-your-exclusive-30-discount-on-portable-charger-zdnet/"><u>Anker 737 Battery Savings: Claim Your Exclusive $30 Discount on Portable Charger - ZDNet</u></a></li>
<li><a href="https://win-lab.techidaily.com/comment-configurer-un-stockage-de-sauvegarde-avec-le-disque-asus-dans-windows-10-methodes-et-astuces/"><u>Comment Configurer Un Stockage De Sauvegarde Avec Le Disque ASUS Dans Windows 10 - Méthodes Et Astuces</u></a></li>
<li><a href="https://win-online.techidaily.com/effortless-data-backup-using-command-line-and-batch-scripting-with-aomei-backupper/"><u>Effortless Data Backup Using Command Line & Batch Scripting with AOMEI Backupper</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expertly-selected-premier-flashlight-picks-zdnet-insights/"><u>Expertly Selected Premier Flashlight Picks | ZDnet Insights</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/green-internet-alert-zdnet-reveals-most-polluting-urls-and-their-environmental-toll-ranked-from-worst-to-less-damaging/"><u>Green Internet Alert: ZDNet Reveals Most Polluting URLs and Their Environmental Toll, Ranked From Worst to Less Damaging</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-the-ecoflow-mobile-power-station-saved-my-household-from-the-latest-energy-crisis-insights-on-widespread-outages/"><u>How the EcoFlow Mobile Power Station Saved My Household From the Latest Energy Crisis - Insights on Widespread Outages</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-13-pro-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 13 Pro without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mike-cannon-brookes-grok-ventures-outmaneuvers-with-11-stake-purchase-in-agl-against-merger-schemes-tech-news/"><u>Mike Cannon-Brookes' Grok Ventures Outmaneuvers with 11% Stake Purchase in AGL Against Merger Schemes | Tech News</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/power-through-any-storm-run-your-lights-for-entire-months-with-the-revolutionary-ecoflow-go-exclusive-tutorial/"><u>Power Through Any Storm: Run Your Lights for Entire Months with the Revolutionary EcoFlow Go! - Exclusive Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-sound-problems-how-to-get-your-mic-working-again-on-windows-11/"><u>Resolving Sound Problems: How to Get Your Mic Working Again on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-huawei-nova-y91-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Huawei Nova Y91 Location | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-rated-smart-home-innovations-in-2cy24-comprehensive-gadget-reviews-by-tech-pros-zdnet/"><u>Top Rated Smart Home Innovations in 2CY24: Comprehensive Gadget Reviews by Tech Pros | ZDNET</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-rated-portable-solar-power-packs-a-comprehensive-review-by-techradar/"><u>Top-Rated Portable Solar Power Packs : A Comprehensive Review by TechRadar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-rapid-download-experience-at-ms-store/"><u>Tricks for Rapid Download Experience at MS Store</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-to-choosing-elite-window-ac-units-of-202n-pros-recommendations-featured-on-zdnet/"><u>Ultimate Guide to Choosing Elite Window AC Units of 202N: Pros' Recommendations | Featured on ZDNET</u></a></li>
</ul></div>

