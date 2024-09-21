---
title: The Ins and Outs of Changing Your IP Address – Pros, Cons, and Timely Strategies Explored by ZDNET
date: 2024-09-19 12:49:51
updated: 2024-09-20 11:25:51
tags:
  - vpn
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/e4de47efa18b0a8b6cc6392c97126d2a7988c8c7/2022/12/21/6b950ba2-6cd7-4e61-a2f3-6577126faa48/ip-address-scrabble.jpg?width=278&height=156&fit=crop&auto=webp
---

## The Ins and Outs of Changing Your IP Address – Pros, Cons, and Timely Strategies Explored by ZDNET

![Cat5 ethernet cable](https://www.zdnet.com/a/img/resize/8d6e7880e17466cf8ef4e0ad59c77ebd0fc72fde/2024/04/22/54f4b6c8-1c32-4f6f-a0b3-f75008840c2e/ethernethero.jpg?auto=webp&width=1280)

Jack Wallen/ZDNET

Security and privacy have been hot topics for a long time (and that's not going to change any time soon). One means of achieving privacy on the internet is to either change or obfuscate your IP address, so evildoers and/or third parties aren't able to track you or keep a history of your browsing traffic.

**Also: [The best VPN services of 2024](https://www.zdnet.com/article/best-vpn/)**

Changing your IP address might sound like a task that requires a computer science degree -- but it's not. It's easier than you think. I want to show you how you can accomplish this without a struggle.

Before we get started, some explanation is in order. 

## What is an IP address? 

An IP address is a series of numbers (in the form 192.168.1.100) assigned to every device connected to a network that serves to identify a host/device, allows the devices to send and receive data, and determines the approximate geolocation of a device. Think of an IP address like the address of your home. With that number and street name, other people can find where you live. Without either piece of that puzzle, it would be incredibly challenging to locate your home (for those who've never been there). 

**Also: [Do you need antivirus on Linux?](https://www.zdnet.com/article/do-you-need-antivirus-on-linux/)**

There are two types of IP addresses: IPv4 and IPv6\. IPv4 is the most widely used because of its simplicity. IPv6 addresses are longer and more complicated and look like this: 2345:0425:2CA1:0000:0000:0567:5673:23b5\. IP addresses can be dynamic (assigned to a device by a router) or static (manually assigned by a user or administrator). Static IP addresses remain constant, whereas dynamic addresses automatically change at certain intervals. Without IP addresses, the internet would fail to function.

## Different IP addresses

One of the first things to understand is the difference between an internal and external IP address. On your home network, you have one external IP address (which is assigned to the modem/router your service provider gave you). This IP address is what you see if you open a browser and go to [What Is My IP Address](https://whatismyipaddress.com). 

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

This address is the one seen by the outside world -- and it's one you cannot change _permanently_. However, you can make it _appear_ to be different from what it is. Why would you want to do that? Changing the IP address as seen by the outside world makes it harder for others to track you, especially if you change it randomly. Perhaps you need to transmit sensitive data and you want the IP address to appear as though it's in a different location -- even a different country.

**Also: [5 ways to improve your Chrome browser's security](https://www.zdnet.com/article/5-ways-to-improve-your-chrome-browsers-security-and-why-you-should/)**

On the other hand, you have several _internal_ IP addresses -- the addresses assigned by your router \\to the various devices on your network (desktops, laptops, phones, tablets, TVs, etc.). You can change those addresses manually. If you have the skill (and the ability to access your router's configuration window), you can even change the IP address scheme from something like 192.168.1.0 to 10.0.1.0\. 

Changing your internal IP address isn't nearly as important as how your device is seen by the outside world via your _external_ IP address. Why would you want to change an internal IP address? In a word, convenience. Here's a personal example: I have a Samba share on my network and I want to ensure that this machine has an IP address that I can easily remember _and_ an address that won't ever change. 

A caution is in order: It's not always a good idea to change these internal IP addresses. There's a little thing called an IP address conflict, which happens when more than one device on a network has the same address. When this happens, a device might have difficulty accessing the internet or it could cause slowdowns on your network.

**Also: [What are passkeys? Experience the life-changing magic of going passwordless](https://www.zdnet.com/article/passkeys-what-are-they-and-how-to-get-started/)**

Your internal IP addresses are assigned by your router. Unless you configure your router manually to only assign from a specific pool of addresses (say 192.168.1.1-192.168.1.50) and then only configure manual addresses from 192.168.1.51 and up, you might run into IP address conflicts. To that end, it's best to only change internal IP addresses if you know what you're doing. 

So, read on!

## How to change your internal IP address manually

Here are the steps for different operating systems.

## Linux

How you do this will depend on your desktop environment, so I'll walk you through how it's done on the GNOME desktop environment (which will be similar to other desktops) :

1. Open the Settings app.
2. Locate Network.
3. Click the gear icon associated with either Wired or Wireless.
4. Select the IPv4 tab.
5. Click Manual.
6. Fill out the necessary information (Address, Netmask, Gateway, DNS) and click Apply.

## MacOS

1. Open System Settings.
2. Go to Wi-Fi (if connected wirelessly).
3. Locate your current wireless connection and click Details.
4. Click TCP/IP.
5. Select Manually from the Configure IPv4 drop-down.
6. Fill out the necessary information (Address, Netmask, Gateway, DNS) and click Apply.
7. Click OK.

## Windows 11

1. Open Settings.
2. Go to Network & Internet.
3. Select your connection type (Ethernet or Wi-Fi).
4. Click Manage and then click Edit.
5. Select Manual under Edit Network IP.
6. Fill out the necessary information (Address, Netmask, Gateway, DNS) and click Apply.
7. Click Save.

## Android

1. Open Settings.
2. Tap Network & Internet.
3. Tap the gear icon associated with the wireless network you're using.
4. Tap the pencil icon in the upper right corner.
5. Tap Advanced options.
6. Select Static from the IP Settings drop-down.
7. Fill out the necessary information (Address, Netmask, Gateway, DNS) and click Apply.
8. Click Save.

## iOS

1. Open Settings.
2. Select Wi-Fi
3. Tap the icon to the right of the wireless network you're using.
4. Select Manual from the Configure IP drop-down.
5. Fill out the necessary information (Address, Netmask, Gateway, DNS) and click Apply.
6. Click Save

Remember, changing your internal IP address does nothing to your external address.  

## How to change your external IP address

As I mentioned, you won't be doing this manually or permanently. What you can do, however, is use a service to masquerade your true external IP address as something else. For this, you can obfuscate your external IP address in three different ways.

### 1\. VPN

Most modern VPN services not only mask your external IP address but also encrypt your traffic. This is probably the easiest method to [hide your external IP address](https://www.zdnet.com/article/how-to-change-your-ip-address-why-youd-want-to-and-when-you-shouldnt/). You'll find [VPN services](https://www.zdnet.com/article/best-vpn/) for every platform you use (Linux, MacOS, Windows, [Android,](https://www.zdnet.com/article/best-mobile-vpn/) and [iOS](https://www.zdnet.com/article/best-mobile-vpn/)). Popular VPNs include [NordVPN](https://go.nordvpn.net/aff%5Fc?aff%5Fsub=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp&aff%5Fid=307&source=ZDNET&offer%5Fid=378), [ExpressVPN](https://go.expressvpn.com/c/159047/1330033/16063?&sharedid=zdnet&partnerpropertyid=1980086&u=https%3A%2F%2Fwww.expressvpn.com%2Forder&subId1=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp), [Surfshark VPN](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fget.surfshark.net%2Faff%255Fc%3Faff%255Fsub%3Dzd-%255F%255FCOM%255FCLICK%255FID%255F%255F-dtp%26aff%255Fid%3D1511%26source%3DZDNET%26offer%255Fid%3D786), [Private Internet Access](https://www.tkqlhce.com/click-9041660-14351883-1682250314000?sid=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp), and [Proton VPN](https://go.getproton.me/aff%5Fc?offer%5Fid=25&aff%5Fid=4706&source=ZDNET&aff%5Fsub=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp). You can read more about how these services rate (and what features they offer) [here](https://www.zdnet.com/article/best-vpn/). Most VPNs do have an associated cost.

### 2\. Tor Browser

If you don't want to have to either pay for a VPN or go through the process of installing and configuring such a service, you could always use Tor Browser. [Tor Browser](https://www.torproject.org/download/) does everything a VPN does, only with more layers of security. The only caveat to using Tor Browser is that it only works for your web browser traffic, which means it won't obfuscate your external IP address for other network-based services.

**Also: [How to use Tor browser](https://www.zdnet.com/article/how-to-use-tor-browser-and-why-you-should/)**

### 3\. Proxy Server

This is the most complicated process because it requires installing and configuring the service, which is often more challenging than using either a VPN or Tor Browser. On top of that, if you opt for a Proxy Server, you also have to configure any machine on your network to connect through the proxy server. I wouldn't recommend going this route as the complications it adds can be quite frustrating. 

And there you have it: The various ways you can change your internal and external IP address. Do keep in mind that when changing your internal IP address you want to make sure you're not changing it to one that is already in use (otherwise, you'll wind up with IP Address conflict errors). As for your external address, your best bet is to go with either a VPN or Tor Browser to obfuscate your external address, which not only prevents third parties from locating (and even tracking) you but also encrypts your network traffic.

#### Featured

[How to disable ACR (and greatly reduce ads) on every TV model - and why you should](https://www.zdnet.com/article/how-to-disable-acr-and-greatly-reduce-ads-on-every-tv-model-and-why-you-should/ "How to disable ACR (and greatly reduce ads) on every TV model - and why you should")

[I replaced my Samsung Galaxy S24 Ultra with the Pixel 9 Pro XL for two weeks - and can't go back](https://www.zdnet.com/article/i-replaced-my-samsung-galaxy-s24-ultra-with-the-pixel-9-pro-xl-for-two-weeks-and-cant-go-back/ "I replaced my Samsung Galaxy S24 Ultra with the Pixel 9 Pro XL for two weeks - and can't go back")

[Linus Torvalds talks AI, Rust adoption, and why the Linux kernel is 'the only thing that matters'](https://www.zdnet.com/article/linus-torvalds-talks-ai-rust-adoption-and-why-the-linux-kernel-is-the-only-thing-that-matters/ "Linus Torvalds talks AI, Rust adoption, and why the Linux kernel is 'the only thing that matters'")

[The best mini PCs you can buy: Expert recommended](https://www.zdnet.com/article/best-mini-pc/ "The best mini PCs you can buy: Expert recommended")

* [How to disable ACR (and greatly reduce ads) on every TV model - and why you should](https://www.zdnet.com/article/how-to-disable-acr-and-greatly-reduce-ads-on-every-tv-model-and-why-you-should/ "How to disable ACR (and greatly reduce ads) on every TV model - and why you should")
* [I replaced my Samsung Galaxy S24 Ultra with the Pixel 9 Pro XL for two weeks - and can't go back](https://www.zdnet.com/article/i-replaced-my-samsung-galaxy-s24-ultra-with-the-pixel-9-pro-xl-for-two-weeks-and-cant-go-back/ "I replaced my Samsung Galaxy S24 Ultra with the Pixel 9 Pro XL for two weeks - and can't go back")
* [Linus Torvalds talks AI, Rust adoption, and why the Linux kernel is 'the only thing that matters'](https://www.zdnet.com/article/linus-torvalds-talks-ai-rust-adoption-and-why-the-linux-kernel-is-the-only-thing-that-matters/ "Linus Torvalds talks AI, Rust adoption, and why the Linux kernel is 'the only thing that matters'")
* [The best mini PCs you can buy: Expert recommended](https://www.zdnet.com/article/best-mini-pc/ "The best mini PCs you can buy: Expert recommended")

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
