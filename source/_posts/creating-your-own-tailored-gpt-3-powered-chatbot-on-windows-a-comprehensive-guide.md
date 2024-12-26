---
title: Creating Your Own Tailored GPT-3 Powered Chatbot on Windows - A Comprehensive Guide
date: 2024-12-23T23:28:24.410Z
updated: 2024-12-25T18:16:10.830Z
tags:
  - deals
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/person-using-a-windows-laptop-with-a-gpt-chat-window.jpg
---

## Creating Your Own Tailored GPT-3 Powered Chatbot on Windows - A Comprehensive Guide

### Quick Links

* [Why Would You Want Your Own Local AI Chatbot?](https://extra-information.techidaily.com/updated-10-best-live-streaming-platforms-you-should-know/)
* [How to Host Your Own Local GPT Chatbot on Windows](https://extra-guidance.techidaily.com/2024-approved-smart-shopping-tips-economical-gopro-cameras/)
* [Step 1: Install Docker and the Windows Terminal App](https://fox-glue.techidaily.com/updated-customizing-your-windows-photos-app-filters-and-music-sync-feature-for-2024/)
* [Step 2: Download the Text Generation Web UI GitHub Repository](https://win-solutions.techidaily.com/solving-the-outdated-driver-alert-in-minecraft-a-comprehensive-guide/)
* [Step 3: Launch the Text Generation Web UI](https://visual-screen-recording.techidaily.com/easy-peasy-guide-to-capturing-online-events-for-mac-and-windows-users/)
* [Step 4: Install the GPT-2 Model From OpenAI](https://extra-support.techidaily.com/lolkit-design-memes-and-graphics-with-a-click-for-2024/)
* [Step 5: Start Using Your Custom GPT AI Chatbot](https://some-approaches.techidaily.com/2024-approved-the-ultimate-key-to-exploring-without-boundaries-through-vr/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Running your own local GPT chatbot on Windows is free from online restrictions and censorship.
* Install text-generation-web-ui using Docker on a Windows PC with WSL support and a compatible GPU.
* Customize and train your GPT chatbot for your own specific use cases, like querying and summarizing your own documents, helping you write programs, or imitating your own characters.

 There are a number of advantages to running a GPT/AI chatbot on your own computer rather than accessing one on the Internet. We'll show why you might want to, and the easiest way to get it set up on Windows.

##  Why Would You Want Your Own Local AI Chatbot?

 While online AI chatbots like ChatGPT are dominant, with access to huge amounts of training data and up-to-date information, there are a few reasons you might want to run your own local chatbot on your Windows computer.

 Running your own AI tools locally is free, and comes without the restrictions of online tools: There's no censorship, and you can load whatever machine-learning models, tailor their responses and behavior, and provide any prompt, all without restriction (and in total privacy). It's also a good way to get an understanding of how modern large language model (LLM) AI tools work under the hood, especially if you are looking to get into the AI or tech industry.

 You can find models for just about anything, from fictional character interactions, to programming, to general knowledge, and many other use cases that more general online models may not cover.

##  How to Host Your Own Local GPT Chatbot on Windows

 This tutorial will use [text-generation-web-ui-docker](https://github.com/Atinoda/text-generation-webui-docker "https://github.com/oobabooga/text-generation-webui"), an open-source interface for large language models, that simplifies installing and using LLMs.

 text-generation-web-ui-docker bundles the text-generation-web-ui project using [Docker](https://vp-tips.techidaily.com/new-ultimate-auditory-interface-win-for-2024/), which removes the need for installing and managing all the complex dependencies that local AI tools usually require by storing everything in a container separate to your system. The only thing you need to run your local chatbot is a Windows PC that [supports Docker running using the Windows Subsystem for Linux (WSL)](https://docs.docker.com/desktop/install/windows-install/ "https://docs.docker.com/desktop/install/windows-install/"). You'll also need a fairly recent GPU, ideally one from NVIDIA, for maximum compatibility.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Step 1: Install Docker and the Windows Terminal App

 Docker containers are similar to [virtual machines](https://remote-screen-capture.techidaily.com/2024-approved-essential-guide-video-recording-with-vlc/) in that they contain a whole running system, but they are much more lightweight, and perfect for distributing applications and all of their requirements in a single, easy-to-install bundle. To run text-generation-web-ui-docker in Docker, [download and install Docker on your Windows system](https://www.docker.com/products/docker-desktop/ "https://www.docker.com/products/docker-desktop/").

 Docker can run on Windows in one of two ways: WSL or Hyper-V mode. WSL is recommended for most users, so you may need to [enable it](https://some-skills.techidaily.com/new-unveiling-paid-content-in-product-analysis/) before installing Docker.

 It's also recommended to [install the Windows Terminal app](https://youtube-tips.techidaily.com/ed-mastering-youtube-streaming-a-guide-for-gamers-for-2024/), as it provides a convenient interface for WSL, PowerShell, and the Windows command line.

##  Step 2: Download the Text Generation Web UI GitHub Repository

 To download text-generation-web-ui-docker, [visit its GitHub page](https://github.com/Atinoda/text-generation-webui-docker "https://github.com/oobabooga/text-generation-webui"). You can download a ".zip" file containing all the files you need by clicking on the green "Code" button and then clicking on "Download Zip" from the drop-down menu.

 The screenshot below shows you where to find this on the GitHub page.

![Where to download the .zip file for a GitHub repository.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/download-zip-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Brad Morton / How-To Geek

[Extract the downloaded ZIP file](https://video-screen-grab.techidaily.com/updated-in-2024-essential-screen-capture-software-top-picks-ranked/) into its own folder, and then open the folder containing the unzipped files. Don't worry too much about the contents of this folder: it's all the moving parts for your AI chatbot, but Docker will take care of setting everything up for you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Step 3: Launch the Text Generation Web UI

 Before you launch text-generation-web-ui-docker, you need to make sure it's configured for your PC hardware. Edit the file **docker-compose.yml** to specify the variant that matches your hardware: **default-nvidia** or **default-cpu** (if you don't have a compatible GPU).

![Configuring the docker image variant in docker-compose.yml.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/variant.png) 

Brad Morton / How-To Geek

 Then, still in the folder containing the downloaded and extracted files, right-click on an empty space and click "Open in Terminal" to open the directory in a new [PowerShell](https://some-guidance.techidaily.com/updated-unleash-creativity-fast-windows-10-photo-edits-made-simple/) window.

![The location of the 'Open in Terminal' in the context menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/open-in-terminal.png) 

Brad Morton / How-To Geek

 Make sure Docker Desktop is running before typing in the following Docker command into the Terminal window:

docker compose up -d

 This command will do the following:

* Executes **docker compose**, the program that manages Docker applications
* Start the container using the **up** command
* Runs the container in the background (called detached mode, which is specified by the **\-d**)

![The command for bringing up a Docker container.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/up.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Brad Morton / How-To Geek

 If you haven't run this command before and the application needs to be downloaded (pulled), you might need to go and make a cup of tea, as it could take a while. Once the command has completed running successfully, you'll see that the text-generation-web-ui-docker Docker container has been created and started.

![Windows terminal showing the status of a newly created container.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/created.png) 

Brad Morton / How-To Geek

 The running container will also appear in Docker Desktop, where you can stop, start, and manage it.

![Docker Desktop showing a running container.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/docker.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Brad Morton / How-To Geek

##  Step 4: Install the GPT-2 Model From OpenAI

 Once text-generation-web-ui-docker is up and running in Docker, you can access it by typing the address **http://localhost:7860** into your browser's address bar. [Localhost](https://youtube-docs.techidaily.com/cing-creativity-and-monetization-in-youtube-shorts-for-2024/) is the address your computer uses to access services it is running itself, each of which is assigned a unique port number (in this case 7860). You can see what ports a running Docker container has made available on localhost by opening it in Docker desktop.

 This is an older version of GPT than you get when you use ChatGPT on the internet. Consequently, it won't be as smart or as intuitive as what you might expect, but it is customizable and private.

 Navigate to the Model tab in the web interface and enter **openai-community/gpt2** into the "Download model or LoRA" box, and then click the Download button. This might take a few minutes.

![Downloading a model for use in text-generation-web-ui.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/win-gpt-6.png) 

Brad Morton / How-To Geek

 Click the Refresh icon in the top-left, then select the newly downloaded openai-community/gpt2 from the adjacent Model drop-down menu. Finally, click the "Load" button, and wait a few minutes until you see a success message.

![Loading a model in text-generation-web-ui.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/win-gpt-7.png) 

Brad Morton / How-To Geek

 This model works out of the box, and doesn't require any signup. As you get into AI and want to experiment with different models and AI tools, you can find more on [HuggingFace](https://huggingface.co/ "https://huggingface.co/").

##  Step 5: Start Using Your Custom GPT AI Chatbot

 This isn't quite like the AI chatbots you're used to using online, which are already set up for general use that cover a lot of situations. You'll need to tell the model how to behave before interacting with it, otherwise its output will be a bit... unhinged.

![A slightly unhinged response from an AI model that needs configuration.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/win-gpt-8.png) 

Brad Morton / How-To Geek

_Hoo boy, while it got the right answer, this AI chatbot needs a bit of fine-tuning._ 

 There's a lot you can tweak, and it can be a bit clunky at first, but with practice and experience, you can build a chatbot that is specific to your own usage, and that keeps your data 100% on your own computer, which is great for business and other confidential use-cases. To learn how to configure and train your local GPT chatbot, check out the [text-generation-web-ui documentation](https://github.com/oobabooga/text-generation-webui/wiki "https://github.com/oobabooga/text-generation-webui/wiki") and the [OpenAI GP2 docs on HuggingFace](https://huggingface.co/docs/transformers/en/model%5Fdoc/gpt2#openai-gpt2 "https://huggingface.co/docs/transformers/en/model_doc/gpt2#openai-gpt2").

 If you want to generate images using AI from your Windows PC, [you can use Fooocus to get easier and more immediate results.](https://facebook-video-share.techidaily.com/updated-upgrading-your-videos-appeal-youtube-thumbnail-resizing/)

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
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-samsung-galaxy-s24-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Samsung Galaxy S24 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-ultimate-portable-solar-generator-unmatched-7-hour-runtime-after-just-one-full-charge-spotlight-on-zdnet/"><u>Discover the Ultimate Portable Solar Generator: Unmatched 7-Hour Runtime After Just One Full Charge - Spotlight on ZDNET</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expertly-selected-bests-in-vehicle-energy-storage-your-go-to-list-of-superior-car-battery-chargers-techwatch/"><u>Expertly Selected Bests in Vehicle Energy Storage: Your Go-To List of Superior Car Battery Chargers | TECHWATCH</u></a></li>
<li><a href="https://buynow-help.techidaily.com/exploring-the-unexpected-depths-of-yokus-island-express-an-enchanting-journey-revealed/"><u>Exploring the Unexpected Depths of Yoku's Island Express – An Enchanting Journey Revealed</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-itel-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Itel S23+? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-realme-c67-5g-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Realme C67 5G FRP Locks</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-how-to-manual-for-crafting-youtube-playlists/"><u>In 2024, How-To Manual for Crafting YouTube Playlists</u></a></li>
<li><a href="https://win-answers.techidaily.com/lost-ark-quiet-dilemma-solved-audio-fixes-inside/"><u>Lost Ark Quiet Dilemma Solved – Audio Fixes Inside!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/online-tiff-bmp/"><u>Online 무료 구현: TIFF 및 BMP 이미지를 원활하게 바꾸기 - 모바비</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-mordhau-game-crashes-effective-troubleshooting-steps/"><u>Resolving Mordhau Game Crashes: Effective Troubleshooting Steps</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/scorpius/"><u>Scorpius</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-to-choosing-home-energy-backup-systems-for-2ebr2024-in-depth-analysis-and-ratings-zdnet/"><u>Ultimate Guide to Choosing Home Energy Backup Systems for 2Ebr2024: In-Depth Analysis and Ratings | ZDNET</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-to-choosing-the-perfect-rv-power-station-comprehensive-testing-and-recommendations-cnet-gadgets/"><u>Ultimate Guide to Choosing the Perfect RV Power Station: Comprehensive Testing & Recommendations | CNET Gadgets</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-the-potential-for-terawatts-a-new-era-in-geothermal-technology-zdnet/"><u>Unlocking the Potential for Terawatts: A New Era in Geothermal Technology | ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unmissable-deal-alert-save-big-on-ugreen-gan-chargers-during-the-cyber-monday-rush-exclusive-20-off-tech-insights-from-zdnet/"><u>Unmissable Deal Alert: Save Big on Ugreen GaN Chargers During the Cyber Monday Rush - Exclusive 20% Off | Tech Insights From ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-zdnets-methodology-for-reviewing-compact-energy-storage-solutions-a-deep-dive-into-test-protocols/"><u>Unveiling ZDNet's Methodology for Reviewing Compact Energy Storage Solutions - A Deep Dive Into Test Protocols</u></a></li>
<li><a href="https://discover-helper.techidaily.com/winx-mediatrans-iphoneipadmv/"><u>WinX MediaTrans™: 最適合iPhone、iPad上移動照片及MV管理解決方案</u></a></li>
</ul></div>

