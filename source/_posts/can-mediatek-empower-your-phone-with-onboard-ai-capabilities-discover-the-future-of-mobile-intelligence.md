---
title: Can MediaTek Empower Your Phone with Onboard AI Capabilities? Discover the Future of Mobile Intelligence!
date: 2024-10-27T23:16:40.394Z
updated: 2024-10-30T22:16:28.697Z
tags:
  - edge-computing
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/b881275b4bc2df06c6167ef9042507061ece0c77/2023/08/22/397b3268-0085-47d4-81e0-226f7fbc0b84/gettyimages-1521580109.jpg?width=170&height=128&fit=crop&auto=webp
---

## Can MediaTek Empower Your Phone with Onboard AI Capabilities? Discover the Future of Mobile Intelligence!

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-perfect-pc-video-grabbers-a-comprehensible-selection/"><u>[New] 2024 Approved Perfect PC Video Grabbers A Comprehensible Selection</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-mastering-the-art-of-viral-video-marketing/"><u>[Updated] Mastering the Art of Viral Video Marketing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/amazon-elevates-voice-assistant-with-claude-from-anthropic-the-next-gen-alexa/"><u>Amazon Elevates Voice Assistant with Claude From Anthropic – The Next-Gen 'Alexa'</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/beyond-expectations-a-deep-dive-into-one-of-the-most-powerful-and-quality-bluetooth-speakers-not-from-sonos-or-bose/"><u>Beyond Expectations: A Deep Dive Into One of the Most Powerful and Quality Bluetooth Speakers - Not From Sonos or Bose</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/expert-reviews-ranking-the-10-most-effective-pc-video-editing-tools-of-the-year/"><u>Expert Reviews: Ranking the 10 Most Effective PC Video Editing Tools of the Year</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-any-infinix-note-30-5g-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Infinix Note 30 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-filmmaking-on-youtube-and-substitutes/"><u>In 2024, Mastering Filmmaking on YouTube & Substitutes</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/organize-and-share-music-how-to-make-youtube-playlists-easier/"><u>Organize and Share Music How to Make YouTube Playlists Easier</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-start-installing-dell-gaming-series-laptop-g15-drivers-on-your-pc/"><u>Quick Start: Installing Dell Gaming Series Laptop (G15) Drivers on Your PC</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/sonos-showdown-evaluating-the-era-100-against-the-sonos-one-to-decide-on-your-ultimate-smart-speaker/"><u>Sonos Showdown: Evaluating the Era 100 Against the Sonos One to Decide on Your Ultimate Smart Speaker</u></a></li>
<li><a href="https://win-cloud.techidaily.com/top-3-outils-gratuits-pour-la-sauvegarderecuperation-de-windows-11-guerir-vos-problemes-logiciels/"><u>Top 3 Outils Gratuits Pour La Sauvegarde/Récupération De Windows 11 : Guérir Vos Problèmes Logiciels</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-5-must-have-speaker-systems-a-comprehensive-guide-by-techradar/"><u>Top 5 Must-Have Speaker Systems : A Comprehensive Guide by TechRadar</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-noise-making-non-sonos-non-bose-bluetooth-speaker-beats-all-in-recent-tests-exclusive-review-on-zdnet/"><u>Top Noise-Making Non-Sonos, Non-Bose Bluetooth Speaker Beats All in Recent Tests - Exclusive Review on ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/under-300-and-exceptional-sound-quality-an-in-depth-review-of-the-sonos-one-gen-2-techradar/"><u>Under $300 and Exceptional Sound Quality – An In-Depth Review of the Sonos One (Gen 2) | TechRadar</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-ultimate-illusionist-companion-for-smart-homes-a-game-changing-light-projector-review-tech-innovation-spotlight/"><u>Unveiling the Ultimate Illusionist Companion for Smart Homes: A Game-Changing Light Projector Review | Tech Innovation Spotlight</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/zdnet-picks-highly-recommended-portable-sound-system-showcases-superior-acoustics-on-various-genres/"><u>ZDNet Picks Highly Recommended Portable Sound System, Showcases Superior Acoustics on Various Genres</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

