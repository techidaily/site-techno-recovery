---
title: "Mac Users Rejoice: How To Refresh Your DNS Records Easily"
date: 2024-10-05T19:07:06.506Z
updated: 2024-10-07T20:17:54.500Z
categories:
  - BestProducts
description: "This Article Describes Mac Users Rejoice: How To Refresh Your DNS Records Easily"
excerpt: "This Article Describes Mac Users Rejoice: How To Refresh Your DNS Records Easily"
thumbnail: https://thmb.techidaily.com/1c03d365cac6fcf7e3665fd76e7449b8b7d6ebbb04e310ccec37ca23ea922ee4.jpg
---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037356/7443" target="_top" id="2037356">
  <img src="//a.impactradius-go.com/display-ad/7443-2037356" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037356/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130891/7443" target="_top" id="2130891">
  <img src="//a.impactradius-go.com/display-ad/7443-2130891" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130891/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975836/19272" target="_top" id="1975836">
  <img src="//a.impactradius-go.com/display-ad/19272-1975836" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975836/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863035/11832" target="_top" id="863035">
  <img src="//a.impactradius-go.com/display-ad/11832-863035" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/863035/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Does Flushing DNS Do?

 Each time you access a website in your web browser, the URL you enter is sent to a[DNS server](https://www.lifewire.com/what-is-a-dns-server-2625854) for translation into an[IP address](https://www.lifewire.com/what-is-an-ip-address-2625920) . This information is stored in a cache on your Mac for easy retrieval in the future, hence the term_DNS cache_ .

 When you try to access a website you’ve been to recently, your Mac uses its DNS cache instead of checking with an actual DNS server. The web browser doesn’t have to go through the extra step of communicating with a remote DNS server, which results in less time between entering a website address and the website loading.

 If the local DNS cache is corrupt or outdated, it’s kind of like trying to use an old phone book that's been vandalized. Your web browser checks the cache to find an IP address for the website you’re trying to visit, and it finds either the wrong address or an unusable one. This can slow the process down or prevent websites or specific web page elements, like videos, from loading.

 When you flush your DNS cache, you instruct your Mac to delete its local DNS records. This in turn forces your web browser to check with a DNS server for fresh information. You should always flush your DNS cache after[changing the DNS servers on your Mac](https://www.lifewire.com/network-preference-pane-change-macs-dns-settings-2260394) . It can also be helpful if you’re having connectivity problems.  

 FAQ

* How do I check the DNS cache on a Mac?  
 Open the built-in Console log-viewer app on your Mac and type**any:mdnsresponder** into the search bar. Then, launch Terminal, type in**sudo killall –INFO mDNSResponder** , and press**Enter** or**Return** . Back in the Console app, you can view a list of cached DNS records.
* How do I clear the DNS cache on Windows 10?  
 To[clear the DNS cache on Windows 10](https://www.lifewire.com/flush-and-clear-windows-dns-cache-5095298) , open the Run dialog box, type in**ipconfig /flushdns** , and click**OK** . You can also use the same command in the Windows command prompt if you want more information on the process.
* What is DNS cache poisoning?  
 DNS cache poisoning, also known as DNS spoofing, is when someone deliberately enters false or incorrect information into a DNS cache. After the false information is input, future DNS queries will return incorrect responses and direct users to the wrong websites.

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
<li><a href="https://fox-glue.techidaily.com/new-google-meet-zoom-tips-maximizing-participant-visibility/"><u>[New] Google Meet Zoom Tips Maximizing Participant Visibility</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovative-dvd-production-modern-techniques-for-mac-users/"><u>[New] Innovative DVD Production Modern Techniques for Mac Users</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-mac-methods-for-cleaner-instagram-video-edits-for-2024/"><u>[Updated] Mac Methods for Cleaner Instagram Video Edits for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/a-comprehensible-approach-to-adding-dates-on-youtube-videos/"><u>A Comprehensible Approach to Adding Dates on YouTube Videos</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720062708634-easy-access-to-latest-device-drivers/"><u>Easy Access to Latest Device Drivers!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exclusive-advantages-for-electric-vehicle-drivers-free-parking-spaces-and-carpool-lane-access/"><u>Exclusive Advantages for Electric Vehicle Drivers: Free Parking Spaces & Carpool Lane Access</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-the-features-of-apples-most-recent-ipad-generation/"><u>Exploring the Features of Apple's Most Recent iPad Generation</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-participate-in-a-collaborative-image-collection-on-ios-devices/"><u>How to Participate in a Collaborative Image Collection on iOS Devices</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-perform-a-soft-reset-on-the-iphone-15-efficiently/"><u>How to Perform a Soft Reset on the iPhone 15 Efficiently</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unblemished-visuals-a-buyers-ultimate-guide/"><u>In 2024, Unblemished Visuals A Buyer's Ultimate Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/reducing-motion-illusion-in-vr-environments-for-2024/"><u>Reducing Motion Illusion in VR Environments for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/refresh-your-phone-today-a-step-by-step-walkthrough-to-clear-cache-on-android/"><u>Refresh Your Phone Today: A Step-by-Step Walkthrough to Clear Cache on Android</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/restarting-and-repairing-silent-alexa-devices-effective-methods/"><u>Restarting and Repairing Silent Alexa Devices – Effective Methods</u></a></li>
<li><a href="https://screen-capture.techidaily.com/screencast-essentials-from-basics-to-advanced-tactics-for-2024/"><u>Screencast Essentials From Basics to Advanced Tactics for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-art-of-panoramic-capture-9-techniques-to-perfection-for-2024/"><u>The Art of Panoramic Capture 9 Techniques to Perfection for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/whats-next-for-tech-enthusiasts-oneplus-model-10-release-forecast-price-guess-and-feature-roundup/"><u>What's Next for Tech Enthusiasts: OnePlus Model 10 - Release Forecast, Price Guess, and Feature Roundup</u></a></li>
</ul></div>

