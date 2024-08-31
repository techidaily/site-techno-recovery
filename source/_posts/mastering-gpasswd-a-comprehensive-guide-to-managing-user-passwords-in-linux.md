---
title: "Mastering Gpasswd: A Comprehensive Guide to Managing User Passwords in Linux"
date: 2024-08-30T13:08:14.441Z
updated: 2024-08-31T13:08:14.441Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/2cea6027c03bd4c55f4ae87f65e8c9bc1f9246426c62a6f89484db17077fafde.jpg
---

## Mastering Gpasswd: A Comprehensive Guide to Managing User Passwords in Linux

### Key Takeaways

* Use gpasswd to manage group members & passwords, avoiding security risks & controlling group access efficiently.
* The basic syntax is "gpasswd \[option\] \[group\]".
* Execute commands like "sudo gpasswd -a user group" to add users and "sudo gpasswd -d user group" to remove them.

 Want an easy solution to managing group members and passwords on Linux? The gpasswd command will help you do that. It's used for managing and administering the "/etc/group" and "/etc/gshadow" passwords, members, and administrators. Let's get started.

##  What Makes the gpasswd Command Useful

 The gpasswd command lets you administer groups on Linux. Group passwords don't get used a lot in part because of the security risk they pose: multiple people sharing a password increases the opportunity for accidental or malicious exposure. Any member of the group can add or remove members, controlling the group access, which could easily get out of hand.

 There are a few ways to overcome this problem. You can avoid using group passwords when possible and use alternative mechanisms such as sudoers or access control lists. You can also limit access to the group passwords using privilege control so that only authorized members can do any operations.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
##  gpasswd Command Basic Syntax and Options

 The basic syntax of the gpasswd command allows it to take two arguments: an option or flag argument and the name of the group where you'd like to run the operation. Here's how it looks:

gpasswd [option] group

 Here are the options you can use with the command:

* \-a, --add _user_ : To add a user to the named group.
* \-d, --delete _user_ : To remove a user from the named group.
* \-h, --help : Displays the instructions to use the command.
* \-R, --restrict : Sets the group password to "!" so that only group members with a password are allowed to use newgrp to join the named group.
* \-r, --remove-password : To remove the password from the named group. The group password becomes empty.
* \-A, --administrators _user_ : Sets the list of administrative users.
* \-M, --members _user_ : Sets the list of group members.
* \-Q, --root CHROOT\_DIR : Applies changes in the CHROOT\_DIR directory and uses the configuration files from the CHROOT\_DIR directory.

 We'll see how to use these options in the upcoming sections of the guide.

##  Setting Password for a Group

 The most common use of the gpasswd command is to [set a password](https://unlock-android.techidaily.com/in-2024-best-honor-100-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/) for specific groups. I'll first create a group we can test it upon. Feel free to skip this if you already have a group. To create a new group on your Linux system, run:

sudo groupadd demogroup

![The Linux terminal displaying the process of creating a new group on Linux using the groupadd command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/1-8.png) 

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can use any other name than "demogroup". To confirm if the group creation was successful, display all groups using:

cat /etc/group

![The Linux terminal showing a list of all groups in the system](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/2-7.png) 

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
 You can see the new group on the list. Now let's create a password for the group. To do that, use:

sudo gpasswd demogroup

 You'll be asked to enter your user password first (since you used sudo). Then you'll be asked to enter a new password for the group. After entering the new password, you need to re-enter it to confirm the password.

![The Linux terminal displaying the process of setting a new password for a group using the gpasswd command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/3-7.png) 

 Now if I try to log into this group, the system will ask for a password. That's because I'm not a member of the group. To log into the group, run:

newgrp demogroup

![The Linux terminal showing the process of logging into a group in Linux using the newgrp command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/4-4.png) 

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Removing Password from Group

 If you want to remove a password from a group, you can do that using the -r flag. Remove the password by passing the group name along with the flag like this:

sudo gpasswd -r demogroup

![The Linux terminal showing the process of removing the password from a a group in Linux using the gpasswd command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/10-3.png) 

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you try to log into the group now as a member, you'll be able to do so without entering the password.

##  Adding a User to a Group

 The gpasswd command lets you add new members to groups. The -a option is for that purpose. The command syntax is as follows:

sudo gpasswd -a user group

 So after adding the -a option, you need to pass the member's username and then the group to which you want to add the user. For example, I want to add a user to the new group I created earlier. Here's the command for that:

sudo gpasswd -a zunaid demogroup

![The Linux terminal showing how to use the gpasswd command to add a member to a group](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/5-2.png) 

 You can confirm whether the member was added or not. For that, use the below command:

getent group demogroup

![The Linux terminal shows the current members of the group named demogroup](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/6-7.png) 

 As you can see, I've successfully added myself to the group using gpasswd. For adding multiple users, you'll need to issue separate commands for each, like this:

sudo gpasswd -a user1 group

    
                    sudo gpasswd -a user2 group
                    

##  Removing a User From a Group

 If you want to delete a user from a specific group, you have the -d option for that. Much like the command for adding, simply provide the username and then the group name to the command, like this:

sudo gpasswd -d user group

 So if I want to remove myself from "demogroup", this is the command I need to run:

sudo gpasswd -d zunaid demogroup

![The Linux terminal showing how to remove a user from a group using the gpasswd command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/7-6.png) 

 Again, you can confirm if the user was removed successfully by [listing the group members](https://hardware-updates.techidaily.com/comprehensive-guide-downloading-and-installing-canon-ip1-10-drivers-on-windows-windows-111087/) with this command:

getent group demogroup

 You may need to restart your device or re-login into your session for the changes to take effect. To remove multiple users from a group, use the same repeated command technique as when adding.

sudo gpasswd -d user1 group

    
                    sudo gpasswd -d user2 group
                    

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Setting the List of Group Members

 The gpasswd command allows you to replace the current members of the group with members you want to add. In other words, you can empty the group and then add as many new members as you want with a single command. The -M flag serves that purpose. So for example, currently there are user1 and user2 in a group. You want to remove them and add user3 and user4\. To do this, run:

sudo gpasswd -M user2,user3 demogroup

![The Linux terminal showing the process of setting the list of members of a group using the gpasswd command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/11-3.png) 

 Now if you check the members list of the group, you should see that the previous members are not there. Instead, you'll find the new members.

getent group demogroup

![The Linux terminal displaying the current the members of a group in Linux after setting the members list using gpasswd](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/12-2.png) 

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Promoting a User as the Group Administrator

 You can grant someone administrative privileges of a group using the -A flag. Simply pass the name of the member and the group of which you want to make him the administrator. See the command below:

sudo gpasswd -A zunaid demogroup

 This gives the user "zunaid" administrative privileges in the group called "demogroup".

![The Linux terminal showcasing how to make a user the administrator of a group using the gpasswd command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/8-4.png) 

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
 This doesn't give any output to the terminal. However, you can see the list of administrators of the group to confirm if the operation was successful. Do that with this command:

sudo cat /etc/gshadow

![The Linux terminal displaying the the administrators of every group in Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/9-3.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
##  gpasswd Makes Group Management Easy

 Now you've learned how to use the gpasswd command for controlling group access on Linux. I've covered some of its most useful operations. If you want to learn more about the command, check out its [manpage](https://man7.org/linux/man-pages/man1/gpasswd.1.html) or run the **gpasswd -h** command on your terminal.

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
<li><a href="https://extra-tips.techidaily.com/new-accelerating-your-creative-process-with-mac-dvd-authoring/"><u>[New] Accelerating Your Creative Process with Mac DVD Authoring</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-samsung-ubd-k8500-review/"><u>[New] Samsung UBD-K8500 Review</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-guide-to-controlling-playback-rate-on-snapchat/"><u>[New] The Ultimate Guide to Controlling Playback Rate on Snapchat</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-laughter-ledger-twittersphere-tales-for-2024/"><u>[Updated] Laughter Ledger  Twittersphere Tales for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-sourav-joshis-financial-blueprint-for-online-content-creators-2024/"><u>[Updated] Sourav Joshi's Financial Blueprint for Online Content Creators, 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-artisans-guide-to-podcast-scriptwriting-including-free-samples/"><u>[Updated] The Artisan's Guide to Podcast Scriptwriting (Including Free Samples)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unleash-creativity-ranked-free-drawing-apps-for-mac/"><u>[Updated] Unleash Creativity  Ranked FREE Drawing Apps for Mac</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/11-best-streaming-audio-recorders-for-2024/"><u>11 Best Streaming Audio Recorders for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-direct-to-streamer-duel-obs-vs-shadowtoolkit/"><u>2024 Approved  Direct-to-Streamer Duel  OBS Vs. ShadowToolkit</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-streamline-your-social-footprint-share-videos-on-facebook-easily/"><u>2024 Approved  Streamline Your Social Footprint  Share Videos on Facebook Easily</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/5-of-our-favorite-free-language-learning-apps-of-2024/"><u>5 of Our Favorite Free Language Learning Apps of 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/a-comprehensive-guide-to-selecting-surge-protectors-for-electronic-devices/"><u>A Comprehensive Guide to Selecting Surge Protectors for Electronic Devices</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722865466096-a-step-by-step-guide-to-configuring-parent-controls-on-discord/"><u>A Step-by-Step Guide to Configuring Parent Controls on Discord</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/activatedeactivate-your-pcs-display-keyboard-in-windows-11-with-ease/"><u>Activate/Deactivate Your PC's Display Keyboard in Windows 11 with Ease</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/are-you-experiencing-blizzard-battlenet-downtime-or-personal-internet-glitches/"><u>Are You Experiencing Blizzard Battle.net Downtime or Personal Internet Glitches?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/complete-overview-of-macos-evolution-from-original-to-latest-version/"><u>Complete Overview of macOS Evolution - From Original to Latest Version</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/dealing-with-server-errors-insight-into-the-40urt-request-timed-out-problem-definition-plus-solutions/"><u>Dealing with Server Errors: Insight Into the 40Urt Request Timed Out Problem (Definition + Solutions)</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-for-repairing-malfunctioning-built-in-cameras-on-pcs-with-windows-os/"><u>Easy Solutions for Repairing Malfunctioning Built-In Cameras on PCs with Windows OS</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/escape-from-tarkov-performance-tuning-top-6-expert-tweaks-to-boost-your-fps/"><u>Escape From Tarkov Performance Tuning: Top 6 Expert Tweaks to Boost Your FPS</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/from-zero-to-social-media-hero-crafting-an-x-twitters-new-identity-presence-from-scratch/"><u>From Zero to Social Media Hero: Crafting an X (Twitter's New Identity) Presence From Scratch</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-typing-the-love-symbol-on-your-computer-keyboard/"><u>Guide: Typing the Love Symbol (❤️) on Your Computer Keyboard</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-expand-your-scratch-disk-and-rectify-full-capacity-errors-in-photoshop/"><u>How to Expand Your Scratch Disk and Rectify 'Full Capacity' Errors in Photoshop</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-reinitialize-bios-settings-using-the-cmos-reset-method/"><u>How To Reinitialize BIOS Settings Using the CMOS Reset Method</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-resolve-problems-with-a-non-functioning-zoom-webcam/"><u>How To Resolve Problems With A Non-Functioning Zoom Webcam</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-seamlessly-include-developer-scripts-within-a-word-file/"><u>How to Seamlessly Include Developer Scripts Within a Word File</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/immerse-yourself-in-sound-the-ultimate-selection-of-best-dolby-atmos-movies-at-home/"><u>Immerse Yourself in Sound: The Ultimate Selection of Best Dolby Atmos Movies at Home</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Honor X50i | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/inside-scoop-on-google-pixel-9-projected-pricing-structure-launch-window-and-rumored-gadget-attributes/"><u>Inside Scoop on Google Pixel 9: Projected Pricing Structure, Launch Window & Rumored Gadget Attributes</u></a></li>
<li><a href="https://article-files.techidaily.com/intense-action-iphone-tips-for-artistic-motion-blur-photos/"><u>Intense Action  IPhone Tips for Artistic Motion-Blur Photos</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-optimal-internet-coverage-worth-it-with-a-wi-fi-mesh-setup/"><u>Is Optimal Internet Coverage Worth It with a Wi-Fi Mesh Setup?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-premiere-vs-after-effects-which-video-editing-software-reigns-supreme/"><u>New 2024 Approved Premiere vs After Effects Which Video Editing Software Reigns Supreme?</u></a></li>
<li><a href="https://review-topics.techidaily.com/realme-c67-4g-music-recovery-recover-deleted-music-from-realme-c67-4g-by-fonelab-android-recover-music/"><u>Realme C67 4G Music Recovery - Recover Deleted Music from Realme C67 4G</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solutions-for-microsoft-edge-malfunctioning-problems/"><u>Solutions for Microsoft Edge Malfunctioning Problems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-the-problem-no-signal-on-your-stadia-headset-how-to-reconnect/"><u>Solving the Problem: No Signal on Your Stadia Headset - How to Reconnect?</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-your-problems-repairing-keyboard-malfunctions-in-pathfinder-wrath-of-the-righteous/"><u>Solving Your Problems: Repairing Keyboard Malfunctions in Pathfinder: Wrath of the Righteous</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-process-to-dry-and-restore-your-wet-apple-mobile-device/"><u>Step-by-Step Process to Dry and Restore Your Wet Apple Mobile Device</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-solutions-for-paramount-plus-connectivity-problems-on-amazon-fire-sticks/"><u>Step-by-Step Solutions for Paramount Plus Connectivity Problems on Amazon Fire Sticks</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-7-most-effective-notetakers-for-apples-ipad-and-ipad-pro-devices/"><u>The 7 Most Effective Notetakers for Apple's iPad and iPad Pro Devices</u></a></li>
<li><a href="https://audio-editing.techidaily.com/the-beat-makers-playbook-ranking-the-top-8-daw-applications-for-contemporary-urban-music/"><u>The Beat Makers Playbook Ranking the Top 8 DAW Applications for Contemporary Urban Music</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-gopro-editors-blueprint-to-stunning-colored-images/"><u>The GoPro Editor's Blueprint to Stunning Colored Images</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-showdown-between-iphone-15-pro-max-and-samsung-s24-ultra-who-wins/"><u>The Showdown Between iPhone 15 Pro Max And Samsung S24 Ultra – Who Wins?</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ltimate-compilation-techniques-for-posting-youtube-videos-on-facebook-for-2024/"><u>The Ultimate Compilation  Techniques for Posting YouTube Videos on Facebook for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-list-of-15-free-protective-boot-loaders-you-should-try-today/"><u>The Ultimate List of 15 Free Protective Boot Loaders You Should Try Today</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-11-motivational-films-that-will-fuel-your-spirit/"><u>Top 11 Motivational Films That Will Fuel Your Spirit</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unlock-professional-subtitle-transformation-at-zero-price/"><u>Unlock Professional Subtitle Transformation at Zero Price</u></a></li>
</ul></div>
