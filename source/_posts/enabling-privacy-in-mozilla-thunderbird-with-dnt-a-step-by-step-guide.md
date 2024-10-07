---
title: Enabling Privacy in Mozilla Thunderbird with DNT - A Step-by-Step Guide
date: 2024-10-06T20:09:29.600Z
updated: 2024-10-07T19:18:20.808Z
tags:
  - work-life
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/681af76a539af0f048301a781d0882774c846a9d/2021/01/08/1795ea35-2ef4-47fb-b2b3-3180851ccac0/istock-1198252560.jpg?width=278&height=156&fit=crop&auto=webp
---

## Enabling Privacy in Mozilla Thunderbird with DNT - A Step-by-Step Guide

![Hands typing on laptop](https://www.zdnet.com/a/img/resize/923bc3f7ed74af6da9d926833686266ae282f75a/2021/01/08/1795ea35-2ef4-47fb-b2b3-3180851ccac0/istock-1198252560.jpg?auto=webp&width=1280)

iStockphoto/Getty Images

In this modern age, it's growing harder and harder to prevent being [tracked online](https://www.zdnet.com/article/your-android-apps-are-tracking-you-heres-how-to-stop-them/). Most often this is used to better target you for advertising. That alone, for many, is an [invasion of privacy](https://www.zdnet.com/article/how-to-boost-your-browsers-privacy-with-duckduckgo-privacy-essentials/). Because of that, several types of software have adopted Do Not Track (DNT).

### More how-tos

* [How to download YouTube videos for free, plus two other methods](https://www.zdnet.com/article/how-to-download-youtube-videos-for-free-plus-two-other-methods/)
* [Wi-Fi problems? Add a wired network to your home without Ethernet cable - here's how](https://www.zdnet.com/article/wi-fi-problems-how-to-add-a-wired-network-to-your-home-without-ethernet-cable/)
* [Wiping a Windows laptop? Here's the safest free way to erase your personal data](https://www.zdnet.com/article/wiping-a-windows-laptop-heres-the-safest-free-way-to-erase-your-personal-data/)
* [How to connect a PS4 controller to a smartphone](https://www.zdnet.com/article/how-to-connect-a-ps4-controller-to-a-smartphone/)

In [web browsers](https://www.zdnet.com/home-and-office/work-life/no-browser-is-perfect-whats-a-user-to-do/), for example, this setting automatically requests that web applications disable tracking for users. Not all web browsers enable that setting by default, but users can always switch it on.

Once enabled, the browser will send the Do Not Track request to websites, analytics companies, ad networks, plug-in providers, and any other service or application that attempts to track your activity.

That option isn't just available to web browsers. Most modern email clients have the ability to render HTML content within emails. Because of this, third parties can track you when your email client renders that HTML email.

**Also:** [**You're definitely not making the most of your password manager**](https://www.zdnet.com/article/youre-definitely-not-making-the-most-of-your-password-manager/)

Again, an invasion of privacy.

Some email clients include a DNT feature. Such is the case with my favorite email client, [Thunderbird](https://www.thunderbird.net/). I want to show you how to enable DNT on Thunderbird so you can prevent those third-party organizations from tracking you via your email.

## A caveat to consider

According to [Avast](https://www.avast.com/c-what-is-do-not-track#:~:text=While%20web%20tracking%20isn%27t,and%20was%20never%20widely%20adopted), in its current form, DNT is not very effective. Why? Because many sites refuse to honor the DNT request. Avast says, "No, Do Not Track is not very effective. Without legislation or some sort of meaningful arrangement behind it, Do Not Track has no teeth. Even if all the browsers made it possible to include a Do Not Track option, that doesn't mean that companies that want to track you will comply."

Back in 2012, ZDNET posted a piece calling [DNT a complete failure](https://www.zdnet.com/article/why-do-not-track-is-worse-than-a-miserable-failure/). Again, the failure is because DNT is a voluntary standard and requires good faith from third parties. Unfortunately, most websites aren't honoring those requests. Why? So they can track you. Another problem, according to Ed Bott's piece is, "Two big associations, the Interactive Advertising Bureau and the Digital Advertising Alliance, represent 90% of advertisers. Downey says those big groups have devised their own interpretation of Do Not Track. When the servers controlled by those big companies encounter a DNT=1 header, says Downey, "They have said they will stop serving targeted ads but will still collect and store and monetize data.""

In other words, we need legislation to force third parties to comply with DNT or it will never work properly.

That being said, let's enable it on Thunderbird so that eventually (when businesses are forced to comply with DNT requests) you'll be protected.

## How to add Do Not Track to Thunderbird (and why you should)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016170/19272" target="_top" id="2016170">
  <img src="//a.impactradius-go.com/display-ad/19272-2016170" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016170/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Requirements

The only thing you'll need to make this work is a running instance of the Thunderbird email client. Thunderbird is supported on Linux, MacOS, and Windows, and it doesn't matter which operating system you use, as the feature is the same across all platforms. I'll be demonstrating on Thunderbird version 102.5.0, running on [Pop!\_OS Linux](https://www.zdnet.com/article/pop-os-might-have-a-complicated-name-but-it-makes-using-linux-so-easy/).

With that said, let's get this feature enabled.

## 1\. Open Thunderbird and access the menu

Open your Thunderbird email client and click the three-horizontal-line menu button in the top right corner of the main window.

Accessing the Thunderbird menu is but a click away.

Jack Wallen/ZDNET

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Open Settings

From the pop-up menu, click Settings.

Make sure to click Settings and not Account Settings.

Jack Wallen/ZDNET

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Enable DNT

In the Privacy & Security section, under Web Content, click the checkbox for **Send websites a "Do Not Track" signal that you don't want to be tracked**.

**Also:** [**How to create message filters in Thunderbird to keep your inbox organized**](https://www.zdnet.com/article/how-to-create-message-filters-in-thunderbird-to-keep-your-inbox-organized/)

Once you've done that, you can close the settings window and trust that Thunderbird is sending the DNT request.

Enabling DNT in Thunderbird's Settings window.

Jack Wallen/ZDNET

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006928/19272" target="_top" id="2006928">
  <img src="//a.impactradius-go.com/display-ad/19272-2006928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Another handy tip

By default, Thunderbird is configured not to display remote content (HTML email). I would highly recommend you keep that setting as is and only allow Thunderbird to show remote content for emails from people or companies you can absolutely trust. 

**Also:** [**How to encrypt email on Thunderbird (and why you should)**](https://www.zdnet.com/article/how-to-encrypt-email-in-thunderbird-and-why-you-should/)

Even then (especially with HTML email from business), unless you have DNT enabled, the likelihood of you being tracked is high. In other words, enable DNT or your privacy is at risk.

#### Open Source

[5 Linux commands you must know to keep your device running smoothly](https://www.zdnet.com/article/5-linux-commands-you-must-know-to-keep-your-device-running-smoothly/ "5 Linux commands you must know to keep your device running smoothly")

[The best Linux laptops you can buy: Expert tested](https://www.zdnet.com/article/best-linux-laptop/ "The best Linux laptops you can buy: Expert tested")

[The best Linux distros for beginners](https://www.zdnet.com/article/best-linux-desktops-for-beginners/ "The best Linux distros for beginners")

[My 5 favorite Linux text editors (and why you should be using one)](https://www.zdnet.com/article/my-favorite-linux-text-editors-and-why-you-should-be-using-one/ "My 5 favorite Linux text editors (and why you should be using one)")

* [5 Linux commands you must know to keep your device running smoothly](https://www.zdnet.com/article/5-linux-commands-you-must-know-to-keep-your-device-running-smoothly/ "5 Linux commands you must know to keep your device running smoothly")
* [The best Linux laptops you can buy: Expert tested](https://www.zdnet.com/article/best-linux-laptop/ "The best Linux laptops you can buy: Expert tested")
* [The best Linux distros for beginners](https://www.zdnet.com/article/best-linux-desktops-for-beginners/ "The best Linux distros for beginners")
* [My 5 favorite Linux text editors (and why you should be using one)](https://www.zdnet.com/article/my-favorite-linux-text-editors-and-why-you-should-be-using-one/ "My 5 favorite Linux text editors (and why you should be using one)")

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
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-dive-into-filmoras-certified-creative-program/"><u>[Updated] 2024 Approved Dive Into Filmora’s Certified Creative Program</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-premiere-pro-streamline-for-online-video-uploads/"><u>[Updated] Premiere Pro Streamline for Online Video Uploads</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effortlessly-enhance-sound-quality-by-connecting-assorted-bluetooth-speakers-to-one-device-a-step-by-step-guide/"><u>Effortlessly Enhance Sound Quality by Connecting Assorted Bluetooth Speakers to One Device: A Step-by-Step Guide</u></a></li>
<li><a href="https://buynow-help.techidaily.com/experience-cutting-edge-technology-without-overspending-on-an-lg-24lh4830-smart-tv/"><u>Experience Cutting-Edge Technology Without Overspending on an LG 24LH4830 Smart TV</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Poco C51 | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722893699785-master-the-art-of-awkward-potion-creation-in-minecraft-tutorial-inside/"><u>Master the Art of Awkward Potion Creation in Minecraft - Tutorial Inside</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-disk-checks-a-step-by-step-guide-to-running-chkdsk-on-windows/"><u>Mastering Disk Checks: A Step-by-Step Guide to Running Chkdsk on Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/step-by-step-guide-to-new-amd-drivers-in-w11/"><u>Step-by-Step Guide to New AMD Drivers in W11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-list-best-fitness-tracking-apps-for-your-routine/"><u>The Ultimate List: Best Fitness Tracking Apps for Your Routine</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unveiling-types-and-methods-for-hand-detection-systems/"><u>Unveiling Types and Methods for Hand Detection Systems</u></a></li>
<li><a href="https://techidaily.com/windows-11-microsoft-update-download-and-install-cumulative-patch-kb5040442/"><u>Windows 11 Microsoft Update: Download and Install Cumulative Patch KB5040442</u></a></li>
</ul></div>

