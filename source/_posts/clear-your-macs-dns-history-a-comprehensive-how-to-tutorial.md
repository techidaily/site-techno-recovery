---
title: "Clear Your Mac's DNS History: A Comprehensive How-To Tutorial"
date: 2024-12-15T23:56:48.947Z
updated: 2024-12-17T03:59:25.956Z
categories:
  - BestProducts
description: "This Article Describes Clear Your Mac's DNS History: A Comprehensive How-To Tutorial"
excerpt: "This Article Describes Clear Your Mac's DNS History: A Comprehensive How-To Tutorial"
thumbnail: https://thmb.techidaily.com/50b8c0240239aa64db52b1f5d6c9798f04334cb3acf289ccfe4f5fa8ce22d8a0.jpg
---

## Clear Your Mac's DNS History: A Comprehensive How-To Tutorial
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-info.techidaily.com/new-cutting-edge-video-assemblers-iphone-and-androids-best/"><u>[New] Cutting-Edge Video Assemblers IPhone & Android's Best</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-delving-into-t-series-revenue-generation-on-video-platforms-for-2024/"><u>[New] Delving Into T-Series' Revenue Generation on Video Platforms for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-algorithm-advantage-tips-for-achieving-instagram-video-fame/"><u>[New] In 2024, The Algorithm Advantage Tips for Achieving Instagram Video Fame</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-top-20-iconic-anime-theme-melodies-ever/"><u>[Updated] 2024 Approved Top 20 Iconic Anime Theme Melodies Ever</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-guide-to-writing-enthralling-videography-content/"><u>[Updated] Guide to Writing Enthralling Videography Content</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-conquering-facebook-audiences-live-stream-excellence-with-wirecast/"><u>2024 Approved Conquering Facebook Audiences Live Stream Excellence with Wirecast</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/achieving-top-ranking-visibility-on-apple-tv-channels/"><u>Achieving Top Ranking Visibility on Apple TV Channels</u></a></li>
<li><a href="https://win-updates.techidaily.com/easy-steps-to-restore-accidentally-deleted-files-on-your-windows-10-pc/"><u>Easy Steps to Restore Accidentally Deleted Files on Your Windows 10 PC</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-tips-on-deleting-your-pcs-windows-recovery-section/"><u>Expert Tips on Deleting Your PC's Windows Recovery Section</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-learning-how-to-track-opened-messages-in-gmail/"><u>Guide: Learning How to Track Opened Messages in Gmail</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-visionary-software-solutions-for-virtual-meetings/"><u>In 2024, Visionary Software Solutions for Virtual Meetings</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/inside-espnpluss-world-class-streaming-service-features-and-functionality-explained/"><u>Inside ESPN+'s World-Class Streaming Service: Features and Functionality Explained</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/spotify-mastery-the-ultimate-tutorial-for-blending-multiple-playlists-into-one/"><u>Spotify Mastery: The Ultimate Tutorial for Blending Multiple Playlists Into One</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722899018720-step-by-step-fix-for-stop-code-0x0000007b-no-more-blue-screen-woes/"><u>Step-by-Step Fix for Stop Code 0X0000007B – No More Blue Screen Woes</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/step-by-step-guide-watching-vob-movies-on-macos-air-pro-imac/"><u>Step-by-Step Guide: Watching VOB Movies on macOS (Air, Pro, iMac)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-how-to-on-reviving-a-disabled-snapchat-username/"><u>The Ultimate How-To on Reviving a Disabled Snapchat Username</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-80s-cinema-hits-essential-movies-from-the-decade-to-stream-today/"><u>Top 80S Cinema Hits: Essential Movies From the Decade to Stream Today</u></a></li>
<li><a href="https://win-help.techidaily.com/transform-static-chm-documents-into-interactive-ebooks-with-tables-of-contents-using-flipbuilder/"><u>Transform Static CHM Documents Into Interactive Ebooks with Tables of Contents Using FlipBuilder</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-list-of-gmails-fastest-typing-tricks-discover-the-top-30-shortcuts/"><u>Ultimate List of Gmail's Fastest Typing Tricks: Discover the Top 30 Shortcuts</u></a></li>
</ul></div>

