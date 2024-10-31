---
title: StarlingX Revolutionized with Enhanced Cloud-Edge Integration - Latest Update Unveiled on ZDNet
date: 2024-10-27T00:01:11.138Z
updated: 2024-10-30T20:12:12.602Z
tags:
  - edge-computing
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/edge-computing/    https://www.zdnet.com/a/img/resize/72be91e981ff57b2ebad7a55c1762f5aa2a63c98/2021/11/19/f1c1e2cb-df25-4ef1-bf2e-76a7087ef5c1/edge-computing.png?width=170&height=128&fit=crop&format=pjpg&auto=webp
---

## StarlingX Revolutionized with Enhanced Cloud-Edge Integration - Latest Update Unveiled on ZDNet

![Bright arrows moving forward towards blue screens.](https://www.zdnet.com/a/img/resize/671d44eb10868c4e95d9d7fe8c95e82b32ef2df3/2021/11/19/f1c1e2cb-df25-4ef1-bf2e-76a7087ef5c1/edge-computing.png?auto=webp&width=1280)

metamorworks/Shutterstock

When [Gartner](https://www.gartner.com/en) recently looked into its crystal ball, [it saw](https://www.equinix.com/resources/analyst-reports/gartner-distributed-enterprise-predictions-2022?ls=Advertising%20-%20Web&lsd=22q1%5Fenterprise%5Fdigital-infrastructure--not-applicable%5F/resources/analyst-reports/gartner-distributed-enterprise-predictions-2022%5Fdm%5Fobility%5Fpaid-search%5Fgoogle%5Fus-en%5FAMER%5Fdigital-edge%5Fdemand-gen&utm%5Fcampaign=us-en%5Fgoogle%5Fpaid-search%5Fdigital-edge%5Fdm&utm%5Fsource=google&utm%5Fmedium=paid-search&utm%5Fcontent=digital-infrastructure--not-applicable%5Fgartner-distributed-enterprise-predictions-2022&gclid=CjwKCAjwyaWZBhBGEiwACslQo1AGTjhNzGVtdMvA2aB17%5FaXR24lcHFSGMewfbYLWpLwzsH6Mult0BoCfQ0QAvD%5FBwE), "By 2025, more than 50% of enterprise-managed data will be created and processed outside the data center or cloud." So where will it be then? It will be on [edge computing](https://www.zdnet.com/topic/edge-computing/), and chances are excellent that you'll be using the newest version of [StarlingX](https://www.starlingx.io/), [StarlingX 7.0](https://docs.starlingx.io/specs/specs/stx-7.0/index.html), the open-source edge computing and IoT cloud platform there.

**Also:** [Google is exiting the IoT business. Microsoft is doing the opposite](https://www.zdnet.com/article/google-is-exiting-the-iot-services-business-microsoft-is-doing-the-opposite/) 

### Cloud

* [​What is digital transformation? Everything you need to know](https://www.zdnet.com/article/what-is-digital-transformation-everything-you-need-to-know-about-how-technology-is-reshaping/)
* [The best cloud providers compared: AWS, Azure, Google Cloud, and more](https://www.zdnet.com/article/the-top-cloud-providers-of-2021-aws-microsoft-azure-google-cloud-hybrid-saas/)
* [The top 6 cheap web hosting services: Find an affordable option](https://www.zdnet.com/article/best-cheap-web-hosting/)
* [What is cloud computing? Here's everything you need to know](https://www.zdnet.com/article/what-is-cloud-computing-everything-you-need-to-know-about-the-cloud/)

Why? Because rather than trying to reinvent the wheel, the [OpenInfra Foundation's](https://openinfra.dev/) StarlingX uses best-of-breed open-source programs to deliver a complete edge computing stack. This starts with Ceph. This Red Hat-sponsored do-it-all, open-source software-defined storage platform can work with object-level, block-level, and file-level storage. For cloud management, it uses the tried and true OpenStack. And, for container orchestration, StarlingX uses, of course, Kubernetes.

It comes as no surprise then that StarlingX is used in industrial Internet of Things (IoT), telecom, video delivery, and so on. In short, if you need ultra-low latency and all the resources a full cloud stack can bring you, StarlingX is probably for you. Such Telecom companies as Docomo, NTT, Verizon, and Vodafone are already using it for their 5G deployments.

Ildikó Váncsa, OpenInfra's Senior Manager for Community & Ecosystem, added in a statement that more is to come. While what it brings to the table is great for 5G Open Radio Access Network (RAN), its characteristics also make "StarlingX the ideal platform for innovations like autonomous vehicles, smart cities, augmented reality, manufacturing, drone delivery, and remote healthcare to become reality."

The biggest single change is that StarlingX no longer uses [CentOS](https://www.centos.org/) for its base operating system. Instead, it now uses [Debian](https://www.debian.org/). Specifically, the latest [Debian Stable Release, Bullseye.](https://www.debian.org/releases/bullseye/) The [developers moved to Debian](https://docs.starlingx.io/specs/specs/stx-6.0/approved/starlingx%5F2008704%5Fdebian%5Ftransition.html) because they didn't want to rely on a commercial Linux distro. They felt burned by Red Hat's decision to turn CentOS into an upstream of [Red Hat Enterprise Linux (RHEL)](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux). Debian, on the other hand, appeared more stable and had a robust community that already supports core StarlingX open-source programs such as Kubernetes, Ceph, and OpenStack.

**Also:** [CentOS Linux lives on in the AlmaLinux 9](https://www.zdnet.com/article/old-style-centos-linux-lives-on-in-the-new-almalinux-9/)

That said, StarlingX 7,0 does come with prebuilt CentOS, Debian, and Docker images. It also now uses [Kubernetes 1.23](https://kubernetes.io/blog/2021/12/07/kubernetes-1-23-release-announcement/), the December 2021 release, by default.

To help StarlingX live up to its potential, the new StarlingX 7.0 key features include:

* **Improved scalability**: The more sub-clouds StarlingX's Distributed Cloud architecture can manage, the larger you can grow your edge infrastructure, StarlingX 7.0 can handle up to 1,000 sub-clouds.
* **Greater network speed**: StarlingX 7.0 now uses [Istio service mesh](https://istio.io/latest/about/service-mesh/) to speed up Kubernetes' observability, traffic management, security, and policy management functions.
* **Enhanced security**: It now enables you to log commands using the popular representational state transfer (REST) Application Programming Interface (API) to Kubernetes. This enables you to spot suspicious activity and block it before it can cause trouble.
* **Enhanced security II**: It has also replaced Kubernetes Pod Security Policies (PSP) with Pod Security Admission Controller. This is a more efficient and reliable way to enforce pod security standards.

Check out the [StarlingX 7.0 release notes](https://docs.starlingx.io/releasenotes/r7-0-release-notes-85446867da2a.html) for more details about these and other features.

If you see [Edge Computing](https://www.zdnet.com/article/edge-computing-is-coming-and-businesses-arent-ready/) in your company's future, you should look into StarlingX. When Arpit Joshipura, the Linux Foundation's general manager of networking, said in 2019 that [edge computing would overtake cloud computing by 2025](https://www.zdnet.com/article/linux-foundation-executive-believes-edge-computing-will-be-more-important-than-cloud-computing/), it looks like he was right. And, by using best-of-best-of-breed open-source software to create a complete stack, your developers will find it much easier to build solid, Edge Computing applications and services. 

#### Featured

[The fastest VPNs: Expert tested and reviewed](https://www.zdnet.com/article/fastest-vpn/ "The fastest VPNs: Expert tested and reviewed")

[Google Pixel 9 Pro XL vs. Samsung Galaxy S24 Ultra: I tested both and here are the key differences](https://www.zdnet.com/article/google-pixel-9-pro-xl-vs-samsung-galaxy-s24-ultra/ "Google Pixel 9 Pro XL vs. Samsung Galaxy S24 Ultra: I tested both and here are the key differences")

[How to upgrade your 'incompatible' Windows 10 PC to Windows 11](https://www.zdnet.com/article/how-to-upgrade-your-incompatible-windows-10-pc-to-windows-11/ "How to upgrade your 'incompatible' Windows 10 PC to Windows 11")

[Your Android phone is getting an anti-theft upgrade, thanks to AI. How it works](https://www.zdnet.com/article/your-android-phone-is-getting-an-anti-theft-upgrade-thanks-to-ai-how-it-works/ "Your Android phone is getting an anti-theft upgrade, thanks to AI. How it works")

* [The fastest VPNs: Expert tested and reviewed](https://www.zdnet.com/article/fastest-vpn/ "The fastest VPNs: Expert tested and reviewed")
* [Google Pixel 9 Pro XL vs. Samsung Galaxy S24 Ultra: I tested both and here are the key differences](https://www.zdnet.com/article/google-pixel-9-pro-xl-vs-samsung-galaxy-s24-ultra/ "Google Pixel 9 Pro XL vs. Samsung Galaxy S24 Ultra: I tested both and here are the key differences")
* [How to upgrade your 'incompatible' Windows 10 PC to Windows 11](https://www.zdnet.com/article/how-to-upgrade-your-incompatible-windows-10-pc-to-windows-11/ "How to upgrade your 'incompatible' Windows 10 PC to Windows 11")
* [Your Android phone is getting an anti-theft upgrade, thanks to AI. How it works](https://www.zdnet.com/article/your-android-phone-is-getting-an-anti-theft-upgrade-thanks-to-ai-how-it-works/ "Your Android phone is getting an anti-theft upgrade, thanks to AI. How it works")

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
<li><a href="https://youtube-docs.techidaily.com/024-approved-the-best-in-class-our-comprehensible-guide-to-top-12-vlogging-cameras/"><u>[New] 2024 Approved The Best in Class Our Comprehensible Guide to Top 12 Vlogging Cameras</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-crafting-compact-comforts-essential-mc-abodes-for-beginners/"><u>[Updated] In 2024, Crafting Compact Comforts Essential MC Abodes for Beginners</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-beyond-binary-boundaries-unveiling-metaverse-vs-multiverse/"><u>2024 Approved Beyond Binary Boundaries Unveiling Metaverse V/S Multiverse</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-organize-and-download-fb-links-optimized-tools-for-23/"><u>2024 Approved Organize and Download FB Links Optimized Tools for '23</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-drivers-for-xbox-360-controllers-compatible-software-and-installation-guide/"><u>Download Drivers for Xbox 360 Controllers: Compatible Software & Installation Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/elevate-your-smart-home-experience-this-labor-day-save-big-on-echo-show-8-with-an-exclusive-30-discount/"><u>Elevate Your Smart Home Experience This Labor Day - Save Big on Echo Show 지 8 with an Exclusive 30% Discount!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exceptional-sound-experience-found-in-non-brand-name-speaker-beyond-bose-and-sony/"><u>Exceptional Sound Experience Found in Non-Brand Name Speaker - Beyond Bose and Sony</u></a></li>
<li><a href="https://discover-blog.techidaily.com/gratis-dvd-ripper-ohne-wasserzeichen-hochwertige-umwandlung-von-dvds/"><u>Gratis DVD Ripper Ohne Wasserzeichen: Hochwertige Umwandlung Von DVDs</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/grell-tws1x-wireless-earbuds-reviewed-stellar-audio-quality-meets-disappointing-design-on-zdnet/"><u>Grell TWS1X Wireless Earbuds Reviewed: Stellar Audio Quality Meets Disappointing Design on ZDNet</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-zte-nubia-flip-5g-frp-by-drfone-android/"><u>How Can We Bypass ZTE Nubia Flip 5G FRP?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-poco-m6-pro-4g-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Poco M6 Pro 4G Location by Number | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/launchpad-to-success-establishing-your-own-food-flavor-blogchannel/"><u>Launchpad to Success Establishing Your Own Food Flavor Blog/Channel</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/philips-fidelio-fb1-the-ultimate-audio-experience-tailored-for-true-audiophiles-insights-from-zdnet/"><u>Philips Fidelio FB1: The Ultimate Audio Experience Tailored for True Audiophiles - Insights From ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-5-budget-friendly-wireless-bluetooth-speakers-below-50-expert-reviews-and-comparison/"><u>Top 5 Budget-Friendly Wireless Bluetooth Speakers Below $50 - Expert Reviews & Comparison</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-ranked-solar-powered-bluetooth-speakers-comprehensive-guide-and-reviews-techradar/"><u>Top-Ranked Solar-Powered Bluetooth Speakers : Comprehensive Guide and Reviews - TechRadar</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-how-to-organize-an-unforgettable-labor-day-celebration-tips-and-tricks-from-zdnet/"><u>Ultimate Guide: How to Organize an Unforgettable Labor Day Celebration - Tips & Tricks From ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unmatched-audio-experience-non-sony-non-jbl-brand-outshines-giants-discover-at-zdnet/"><u>Unmatched Audio Experience: Non-Sony, Non-JBL Brand Outshines Giants - Discover at ZDNet</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

