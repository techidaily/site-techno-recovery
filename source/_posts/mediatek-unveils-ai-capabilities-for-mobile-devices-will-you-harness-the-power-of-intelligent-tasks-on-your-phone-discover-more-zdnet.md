---
title: MediaTek Unveils AI Capabilities for Mobile Devices – Will You Harness the Power of Intelligent Tasks on Your Phone? Discover More | ZDNet
date: 2024-10-28T04:45:57.276Z
updated: 2024-10-30T16:34:07.022Z
tags:
  - edge-computing
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a080ef814e8219bc0372e6a68a593bc00b4cb1212abb381c555dc4e79829ce23.jpg
---

## MediaTek Unveils AI Capabilities for Mobile Devices – Will You Harness the Power of Intelligent Tasks on Your Phone? Discover More | ZDNet

![using phone](https://www.zdnet.com/a/img/resize/9a3f2a81298c671fac8f4a9c031b59b1e87c35d8/2023/08/22/397b3268-0085-47d4-81e0-226f7fbc0b84/gettyimages-1521580109.jpg?auto=webp&width=1280)

d3sign/Getty Images

Generative AI, one of the hottest growing technologies, is used by [OpenAI's ChatGPT](https://www.zdnet.com/article/what-is-chatgpt-and-why-does-it-matter-heres-everything-you-need-to-know/) and [Google Bard](https://www.zdnet.com/article/what-is-google-bard-heres-everything-you-need-to-know/) for chat and by image generation systems such as [Stable Diffusion](https://www.zdnet.com/article/how-to-use-stable-diffusion-ai-to-create-amazing-images/) and [DALL-E](https://www.zdnet.com/article/how-to-use-dall-e-2-to-turn-your-creative-visions-into-ai-generated-art/). Still, it has certain limitations because these tools require the use of cloud-based data centers with hundreds of GPUs to perform the computing processes needed for every query. 

But one day you could run [generative AI](https://www.zdnet.com/article/what-is-generative-ai-and-why-is-it-so-popular-heres-everything-you-need-to-know/) tasks directly on your mobile device. Or your connected car. Or in your living room, bedroom, and kitchen on smart speakers like Amazon Echo, Google Home, or Apple HomePod.

**Also: [Your next phone will be able to run generative AI tools (even in Airplane Mode)](https://www.zdnet.com/article/your-next-phone-will-be-able-to-run-generative-ai-tools-even-in-airplane-mode/)**

MediaTek believes this future is closer than we realize. Today, the Taiwan-based semiconductor company announced that it is working with Meta to port the social giant's [Lllama 2](https://www.zdnet.com/article/meta-releases-big-new-open-source-ai-large-language-model/) LLM -- in combination with the [company's latest-generation APUs](https://www.mediatek.com/technology/ai-for-smartphones-6th-gen) and [NeuroPilot](https://neuropilot.mediatek.com/) software development platform -- to run generative AI tasks on devices without relying on external processing.

Of course, there's a catch: This won't eliminate the data center entirely. Due to the size of LLM datasets (the number of parameters they contain) and the storage system's required performance, you still need a data center, albeit a much smaller one. 

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

For example, Llama 2's "small" dataset is 7 billion parameters, or about 13GB, which is suitable for some rudimentary generative AI functions. However, a much larger version of 72 billion parameters requires a lot more storage proportionally, even using advanced data compression, which is outside the practical capabilities of today's smartphones. Over the next several years, LLMs in development will easily be 10 to 100 times the size of Llama 2 or [GPT-4](https://www.zdnet.com/article/what-is-gpt-4-heres-everything-you-need-to-know/), with storage requirements in the hundreds of gigabytes and higher. 

That's hard for a smartphone to store and have enough IOPS for database performance, but certainly not for specially designed cache appliances with fast flash storage and terabytes of RAM. So, for Llama 2, it is possible today to host a device optimized for serving mobile devices in a single rack unit without all the heavy compute. It's not a phone, but it's pretty impressive anyway!

**Also: [The best AI chatbots of 2023: ChatGPT and alternatives](https://www.zdnet.com/article/best-ai-chatbot/)**

MediaTek expects Llama 2-based AI applications to become available for smartphones powered by their next-generation flagship SoC, scheduled to hit the market by the end of the year.

For on-device generative AI to access these datasets, mobile carriers would have to rely on low-latency edge networks -- small data centers/equipment closets with fast connections to the 5G towers. These data centers would reside directly on the carrier's network, so LLMs running on smartphones would not need to go through many network "hops" before accessing the parameter data.

In addition to running AI workloads on device using specialized processors such as MediaTek's, domain-specific LLMs can be moved closer to the application workload by running in a hybrid fashion with these caching appliances within the miniature datacenter -- in a "constrained device edge" scenario.

**Also: [These are my 5 favorite AI tools for work](https://www.zdnet.com/article/these-are-my-5-favorite-ai-tools-for-work/)**

So, what are the benefits of using on-device generative AI? 

* **Reduced latency:** Because the data is being processed on the device itself, the response time is reduced significantly, especially if localized cache methodologies are used by frequently accessed parts of the parameter dataset.
* **Improved data privacy:** By keeping the data on the device, that data (such as a chat conversation or training submitted by the user) isn't transmitted through the data center; only the model data is.
* **Improved bandwidth efficiency:** Today, generative AI tasks require all data from the user conversation to go back and forth to the data center. With localized processing, a large amount of this occurs on the device.
* **Increased operational resiliency:** With on-device generation, the system can continue functioning even if the network is disrupted, particularly if the device has a large enough parameter cache.
* **Energy efficiency:** It doesn't require as many compute-intensive resources at the data center, or as much energy to transmit that data from the device to the data center.

However, achieving these benefits may involve splitting workloads and using other load-balancing techniques to alleviate centralized data center compute costs and network overhead.

In addition to the continued need for a fast-connected edge data center (albeit one with vastly reduced computational and energy requirements), there's another issue: Just how powerful an LLM can you really run on today's hardware? And while there is less concern about on-device data being intercepted across a network, there is the added security risk of sensitive data being penetrated on the local device if it isn't properly managed -- as well as the challenge of updating the model data and maintaining data consistency on a large number of distributed edge caching devices. 

**Also: [How edge-to-cloud is driving the next stage of digital transformation](https://www.zdnet.com/article/how-edge-to-cloud-is-driving-the-next-stage-of-digital-transformation/)**

And finally, there is the cost: Who will foot the bill for all these mini edge datacenters? Edge networking is employed today by Edge Service Providers (such as Equinix), which is needed by services such as Netflix and Apple's iTunes, traditionally not mobile network operators such as AT&T, T-Mobile, or Verizon. Generative AI services providers such as OpenAI/Microsoft, Google, and Meta would need to work out similar arrangements. 

There are a lot of considerations with on-device generative AI, but it's clear that tech companies are thinking about it. Within five years, your on-device intelligent assistant could be thinking all by itself. Ready for AI in your pocket? It's coming -- and far sooner than most people ever expected. 

#### Artificial Intelligence

[Photoshop vs. Midjourney vs. DALL-E 3: Only one AI image generator passed my 5 tests](https://www.zdnet.com/article/is-photoshops-new-text-to-image-as-good-as-midjourney-and-dall-e-we-test-it-and-see/ "Photoshop vs. Midjourney vs. DALL-E 3: Only one AI image generator passed my 5 tests")

[AI-powered 'narrative attacks' a growing threat: 3 defense strategies for business leaders](https://www.zdnet.com/article/ai-powered-narrative-attacks-a-growing-threat-3-defense-strategies-for-business-leaders/ "AI-powered 'narrative attacks' a growing threat: 3 defense strategies for business leaders")

[Copilot Pro vs. ChatGPT Plus: Which AI chatbot is worth your $20 a month?](https://www.zdnet.com/article/copilot-pro-vs-chatgpt-plus-which-is-ai-chatbot-is-worth-your-20-a-month/ "Copilot Pro vs. ChatGPT Plus: Which AI chatbot is worth your $20 a month?")

[How my 4 favorite AI tools help me get more done at work](https://www.zdnet.com/article/how-my-4-favorite-ai-tools-help-me-get-more-done-at-work/ "How my 4 favorite AI tools help me get more done at work")

* [Photoshop vs. Midjourney vs. DALL-E 3: Only one AI image generator passed my 5 tests](https://www.zdnet.com/article/is-photoshops-new-text-to-image-as-good-as-midjourney-and-dall-e-we-test-it-and-see/ "Photoshop vs. Midjourney vs. DALL-E 3: Only one AI image generator passed my 5 tests")
* [AI-powered 'narrative attacks' a growing threat: 3 defense strategies for business leaders](https://www.zdnet.com/article/ai-powered-narrative-attacks-a-growing-threat-3-defense-strategies-for-business-leaders/ "AI-powered 'narrative attacks' a growing threat: 3 defense strategies for business leaders")
* [Copilot Pro vs. ChatGPT Plus: Which AI chatbot is worth your $20 a month?](https://www.zdnet.com/article/copilot-pro-vs-chatgpt-plus-which-is-ai-chatbot-is-worth-your-20-a-month/ "Copilot Pro vs. ChatGPT Plus: Which AI chatbot is worth your $20 a month?")
* [How my 4 favorite AI tools help me get more done at work](https://www.zdnet.com/article/how-my-4-favorite-ai-tools-help-me-get-more-done-at-work/ "How my 4 favorite AI tools help me get more done at work")

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
<li><a href="https://youtube-web.techidaily.com/ed-enhance-your-contents-visibility-peak-days-for-2024/"><u>[Updated] Enhance Your Content's Visibility - Peak Days for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-unleash-your-videos-potential-thriving-in-youtube-rankings/"><u>[Updated] Unleash Your Video's Potential Thriving in YouTube Rankings</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/are-gpt-3-experts-overtaking-ai-researchers-in-popularity-for-top-tech-career-insights-from-a-zdnet-analysis/"><u>Are GPT-3 Experts Overtaking AI Researchers in Popularity for Top Tech Career: Insights From a ZDNet Analysis</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/behind-the-headlines-why-job-reductions-at-leading-technology-companies-tell-a-different-tale-zdnet/"><u>Behind the Headlines: Why Job Reductions at Leading Technology Companies Tell a Different Tale | ZDNET</u></a></li>
<li><a href="https://technical-tips.techidaily.com/blue-screen-blues-discover-8-fixes-to-restore-your-tv-displays-true-colors/"><u>Blue Screen Blues? Discover 8 Fixes to Restore Your TV Display's True Colors</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/bridging-the-gap-in-remote-teams-a-critical-analysis-of-hybrid-workplace-solutions-by-zdnet/"><u>Bridging the Gap in Remote Teams: A Critical Analysis of 'Hybrid Workplace Solutions' By ZDNet</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/brother-hl-l2350dw-printer-software-downloader-latest-drivers-and-updates/"><u>Brother HL-L2350DW Printer Software Downloader: Latest Drivers and Updates</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/choosing-the-right-bootcamp-the-ultimate-list-of-leading-coding-schools/"><u>Choosing the Right Bootcamp: The Ultimate List of Leading Coding Schools</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comparing-remote-work-and-in-office-setup-unveiling-pros-and-potential-pitfalls-on-zdnet/"><u>Comparing Remote Work and In-Office Setup: Unveiling Pros & Potential Pitfalls on ZDNet</u></a></li>
<li><a href="https://common-error.techidaily.com/et3rminate-all-unnecessary-applications-running-in-the-background-that-might-be-hogging-system-resources-which-could-potentially-help-with-driver-installati143/"><u>e.t3rminate All Unnecessary Applications Running in the Background that Might Be Hogging System Resources, Which Could Potentially Help with Driver Installation Issues.</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/free-streaming-of-amazing-sci-fi-blockbusters-secrets-for-accessing-epic-galactic-adventures-at-no-charge/"><u>Free Streaming of Amazing Sci-Fi Blockbusters: Secrets for Accessing Epic Galactic Adventures at No Charge</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/galaxy-s20-video-playback-compatible-audio-and-video-codecs/"><u>Galaxy S20 Video Playback: Compatible Audio & Video Codecs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-your-honor-magic-5-pro-lock-screen-password-by-drfone-android/"><u>How to Reset your Honor Magic 5 Pro Lock Screen Password</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-5-from-zte-nubia-flip-5g-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 5 from ZTE Nubia Flip 5G to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigate-the-nerves-of-a-fresh-start-mastering-career-transition-anxiety-with-advice-from-zdnet/"><u>Navigate the Nerves of a Fresh Start: Mastering Career Transition Anxiety with Advice From ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/networking-strategies-for-the-shy-professional-insights-from-zdnet/"><u>Networking Strategies for the Shy Professional: Insights From ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/strategies-for-securing-your-next-position-without-risking-current-employment/"><u>Strategies for Securing Your Next Position Without Risking Current Employment</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123736/7443" target="_top" id="2123736">
  <img src="//a.impactradius-go.com/display-ad/7443-2123736" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123736/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

