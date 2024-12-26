---
title: "Replacing the Favorite Abandoned Linux Command Line Tool: Best Options Available Now"
date: 2024-12-24T05:45:13.405Z
updated: 2024-12-26T07:02:27.725Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a0a9154950aed42e7733b765877eaeb4a66b52b52c8c12f95943f09a40bb3819.jpg
---

## Replacing the Favorite Abandoned Linux Command Line Tool: Best Options Available Now

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* It's time to say goodbye to neofetch, as the developer has abandoned the project due to farming commitments.
* Fastfetch, macchina, NerdFetch, and others are viable alternatives offering new features and better maintenance.

 If you're a Linux user, you might know about neofetch, a popular command-line tool that shows system information in the terminal. Many users love it because it's customizable and looks great. Unfortunately, the developer has discontinued the project, so it's time to say goodbye to this helpful tool.

##  Is neofetch Dead?

 Yes, it's true—the neofetch project has been officially declared dead. Although the developer archived the project on April 26th, 2024, the last update was three years ago. The developer left a note in the README file stating he had taken up farming, which is the only explanation for the archiving.

 neofetch's abandonment doesn't mean it will disappear immediately. Since it's a Bash script, it will likely continue to work for a long time until the applications it relies on become outdated.

 You can continue using neofetch if you wish, but be aware that it is no longer maintained or updated. Using outdated software can pose security risks, so I strongly advise against relying on expired or out-of-date tools. Instead, consider exploring alternative, actively supported options.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, you can get system information directly using:

macchina

![Linux terminal window showing system information by executing macchina](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-window-showing-system-information-by-executing-macchina.png) 

 If you are an Arch Linux user, you can also install macchina [from the AUR using Yay](https://win-answers.techidaily.com/resolved-overcoming-ies-webpage-display-issues/).

yay -S macchina

###  screenFetch

[screenFetch](https://github.com/KittyKatt/screenFetch) is another handy terminal utility just like neofetch that displays system information in a terminal. In fact, screenFetch is older than neofetch. While it may not have the same level of visual appeal as some of the newer options, screenFetch is a reliable and well-established tool that gets the job done.

 By running the **screenfetch** command, you can quickly display a snapshot of your system’s current state, including OS, kernel version, uptime, package counts, and more. You can also screenshot the displayed output using **screenfetch -s**.

 screenFetch is available in the default Ubuntu repositories. To get it, run:

sudo apt install screenfetch

![Linux terminal window showing system information by executing screenfetch](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-window-showing-system-information-by-executing-screenfetch.png) 

 screenFetch also allows you to display a different ASCII art logo than the default one detected by screenFetch. You can simply specify a distribution name with the **\-A 'distribution\_name'** option like this:

screenfetch -A 'Debian'

![Linux terminal window showing debian ASCII art logo along with system information by using screenfetch tool](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-window-showing-debian-ascii-art-logo-along-with-system-information-by-using-screenfetch-tool.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To get screenFetch on RHEL/CentOS/Fedora, run:

sudo dnf install screenfetch 

 On Arch Linux:

sudo pacman -S screenfetch

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Arch users can get NerdFetch using any AUR helper like Yay or Paru:

yay -S nerdfetch

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
<li><a href="https://youtube-webster.techidaily.com/erfect-panning-leading-stabilizers-unveiled/"><u>[New] Perfect Panning Leading Stabilizers Unveiled</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-sequential-appearance-start/"><u>[Updated] Sequential Appearance Start</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-assessing-instagrams-selfie-validation/"><u>2024 Approved Assessing Instagram's Selfie Validation</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/amazon-explores-new-escrow-feature-for-cryptocurrency-transactions-insights-from-zdnet/"><u>Amazon Explores New Escrow Feature for Cryptocurrency Transactions: Insights From ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/amazon-prime-early-bird-special-a-smart-investment-or-a-marketing-gimmick-digitaltrends/"><u>Amazon Prime Early Bird Special: A Smart Investment or a Marketing Gimmick? | DigitalTrends</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-simplified-shopping-top-5-innovative-updates-on-amazon-enhance-your-search-experience-insights-from-zdnet/"><u>Discover Simplified Shopping: Top 5 Innovative Updates on Amazon Enhance Your Search Experience - Insights From ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/explore-effortless-event-entry-learn-how-to-generate-various-passes-using-google-wallet-exclusive-tutorial-cnet/"><u>Explore Effortless Event Entry: Learn How to Generate Various Passes Using Google Wallet - Exclusive Tutorial | CNET</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-most-e-commerce-buyers-prefer-mobile-devices-for-making-transactions-insights-from-zdnet/"><u>How Most E-Commerce Buyers Prefer Mobile Devices for Making Transactions: Insights From ZDNet</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-still-using-pattern-locks-with-vivo-v30-pro-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Vivo V30 Pro? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-macbook-heat-top-tips-for-monitoring-your-laptops-temperature/"><u>Mastering MacBook Heat: Top Tips for Monitoring Your Laptop's Temperature</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mimicking-your-penmanship-adapting-chatgpt-for-authentic-self-expressive-writing/"><u>Mimicking Your Penmanship: Adapting ChatGPT for Authentic Self-Expressive Writing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/octobers-greatest-tech-steals-post-prime-day-discover-the-most-weird-and-wonderful-deals-on-gadgets-insider-tips-by-zdnet/"><u>October's Greatest Tech Steals Post-Prime Day – Discover the Most Weird and Wonderful Deals on Gadgets | Insider Tips by ZDNET</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/risking-it-all-the-tale-of-8000-passengers-on-southwest-airlines-insights-from-zdnet/"><u>Risking It All: The Tale of 8,000 Passengers on Southwest Airlines | Insights From ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-starbucks-stealthy-growth-a-luxurious-offering-that-could-excite-your-taste-buds-discovered-by-zdnet/"><u>Unveiling Starbucks' Stealthy Growth: A Luxurious Offering That Could Excite Your Taste Buds - Discovered by ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-secret-behind-temus-low-prices-a-deep-dive-explored-by-zdnet/"><u>Unveiling the Secret Behind Temu's Low Prices: A Deep Dive Explored by ZDNet</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-effortless-video-editing-how-to-add-effects-in-fcp-x-3-simple-steps/"><u>Updated 2024 Approved Effortless Video Editing How to Add Effects in FCP X (3 Simple Steps)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/why-im-continuously-choosing-the-apple-watch-series-7-over-upcoming-series-10/"><u>Why I'm Continuously Choosing the Apple Watch Series 7 Over Upcoming Series 10</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/young-prodigys-riches-soar-in-digital-world-fame-for-2024/"><u>Young Prodigy's Riches Soar in Digital World Fame for 2024</u></a></li>
</ul></div>

