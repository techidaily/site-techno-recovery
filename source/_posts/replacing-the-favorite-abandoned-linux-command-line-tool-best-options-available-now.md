---
title: "Replacing the Favorite Abandoned Linux Command Line Tool: Best Options Available Now"
date: 2024-08-30T13:08:22.292Z
updated: 2024-08-31T13:08:22.292Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a0a9154950aed42e7733b765877eaeb4a66b52b52c8c12f95943f09a40bb3819.jpg
---

## Replacing the Favorite Abandoned Linux Command Line Tool: Best Options Available Now

### Key Takeaways

* It's time to say goodbye to neofetch, as the developer has abandoned the project due to farming commitments.
* Fastfetch, macchina, NerdFetch, and others are viable alternatives offering new features and better maintenance.

 If you're a Linux user, you might know about neofetch, a popular command-line tool that shows system information in the terminal. Many users love it because it's customizable and looks great. Unfortunately, the developer has discontinued the project, so it's time to say goodbye to this helpful tool.

##  Is neofetch Dead?

 Yes, it's true—the neofetch project has been officially declared dead. Although the developer archived the project on April 26th, 2024, the last update was three years ago. The developer left a note in the README file stating he had taken up farming, which is the only explanation for the archiving.

 neofetch's abandonment doesn't mean it will disappear immediately. Since it's a Bash script, it will likely continue to work for a long time until the applications it relies on become outdated.

 You can continue using neofetch if you wish, but be aware that it is no longer maintained or updated. Using outdated software can pose security risks, so I strongly advise against relying on expired or out-of-date tools. Instead, consider exploring alternative, actively supported options.

##  Alternatives to neofetch

 neofetch's abandonment might be sad, but it's not the end. Explore alternatives like Fastfetch, macchina, and others, which offer new features and better maintenance.

###  Fastfetch

[Fastfetch](https://github.com/fastfetch-cli/fastfetch) is a faster, lighter, and up-to-date alternative to neofetch. It is written mainly in C and compatible with various platforms like macOS, Linux, and Windows. Fastfetch is actively maintained with community support and regular updates. Furthermore, it is easy to install and provides more information than neofetch, including desktop environment, window theme, and font.

 Fastfetch is not available by default in Debian or Ubuntu's software repositories. You can manually install its more recent version by adding a PPA repository to Ubuntu.

sudo add-apt-repository ppa:zhangsongcui3371/fastfetch

 Next, update your system's package list and install Fastfetch.

sudo apt update && sudo apt install fastfetch

 To get system information using Fastfetch, run:

fastfetch

![Linux terminal displaying system information using fastfetch tool](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-displaying-system-information-using-fastfetch-tool.png) 

 You can install Fastfetch on Fedora, CentOS, and RHEL by running this command:

sudo yum install fastfetch

 If you're an Arch Linux user, use this:

sudo pacman -S fastfetch

 Fastfetch displays your local IP address as well, so be careful when sharing your Fastfetch information screenshots with others.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  macchina

[macchina](https://github.com/Macchina-CLI/macchina) is a quick and easy tool for gathering information about your system. It's a lightweight alternative to neofetch that's all about speed and simplicity. It's designed with customization in mind, allowing you to tailor your system information display to your preferences.

 macchina has a theming system that lets you customize its appearance. You can create several themes and shift between them easily without affecting the main configuration.

 Moreover, you have two options to get started with macchina: either download the pre-built binary from the [Releases page](https://github.com/Macchina-CLI/macchina/releases) and use it directly, or install it using Cargo, Rust's package manager.

 If you choose to install using Cargo, first install Cargo on your Linux PC. To install Cargo on Ubuntu, for instance, run:

sudo apt install cargo

 Next, run the following command to install macchina:

cargo install macchina

 Once installed, you can display your system information by running the **\~/.cargo/bin/macchina** command with your desired flags. However, this is not a practical approach for getting system information using macchina.

 To avoid typing the full path to the macchina executable every time, you can add its installation directory to the PATH environment variable. This allows you to run macchina from any directory in your terminal.

 You can do this by editing your user's profile file. Simply open the file with gedit:

gedit ~/.profile 

 Next, add the ".cargo/bin" directory to your PATH.

![Adding macchina directory path in user profile file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/adding-macchina-directory-path-in-user-profile-file.png) 

 Now, you can get system information directly using:

macchina

![Linux terminal window showing system information by executing macchina](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-window-showing-system-information-by-executing-macchina.png) 

 If you are an Arch Linux user, you can also install macchina [from the AUR using Yay](https://win-answers.techidaily.com/resolved-overcoming-ies-webpage-display-issues/).

yay -S macchina

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  screenFetch

[screenFetch](https://github.com/KittyKatt/screenFetch) is another handy terminal utility just like neofetch that displays system information in a terminal. In fact, screenFetch is older than neofetch. While it may not have the same level of visual appeal as some of the newer options, screenFetch is a reliable and well-established tool that gets the job done.

 By running the **screenfetch** command, you can quickly display a snapshot of your system’s current state, including OS, kernel version, uptime, package counts, and more. You can also screenshot the displayed output using **screenfetch -s**.

 screenFetch is available in the default Ubuntu repositories. To get it, run:

sudo apt install screenfetch

![Linux terminal window showing system information by executing screenfetch](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-window-showing-system-information-by-executing-screenfetch.png) 

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 screenFetch also allows you to display a different ASCII art logo than the default one detected by screenFetch. You can simply specify a distribution name with the **\-A 'distribution\_name'** option like this:

screenfetch -A 'Debian'

![Linux terminal window showing debian ASCII art logo along with system information by using screenfetch tool](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-window-showing-debian-ascii-art-logo-along-with-system-information-by-using-screenfetch-tool.png) 

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To get screenFetch on RHEL/CentOS/Fedora, run:

sudo dnf install screenfetch 

 On Arch Linux:

sudo pacman -S screenfetch

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
###  NerdFetch

[NerdFetch](https://github.com/ThatOneCalculator/NerdFetch) is a POSIX-compliant fetch script that displays system information in a visually appealing format in the terminal. It utilizes [Nerd fonts](https://www.nerdfonts.com/font-downloads) to enhance the visual presentation of system information.

 Like other system information tools, NerdFetch also fetches and displays details such as your operating system name, version, and others. However, NerdFetch sets itself apart with its high level of customization, offering three distinct font modes for displaying system information, such as Cozette, Phosphor, and Emojis. You can switch between different fonts with the command-line options -c, -p, and -e.

 To install NerdFetch, simply download its script from the GitHub repository using [curl](https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-xiaomi-mix-fold-3-frp-locks-by-drfone-android/):

sudo curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/main/nerdfetch -o /usr/bin/nerdfetch

 After downloading, you need to make the script executable with:

sudo chmod +x /usr/bin/nerdfetch

 To display your system information, run:

nerdfetch

![Linux terminal showing system information in three different modes by using nerdfetch with flags](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-showing-system-information-in-three-different-modes-by-using-nerdfetch-with-flags.png) 

 Arch users can get NerdFetch using any AUR helper like Yay or Paru:

yay -S nerdfetch

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Customize Your Linux System for a Better Experience

 Customizing your Linux system can be a fun and rewarding experience. Whether you want to create your own Linux distribution or tweak your existing setup, there are numerous ways to make your desktop your own. For example, you can personalize your existing Linux installation by changing desktop themes and adding new icons and fonts. Furthermore, you can also use [Conky](https://facebook-video-content.techidaily.com/new-2024-approved-the-social-media-economy-maximizing-your-facebook-revenue/) to customize your widgets that display different system information.

 You can also use [Ubuntu Tweaks](https://youtube-web.techidaily.com/nfluencer-collaborations-impacting-video-view-counts-for-2024/) to customize your Ubuntu system easily. It lets you change settings and customize your Linux desktop to your liking.

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
<li><a href="https://youtube-data.techidaily.com/024-approved-maximize-visibility-with-well-structured-yt-summaries/"><u>[New] 2024 Approved  Maximize Visibility with Well-Structured YT Summaries</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-cultivating-companions-best-farm-games-to-share-with-pals/"><u>[New] In 2024, Cultivating Companions  Best Farm Games to Share with Pals</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-the-art-of-crafting-impactful-documentary-stories/"><u>[New] In 2024, The Art of Crafting Impactful Documentary Stories</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-top-11-best-online-facebook-cover-photo-makers/"><u>[New] Top 11 Best Online Facebook Cover Photo Makers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-masterpiece-maker-scenery-and-sound-unite-for-2024/"><u>[Updated] Masterpiece Maker  Scenery & Sound Unite for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-nubia-red-magic-8s-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/advanced-tips-for-capturing-gaming-moments-in-overwatch-for-2024/"><u>Advanced Tips for Capturing Gaming Moments in Overwatch for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/best-free-mobile-apps-for-watching-films-online/"><u>Best Free Mobile Apps for Watching Films Online</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/can-you-authentically-enjoy-immersive-dolby-atmos-surround-sound/"><u>Can You Authentically Enjoy Immersive Dolby Atmos Surround Sound?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-guide-to-fugeteks-ft-568-a-high-end-reliable-choice-for-selfie-enthusiasts/"><u>Comprehensive Guide to Fugetek's FT-568: A High-End, Reliable Choice for Selfie Enthusiasts</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-guide-how-to-correct-msvcr71dll-error-on-windows-systems/"><u>Comprehensive Guide: How to Correct MSVCR71.DLL Error on Windows Systems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/decoding-instagram-insights-into-how-it-works-and-why-people-love-it/"><u>Decoding Instagram: Insights Into How It Works and Why People Love It</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/diagnosing-issues-how-to-get-your-apple-software-running-smoothly-again/"><u>Diagnosing Issues: How to Get Your Apple Software Running Smoothly Again</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-ultimate-guide-to-organizing-your-familys-schedule-with-shared-calendars/"><u>Discover the Ultimate Guide to Organizing Your Family's Schedule with Shared Calendars</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/dive-into-safety-expertly-reviewed-best-water-resistant-smartphone-covers/"><u>Dive Into Safety: Expertly Reviewed Best Water-Resistant Smartphone Covers</u></a></li>
<li><a href="https://media-tips.techidaily.com/enhanced-amazon-fire-tv-upgraded-with-high-quality-soundbar-latest-4k-devices-and-additional-features/"><u>Enhanced Amazon Fire TV: Upgraded With High-Quality Soundbar, Latest 4K Devices & Additional Features</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/explore-our-chosen-selection-the-finest-no-cost-malware-eradication-tools-of-2024/"><u>Explore Our Chosen Selection: The Finest No-Cost Malware Eradication Tools of 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/fixes-for-rainbow-six-extraction-unwanted-restarts-and-crashes-on-windows/"><u>Fixes for Rainbow Six Extraction Unwanted Restarts and Crashes on Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/fixing-critical-system-failsures-a-deep-dive-into-ntldr-error-troubleshooting/"><u>Fixing Critical System Failsures: A Deep Dive Into NTLDR Error Troubleshooting</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/from-novice-to-expert-mastering-tiktoks-duet-feature-for-viral-success/"><u>From Novice to Expert: Mastering TikTok's Duet Feature for Viral Success</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/identifying-top-economical-iosandroid-live-streaming-tools/"><u>Identifying Top Economical iOS/Android Live Streaming Tools</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-oppo-reno-10-pro-5g-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Oppo Reno 10 Pro 5G</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/installing-microsoft-365-on-pcs-made-easy-a-comprehensive-walkthrough/"><u>Installing Microsoft 365 on PCs Made Easy - A Comprehensive Walkthrough</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722892994739-is-it-possible-to-know-if-someone-has-checked-your-sms-heres-how/"><u>Is It Possible to Know if Someone Has Checked Your SMS? Here's How</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-it-really-zoom-lagging-or-is-something-else-affecting-your-call-quality/"><u>Is It Really Zoom Lagging, or Is Something Else Affecting Your Call Quality?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/master-the-troubleshooting-process-for-ntloader-is-unavailable-and-similar-glitches/"><u>Master the Troubleshooting Process for 'NTLoader Is Unavailable' And Similar Glitches</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-dll-file-recovery-fixing-missing-libeay32dll-problems/"><u>Mastering DLL File Recovery: Fixing Missing 'libeay32.dll' Problems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-quick-fixes-for-malfunctioning-computer-keyboards-tips-and-techniques/"><u>Mastering Quick Fixes for Malfunctioning Computer Keyboards: Tips & Techniques</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/playstation-networks-stability-worldwide-crash-or-just-you-guys/"><u>PlayStation Network's Stability: Worldwide Crash or Just You, Guys?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/protecting-data-made-easy-with-these-e-free-backup-program-reviews-and-ratings/"><u>Protecting Data Made Easy with These E FREE Backup Program Reviews & Ratings</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resetting-your-samsung-tv-essential-steps-and-tips-for-success/"><u>Resetting Your Samsung TV: Essential Steps and Tips for Success</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/save-money-with-these-10-excellent-streaming-options-that-cost-nothing/"><u>Save Money with These 10 Excellent Streaming Options That Cost Nothing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-capturing-your-screen-on-windows-or-macos/"><u>Step-by-Step Guide: Capturing Your Screen on Windows or macOS</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722863532420-step-by-step-guide-setting-up-your-oculus-questquest-account/"><u>Step-by-Step Guide: Setting Up Your Oculus Quest/Quest #Account</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-strategies-to-find-and-buy-the-ideal-home-entertainment-tv/"><u>Step-by-Step Strategies to Find and Buy the Ideal Home Entertainment TV</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/take-charge-of-your-listening-experience-disabling-autoplay-in-apple-music/"><u>Take Charge of Your Listening Experience: Disabling Autoplay in Apple Music</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-progress-and-potential-of-5g-technology-at-verizon/"><u>The Progress and Potential of 5G Technology at Verizon</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-role-of-generative-ai-in-modern-search-technologies-and-businesses-leading-the-way/"><u>The Role of Generative AI in Modern Search Technologies & Businesses Leading the Way</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-checklist-of-7-key-aspects-for-choosing-the-right-smart-tv/"><u>The Ultimate Checklist of 7 Key Aspects for Choosing the Right Smart TV</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-guide-to-solving-wifi-authentication-troubles-on-android-smartphones/"><u>The Ultimate Guide to Solving Wifi Authentication Troubles on Android Smartphones</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-airpods-charge-issues-try-these-9-fixes/"><u>Troubleshooting AirPods Charge Issues? Try These 9 Fixes!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-solving-your-ipads-wi-fi-connection-issues/"><u>Ultimate Guide: Solving Your iPad's Wi-Fi Connection Issues</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/uncovering-hidden-digits-techniques-to-find-and-restore-erased-phone-numbers-on-android-phones/"><u>Uncovering Hidden Digits: Techniques to Find and Restore Erased Phone Numbers on Android Phones</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-ussd-unpacking-the-essentials-of-unstructured-supplementary-service-data/"><u>Understanding USSD: Unpacking the Essentials of Unstructured Supplementary Service Data</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-17-exceptional-tools-for-graphic-design-professionals/"><u>Unveiling 17 Exceptional Tools for Graphic Design Professionals</u></a></li>
</ul></div>
