---
title: Easy Guide to Updating to the Newest FreeLibreOffice on Linux Systems
date: 2024-09-19 22:58:13
updated: 2024-09-20 10:37:52
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

## 1\. Download the latest version of LibreOffice

The first thing to do is to download the latest version of LibreOffice. Open your web browser, head over to the [LibreOffice download page](https://www.libreoffice.org/download/download-libreoffice/), and download the RPM version of the software. Make sure to save the file in your Downloads folder.

Make sure to download the RPM version for RHEL-based distributions and the DEB version for Ubuntu-based distributions.

Jack Wallen/ZDNET

## 2\. Unpack the file

Once the download is finished, you must open your file manager and navigate to the Downloads folder. Right-click the file that ends with .tar.gz. From the popup menu, select Extract. This will create a new directory that starts with LibreOffice. Change into that newly-created directory and then change into the child directory within (that also starts with LibreOffice).

Extracting the downloaded LibreOffice file in the GNOME file manager.

Jack Wallen/ZDNET

## 3\. Open a terminal and install the software

Within the new directory, you'll find yet another directory, named RPMS. Change into that directory. Once inside that directory, right-click on any empty spot and select Open in Terminal from the popup menu. Once the terminal opens, issue the following command to install the software:

sudo rpm -i *.rpm

Once the command completes, you can close the terminal and delete both the downloaded .tar.gz file and the LibreOffice folder in Downloads. Search for the software in your desktop menu and you should see LibreOffice 7.5 listed.

A successful LibreOffice installation.

Jack Wallen/ZDNET

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
