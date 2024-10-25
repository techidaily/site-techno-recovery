---
title: How to Eliminate Mac Trackpad Acceleration Effortlessly
date: 2024-10-21T05:44:22.638Z
updated: 2024-10-24T22:52:08.737Z
categories:
  - BestProducts
description: This Article Describes How to Eliminate Mac Trackpad Acceleration Effortlessly
excerpt: This Article Describes How to Eliminate Mac Trackpad Acceleration Effortlessly
thumbnail: https://www.lifewire.com/thmb/NGt852YzCkbbBejPpQDkxI8KJG4=/540x405/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-turn-off-mouse-acceleration-on-mac-6503047-983b1d5393fe4ff599fb1bcb3de8b109.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1880944/19272" target="_top" id="1880944">
  <img src="//a.impactradius-go.com/display-ad/19272-1880944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880944/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-the-secret-sauce-for-stellar-telegram-campaigns-for-2024/"><u>[New] The Secret Sauce for Stellar Telegram Campaigns for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/a-comprehensive-guide-to-understanding-smartwatch-capabilities/"><u>A Comprehensive Guide to Understanding Smartwatch Capabilities</u></a></li>
<li><a href="https://sound-issues.techidaily.com/are-auditory-hallucinations-a-sign-of-mental-illness/"><u>Are Auditory Hallucinations a Sign of Mental Illness?</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722964711297-latest-brother-mfc-7860dw-drivers-for-windows-free-downloads-available/"><u>Latest Brother MFC- 7860DW Drivers for Windows - Free Downloads Available</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/quick-tips-mastering-the-art-of-screenshots-using-logitech-keys/"><u>Quick Tips: Mastering the Art of Screenshots Using Logitech Keys</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/resolving-onedrive-video-playback-problems-a-guide-to-five-easy-solutions/"><u>Resolving OneDrive Video Playback Problems: A Guide to Five Easy Solutions</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/secrets-of-asmr-success-with-top-recorder-mics/"><u>Secrets of ASMR Success with Top Recorder Mics</u></a></li>
<li><a href="https://os-tips.techidaily.com/step-by-step-tutorial-activating-and-using-smart-lock-functionality-in-android-systems/"><u>Step-by-Step Tutorial: Activating and Using Smart Lock Functionality in Android Systems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/steps-to-troubleshoot-and-fix-missing-mfc42dll-file-issues/"><u>Steps to Troubleshoot and Fix Missing mfc42.dll File Issues</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/strategies-for-dealing-with-an-unavailable-msodll-error-message/"><u>Strategies for Dealing with an Unavailable Mso.dll Error Message</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/surviving-rain-or-shine-top-rated-watershield-phone-sleeves-of-the-current-era/"><u>Surviving Rain or Shine: Top Rated Watershield Phone Sleeves of the Current Era</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-role-of-telecommunication-compannies-in-connecting-calls-and-data/"><u>The Role of Telecommunication Compannies in Connecting Calls and Data</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-to-attracting-followers-on-instagram/"><u>The Ultimate Guide to Attracting Followers on Instagram</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-oppo-a59-5g-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Oppo A59 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-personalization-features-coloring-the-taskbar-on-windows-11/"><u>Unlocking Personalization Features: Coloring the Taskbar on Windows 11</u></a></li>
</ul></div>

