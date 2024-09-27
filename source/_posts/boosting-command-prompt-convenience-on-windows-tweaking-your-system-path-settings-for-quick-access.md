---
title: "Boosting Command Prompt Convenience on Windows: Tweaking Your System PATH Settings for Quick Access"
date: 2024-08-30T13:08:40.982Z
updated: 2024-08-31T13:08:40.982Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/9986a0298b6ed41baf9ff52abd2373f4874f20858ec27b5c29bc07659651b716.jpg
---

## Boosting Command Prompt Convenience on Windows: Tweaking Your System PATH Settings for Quick Access

### Quick Links

* [What Is the Windows System PATH?](https://facebook-record-videos.techidaily.com/updated-harmonizing-youtube-content-a-guide-to-blending-files/)
* [How to Add a Folder to Your PATH](https://fox-cloud.techidaily.com/new-quirky-creations-your-guide-to-no-cost-memes/)

### Key Takeaways

 The PATH tells Windows where it should look for executables, making them accessible via command-line interfaces or scripts. To add a new folder to PATH, navigate to Advanced System Settings > Environment Variables, select PATH, click "Edit" and then "New."

 Have you ever wondered why you can just type ipconfig into a command prompt and it works, but when you want to use a command line program you downloaded you have to navigate to its directory first? Here's how to fix that using the Windows System PATH on Windows 10 and Windows 11.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
##  What Is the Windows System PATH?

 The Windows System PATH tells your PC where it can find specific directories that contain executable files. Ipconfig.exe, for example, is found in the C:\\Windows\\System32 directory, which is a part of the system PATH by default. When you type ipconfig into a Command Prompt, Windows doesn't need to know where that EXE is—it'll check all the folders in its PATH until it finds the right one.

 If you've downloaded a program that uses a command-line interface—like ADB, the [Android Debug Bridge](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/)—you can't just type adb in the Command Prompt or PowerShell to run it, like you can with Windows' built-in commands (e.g.ipconfig). Instead, you have to tell Command Prompt where to find that file, by typing in the full path of the EXE:

C:\Android\platform-tools\adb.exe

 If you don't, you'll get an error message like this.

![ADB is not recognized since it is not on the system PATH.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/adb-error.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In the "System Variables" box, look for a variable called _Path._ Select that and click on the "Edit" button.

 You can modify the PATH for only the current user by changing the PATH variable under "User Variables." It won't affect other users, however. In many cases, it is better and more convenient to add something to the system PATH, so it is universally accessible on your PC.

![Select &quot;PATH&quot; under &quot;System Variables,&quot; then click &quot;Edit.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/system-variables.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
 This process is both easier and less confusing in Windows 10 and Windows 11 than it was in earlier versions of Windows. Once you've clicked the edit button, a new dialog box will appear with each location in the PATH on a separate line. This is a dramatic improvement over the way previous versions of Windows handled PATH locations and makes easy work of adding a new one.

![The current PATH.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/PATH-Stuff.png) 

 First, click the 'new' button, which will add a line at the end of the list. Add your location—"C:\\AndroidSDK" in our example—and hit Enter. Click the "OK" button and you're finished.

 Older versions of Windows required each line end with a semi-colon, but Windows 10 and 11 do not if you use the user interface like we are here. If you use a command-line interface to edit the PATH, you'll still find them there.

![Click &quot;New,&quot; enter the path to ADB, then click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/android-SD.png) 

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The Android Debugging Bridge should now be accessible from any Command Prompt, PowerShell, or Windows Terminal, with no need to specify its directory.

![ADB now works in PowerShell without specifying the path manually.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/adb-on-path.png) 

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
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


