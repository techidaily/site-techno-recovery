---
title: "Mastering Secure Shell (SSH) on Chromebooks: A Guide with ChromeOS's Built-In SSH Client"
date: 2024-10-20T19:42:09.658Z
updated: 2024-10-25T02:01:45.700Z
tags:
  - google
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3b1acf72418bcbc32cbafc2ecf801ef760b09fcf6908ac7624af651ae9d18172.jpg
---

## Mastering Secure Shell (SSH) on Chromebooks: A Guide with ChromeOS's Built-In SSH Client

![Lenovo Chromebook on a table.](https://www.zdnet.com/a/img/resize/4d33e5a80bd88251cc7d5d6adc2b62efe6331ed5/2022/09/13/e077d2a9-647a-4e73-bdea-23e52c1cb65d/lenovo-chromebook-duet.jpg?auto=webp&width=1280)

CNET

Chrome OS has become quite the platform for users of all types. Whether you're a typical user who spends most of your time within an operating system browsing social media, writing ad hoc papers, and shopping for the latest trends, or if you're an administrator who has to work on remote machines throughout the day, Chrome OS has you covered.

One tool that I use quite a bit comes by way of [Linux](https://www.zdnet.com/topic/linux/). If you've already [enabled Linux](https://www.zdnet.com/article/how-to-enable-linux-on-your-chromebook-and-why-you-should/), you understand that Chrome OS is much more than just a web browser. With Linux support enabled, you can install quite a large number of applications to turn Chrome OS into a much more traditional OS.

**Also:** [How I revived three ancient computers with ChromeOS Flex](https://www.zdnet.com/article/how-i-revived-three-ancient-laptops-with-chrome-os-flex/)

## Adding an SSH connection to the Linux terminal app

### **ZDNET** Recommends

[The best Chromebooks in 2022 These Chromebook laptops feature low prices and long battery lives.  Read now](https://www.zdnet.com/article/best-chromebook-laptop/)

Along the ride with Linux, comes a terminal tool that is much more than a means to a command-line end. With the Linux terminal in Chrome OS, you also get a convenient Secure Shell connection manager.

Let me show you how it works.

### Requirements

The only thing you need to enjoy this handy SSH management tool is a [Chromebook](https://shop-links.co/link/?url=https%3A%2F%2Fwww.bestbuy.com%2Fsite%2Fall-laptops%2Fchromebooks%2Fpcmcat244900050010.c%3Fid%3Dpcmcat244900050010&publisher_slug=itechdaily19598&exclusive=1) with Linux support enabled. Of course, you'll also need a remote machine that allows SSH connections. But that's it. Let's get to work.

## 1\. Open the terminal

Open the Launcher at the bottom left corner of your Chrome OS desktop. Locate and click the Terminal app.

Launching the Terminal app from the Chrome OS launcher.

Image: Jack Wallen

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148649/16836" target="_top" id="2148649">
  <img src="//a.impactradius-go.com/display-ad/16836-2148649" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148649/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Add an SSH entry

From the terminal app, click Add SSH.

The Terminal app makes it easy to manage your SSH connections.

Image: Jack Wallen

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526">
  <img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Enter the SSH details

In the resulting popup, type the details for your new SSH connection in the command section, which will look something like this:

_ssh USERNAME@SERVER_

Where USERNAME is the username on the remote server and SERVER is the IP address of the server. For example, the command might look like this:

_ssh zdnet@192.168.1.100_

If your remote server uses a different port for SSH, that command might look something like this:

_ssh zdnet@192.168.1.100 -p 2022_

Don't worry about either the Identity or SSH relay server options sections. Once you've configured the command, click Save and your new entry will now be listed under the SSH section of the terminal app.

Entering the SSH details for a new remote connection.

Image: Jack Wallen

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036496/19272" target="_top" id="2036496">
  <img src="//a.impactradius-go.com/display-ad/19272-2036496" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036496/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Using your new SSH connection

## 1\. Select the connection to be used

Click on the remote server you want to connect to from under the SSH section in the terminal app.

## 2\. Accept the fingerprint

If this is the first time connecting to a remote server from the Chrome OS Linux terminal, you'll be prompted to accept the fingerprint. When prompted, type yes and hit Enter on your keyboard.

Accepting the SSH key fingerprint is required to make a connection.

Image: Jack Wallen

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Type the user password

You will then be prompted to type the password for the remote user. Upon successful authentication, you'll find yourself in an SSH session on the remote machine, where you can then take care of whatever admin tasks you need.

Type your user password for the remote connection and you're in.

Image: Jack Wallen

And that, my admin friends, is all there is to manage your SSH connections from within Chrome OS. 

#### See also

[How to replace Windows with Linux Mint on your PC](https://www.zdnet.com/article/how-to-replace-windows-with-linux-mint-on-your-pc/ "How to replace Windows with Linux Mint on your PC")

[5 best Linux commands for troubleshooting problems (and how I use them)](https://www.zdnet.com/article/5-best-linux-commands-for-troubleshooting-problems-and-how-i-use-them/ "5 best Linux commands for troubleshooting problems (and how I use them)")

[5 reasons why Pop!\_OS is this Linux pro's favorite distro](https://www.zdnet.com/article/5-reasons-why-pop-os-is-this-linux-pros-favorite-distro/ "5 reasons why Pop!_OS is this Linux pro's favorite distro")

[5 best open-source email clients for Linux (and why Geary is my go-to)](https://www.zdnet.com/article/5-best-open-source-email-clients-for-linux-and-why-geary-is-my-go-to/ "5 best open-source email clients for Linux (and why Geary is my go-to)")

* [How to replace Windows with Linux Mint on your PC](https://www.zdnet.com/article/how-to-replace-windows-with-linux-mint-on-your-pc/ "How to replace Windows with Linux Mint on your PC")
* [5 best Linux commands for troubleshooting problems (and how I use them)](https://www.zdnet.com/article/5-best-linux-commands-for-troubleshooting-problems-and-how-i-use-them/ "5 best Linux commands for troubleshooting problems (and how I use them)")
* [5 reasons why Pop!\_OS is this Linux pro's favorite distro](https://www.zdnet.com/article/5-reasons-why-pop-os-is-this-linux-pros-favorite-distro/ "5 reasons why Pop!_OS is this Linux pro's favorite distro")
* [5 best open-source email clients for Linux (and why Geary is my go-to)](https://www.zdnet.com/article/5-best-open-source-email-clients-for-linux-and-why-geary-is-my-go-to/ "5 best open-source email clients for Linux (and why Geary is my go-to)")

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
<li><a href="https://twitter-clips.techidaily.com/updated-how-to-seamlessly-share-tweets-as-video-on-instagram-for-2024/"><u>[Updated] How To Seamlessly Share Tweets as Video on Instagram for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-motorola-moto-g34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/essential-tips-reinstalling-drivers-in-win11-and-older/"><u>Essential Tips: Reinstalling Drivers in Win11 & Older</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-xbox-app-working-again-on-your-windows-laptop/"><u>Get the Xbox App Working Again on Your Windows Laptop</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-14-pro-passcode-without-computer-by-drfone-ios/"><u>How to Unlock Apple iPhone 14 Pro Passcode without Computer?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/mac-users-easily-retrieve-deleting-memories-from-your-iphone-with-our-top-ranked-recovery-software/"><u>Mac Users! Easily Retrieve Deleting Memories From Your iPhone with Our Top-Ranked Recovery Software</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/officially-unveiled-full-roster-of-ps-vr2-titles-announced/"><u>Officially Unveiled: Full Roster of PS VR2 Titles Announced</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-d3dx933dll-not-detected-issues-a-comprehensive-guide/"><u>Resolving d3dx9_33.dll Not Detected Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-friend-code-to-fun-on-ps5-easy-sharing-tips-for-gamers-of-all-levels/"><u>The Friend Code to Fun on PS5: Easy Sharing Tips for Gamers of All Levels</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-meaning-of-microsofts-monthly-maintenance-day-patch-tuesday-explained/"><u>The Meaning of Microsoft's Monthly Maintenance Day - Patch Tuesday Explained</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-password-cracking-tools-for-nokia-xr21-by-drfone-android/"><u>Top 10 Password Cracking Tools For Nokia XR21</u></a></li>
</ul></div>

