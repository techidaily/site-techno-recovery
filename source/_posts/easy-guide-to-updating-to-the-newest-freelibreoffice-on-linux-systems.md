---
title: Easy Guide to Updating to the Newest FreeLibreOffice on Linux Systems
date: 2024-09-30T18:42:50.597Z
updated: 2024-10-07T19:10:26.040Z
tags:
  - work-life
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/8ea608874d8a9d9101001382e1cc9cd2f9e097d4/2023/06/12/54ab6084-d4ec-463d-b9e0-fcf3b839cf96/gettyimages-1416048929.jpg?width=278&height=156&fit=crop&auto=webp
---

## Easy Guide to Updating to the Newest FreeLibreOffice on Linux Systems

![gettyimages-1416048929](https://www.zdnet.com/a/img/resize/3b26eb7c0e2a75ee2dc929b2e839740646de79a3/2023/06/12/54ab6084-d4ec-463d-b9e0-fcf3b839cf96/gettyimages-1416048929.jpg?auto=webp&width=1280)

If LibreOffice is your tool of choice, you don't have to worry that it'll no longer be available to your chosen operating system.

PeopleImages/Getty Images

Soon, users of RHEL-based Linux distributions (such as Fedora, AlmaLinux, and Rocky Linux) will find an important piece of software missing from the official repositories…the LibreOffice office suite.

There's no need to panic, as this is not an end-of-the-world scenario (far from it). Not only is this not cataclysmic, but there will also always be the means to install LibreOffice on your favorite RHEL-based operating system. On top of that, there are other office suites you can install (such as [WPS Office](https://tools.techidaily.com/wps/products/) and [Softmaker Office](https://www.softmaker.de/softmaker-office)).

**Also:** [**How to deploy a cloud-based office suite to your home network**](https://www.zdnet.com/article/how-to-deploy-a-cloud-based-office-suite-to-your-home-network/)

However, if [LibreOffice is your tool of choice](https://www.zdnet.com/article/how-to-add-fields-to-a-libreoffice-document/), you don't have to worry that it'll no longer be available to your chosen desktop (or server) operating system.

I'm going to show you how easy it is to install the latest version of LibreOffice on your desktop. The only caveat to this method is you don't get automatic updates and have to go through the process any time you want to upgrade to the latest version. Even so, that is only a matter of repeating the steps with the latest download.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

With that said, let's get to the steps.

## How to install the latest version of LibreOffice on Fedora Linux

**What you'll need:** You'll only need three things for this - a running instance of an RHEL-based distribution (I'll demonstrate with Fedora 38), a user with sudo privileges, and an internet connection. That's it. Let's get to work.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Download the latest version of LibreOffice

The first thing to do is to download the latest version of LibreOffice. Open your web browser, head over to the [LibreOffice download page](https://www.libreoffice.org/download/download-libreoffice/), and download the RPM version of the software. Make sure to save the file in your Downloads folder.

Make sure to download the RPM version for RHEL-based distributions and the DEB version for Ubuntu-based distributions.

Jack Wallen/ZDNET

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098704/14409" target="_top" id="2098704">
  <img src="//a.impactradius-go.com/display-ad/14409-2098704" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098704/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Unpack the file

Once the download is finished, you must open your file manager and navigate to the Downloads folder. Right-click the file that ends with .tar.gz. From the popup menu, select Extract. This will create a new directory that starts with LibreOffice. Change into that newly-created directory and then change into the child directory within (that also starts with LibreOffice).

Extracting the downloaded LibreOffice file in the GNOME file manager.

Jack Wallen/ZDNET

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918703/19272" target="_top" id="1918703">
  <img src="//a.impactradius-go.com/display-ad/19272-1918703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918703/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Open a terminal and install the software

Within the new directory, you'll find yet another directory, named RPMS. Change into that directory. Once inside that directory, right-click on any empty spot and select Open in Terminal from the popup menu. Once the terminal opens, issue the following command to install the software:

sudo rpm -i *.rpm

Once the command completes, you can close the terminal and delete both the downloaded .tar.gz file and the LibreOffice folder in Downloads. Search for the software in your desktop menu and you should see LibreOffice 7.5 listed.

A successful LibreOffice installation.

Jack Wallen/ZDNET

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100538/7443" target="_top" id="2100538">
  <img src="//a.impactradius-go.com/display-ad/7443-2100538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Installing on Ubuntu

If you use a Ubuntu-based distribution, the process is the same with only two minor differences. First, you must download the DEB version of LibreOffice. The second difference is, once you've extracted the contents of the downloaded file, the installation command for a Ubuntu-based distribution will be:

sudo deb -i *.rpm

And that's all there is to installing the latest version of LibreOffice on either an RHEL- or Ubuntu-based Linux distribution. Once Fedora no longer ships with LibreOffice, you'll be able to easily install the software, so you don't miss out on creating/editing documents, spreadsheets, presentations, and more.

**Also:** [**How to create a LibreOffice template**](https://www.zdnet.com/home-and-office/work-life/how-to-create-a-libreoffice-template/)

#### Jack Wallen: Here's how to...

[How to get true window snapping in MacOS](https://www.zdnet.com/article/how-to-get-true-window-snapping-in-macos/ "How to get true window snapping in MacOS")

[The AGM 5 Pro might be the loudest Android phone ever](https://www.zdnet.com/article/the-agm-5-pro-might-be-the-loudest-android-phone-ever/ "The AGM 5 Pro might be the loudest Android phone ever")

[Nitrux 2.4 Linux distro shows promise](https://www.zdnet.com/article/nitrux-2-4-linux-distribution-shows-promise-but-seems-rough-around-the-edges/ "Nitrux 2.4 Linux distro shows promise")

[Tired of being tracked online? DuckDuckGo's Email Protection can help](https://www.zdnet.com/article/tired-of-being-tracked-online-duckduckgos-email-protection-can-help/ "Tired of being tracked online? DuckDuckGo's Email Protection can help")

* [How to get true window snapping in MacOS](https://www.zdnet.com/article/how-to-get-true-window-snapping-in-macos/ "How to get true window snapping in MacOS")
* [The AGM 5 Pro might be the loudest Android phone ever](https://www.zdnet.com/article/the-agm-5-pro-might-be-the-loudest-android-phone-ever/ "The AGM 5 Pro might be the loudest Android phone ever")
* [Nitrux 2.4 Linux distro shows promise](https://www.zdnet.com/article/nitrux-2-4-linux-distribution-shows-promise-but-seems-rough-around-the-edges/ "Nitrux 2.4 Linux distro shows promise")
* [Tired of being tracked online? DuckDuckGo's Email Protection can help](https://www.zdnet.com/article/tired-of-being-tracked-online-duckduckgos-email-protection-can-help/ "Tired of being tracked online? DuckDuckGo's Email Protection can help")

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-achieving-a-noiseless-presence-on-social-video-platforms/"><u>[New] 2024 Approved Achieving a Noiseless Presence on Social Video Platforms</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-enhance-your-content-filmmaking-for-youtube-trailers-with-filmora/"><u>[New] In 2024, Enhance Your Content Filmmaking for YouTube Trailers with Filmora</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-unlock-high-end-visuals-a-practical-guide-for-sdr-to-hdr-transition/"><u>[New] In 2024, Unlock High-End Visuals A Practical Guide for SDR to HDR Transition</u></a></li>
<li><a href="https://blog-min.techidaily.com/1-stealthy-guide-secretly-recording-video-chats-on-snapchat/"><u>1. Stealthy Guide: Secretly Recording Video Chats on Snapchat</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-deciphering-the-block-code-on-snapchat/"><u>2024 Approved Deciphering the Block Code on Snapchat</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/does-the-iphone-13-offer-protection-against-accidental-dunking/"><u>Does the iPhone 13 Offer Protection Against Accidental Dunking?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-ideal-8-desktop-images-to-personalize-your-mbp/"><u>In 2024, Ideal 8 Desktop Images to Personalize Your MBP</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/protecting-your-inbox-the-ultimate-how-to-for-turning-on-google-mail-2fa/"><u>Protecting Your Inbox: The Ultimate How-To for Turning On Google Mail 2FA</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/secure-your-digital-life-with-these-amoulti-faceted-free-backup-programs-evaluated-for-you/"><u>Secure Your Digital Life with These Amo(u)lti-Faceted Free Backup Programs, Evaluated for You</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/silencing-telemarketers-tips-to-halt-unwanted-texts-on-ios-devices/"><u>Silencing Telemarketers: Tips to Halt Unwanted Texts on iOS Devices</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722889029297-tackling-troublesome-subwoofer-whirring-expert-fixes-revealed/"><u>Tackling Troublesome Subwoofer Whirring: Expert Fixes Revealed</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722880912678-upcoming-touchscreen-macbook-revealed-learn-about-the-projected-costs-and-launch-timeline/"><u>Upcoming Touchscreen MacBook Revealed - Learn About the Projected Costs & Launch Timeline!</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-realme-narzo-60-5g-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Realme Narzo 60 5G? Here is How | Dr.fone</u></a></li>
</ul></div>

