---
title: "Handheld Learning: How AI Could Revolutionize Our Pockets by 2024 - Insights"
date: 2024-12-22T05:55:05.299Z
updated: 2024-12-26T02:57:34.232Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/acb788606a304c096daa8263d45d00ea2b9351615c5d83ea5a34a4991c1927bf.jpg
---

## Handheld AI: Will 2024 Revolutionize Learning On-the-Go? Insights

![man using phone](https://www.zdnet.com/a/img/resize/6cea2486f218870c083e8791504afe595f919250/2024/01/29/4ba711be-5530-4275-a6be-00ad401eea03/gettyimages-1440417504.jpg?auto=webp&width=1280)

Ippei Naoi/Getty Images

The world of [artificial intelligence](https://www.zdnet.com/article/what-is-ai-heres-everything-you-need-to-know-about-artificial-intelligence/) (AI) mostly exists in cloud-computing facilities and rarely touches your smartphone. When you use a tool like [ChatGPT to answer a prompt](https://www.zdnet.com/article/how-to-write-better-chatgpt-prompts-in-5-steps/), the hard work of training the program, so that it functions properly, has been done days, weeks, and months before, behind the scenes, in the enormous AI data centers built by Microsoft and others. 

However, 2024 could be the year the divide is crossed -- and it could be when AI starts to learn in your pocket. Efforts are underway to make it possible to train a neural net -- even a large language model (LLM) -- on your personal device, with little or no connection to the cloud. 

**Also: [I'm taking AI image courses for free on Udemy with this little trick - and you can too](https://www.zdnet.com/article/im-taking-ai-image-courses-for-free-on-udemy-with-this-little-trick-and-you-can-too/)**

The most obvious benefits of on-device training include: avoiding the delay incurred by having to connect to the cloud; learning from local information on a constant and personalized manner; and preserving privacy that would be violated by sending personal data to a cloud data center. 

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

The impact of on-device training could be a transformation in the capabilities of neural networks. AI could be personalized to your own actions as you walk around, tapping, scrolling, and dragging. AI could learn from the environments you pass through during your daily routine, gathering signs about the world. 

**Also:** [**How Apple's AI advances could make or break the iPhone 16**](https://www.zdnet.com/article/how-apples-ai-advances-could-make-or-break-the-iphone-16/)

[Recent work by Apple engineers](https://www.zdnet.com/article/how-apples-ai-advances-could-make-or-break-the-iphone-16/) suggests the company is looking to bring larger neural networks, the "generative" kind represented by OpenAI's [ChatGPT](https://www.zdnet.com/article/what-is-chatgpt-and-why-does-it-matter-heres-everything-you-need-to-know/), to run locally on the iPhone.

More broadly, Google introduced a radically scaled-down AI approach called [TinyML](https://www.zdnet.com/article/google-ai-executive-sees-a-world-of-trillions-of-devices-untethered-from-human-care/) several years ago. TinyML can run neural nets in devices with as little as a milliwatt of power, such as smart sensors placed on machinery. 

The greater challenge for technology companies is to make those kinds of neural networks not just perform predictions on a phone, but also learn new things on a phone -- to carry out training locally. 

That effort takes far more processing power, far more memory, and far more bandwidth for any computer to train a neural net than to use the finished neural net to make predictions.

**Also:** [**Machine learning at the edge: TinyML is getting big**](https://www.zdnet.com/article/machine-learning-at-the-edge-tinyml-is-getting-big/)

Efforts have been underway to conquer that computing mountain by doing things such as selectively updating only portions of the neural net's "weights" or "parameters." A signature effort there is MIT's [TinyTL](https://hanlab.mit.edu/projects/tinytl), which uses what's called transfer learning as a way to refine a neural net that is already mostly trained. 

TinyTL has so far been used for small things, such as facial recognition. But the state of the art is now moving to tackling the LLMs of generative AI, including OpenAI's [GPT-4](https://www.zdnet.com/article/what-is-gpt-4-heres-everything-you-need-to-know/). The LLMs have hundreds of billions of neural weights that need to be kept in memory, and then passed to the processor to be updated as new information comes in. This training challenge takes place on a scale never before attempted. 

**Also: [7 ways to make sure your data is ready for generative AI](https://www.zdnet.com/article/7-ways-to-make-sure-your-data-is-ready-for-generative-ai/)**

[A research report this month](https://www.mdpi.com/2079-9292/13/2/402) by staff at European chip-making giant STMicroelectronics makes the case that it's not enough in these training efforts to perform inference on mobile devices -- instead, the client device must also train the neural network to keep it fresh.

"Enabling only model's inference on the device is not enough," write Danilo Pietro Pau and Fabrizio Maria Aymone. "The performance of the AI models, in fact, deteriorates as time passes since the last training cycle; phenomenon known as concept drift," for which the solution is to update the program with new training data. 

**Also:** [**How Google and OpenAI prompted GPT-4 to deliver more timely answers**](https://www.zdnet.com/article/how-google-and-openai-prompted-gpt-4-to-deliver-more-timely-answers/)

The authors suggest slimming down a neural net, so it's easier to train a model on a memory-constrained device. Specifically, they experiment with removing what's called "back-propogation", the mathematical method in LLMs that is the most compute-intensive part of training. 

Pau and Aymone found that replacing back-propogation with simpler math could reduce the amount of on-device memory needed for the neural weights by as much as 94%.

Some scientists advocate for splitting up the training task among many client devices, which is called "federated learning".

Federated learning in action.

QMUL

Researchers Chu Myaet Thwal and team at Kyung Hee University [this month adapted](https://arxiv.org/pdf/2401.11652.pdf) a form of LLM used for image recognition across as many as 50 workstation computers, each running a single Nvidia GPU gaming card. Their code took less memory on the device to train than the standard version of the neural net without losing accuracy.

Some experts, meanwhile, argue network communications will have to be adjusted, so mobile devices can communicate better when performing federated learning. 

**Also:** [**AI will change software development in massive ways, says MongoDB CTO**](https://www.zdnet.com/article/ai-is-going-to-change-software-development-in-massive-ways-says-mongodb-cto/)

Scholars at the Institute for Electrical and Electronic Engineering [this month hypothesized](https://arxiv.org/pdf/2401.02662.pdf) a communications network using the forthcoming 6G standard, where the bulk of LLM training is completed first in a data center. Then, the cloud coordinates a bunch of client devices that "fine-tune" the LLM with local data.

Such "federated fine-tuning", where each device learns some portion of an LLM, without starting from scratch, can be done with a lot less processing power on the battery-powered device than in full training.

Many approaches aim to reduce the memory and processing required for each neural weight. The ultimate approach is what's called "binary neural networks", where instead of each weight having a numeric value, the weights have only a one or a zero, which vastly reduces the amount of on-device storage required.

**Also:** [**Problems scaling AI? MIT proposes sub-photon optical deep learning at the edge**](https://www.zdnet.com/article/problem-scaling-ai-mit-proposes-sub-photon-optical-deep-learning-at-the-edge/)

A lot of the technical concerns mentioned above sound abstract, but consider some of the use cases of training a neural net locally. 

A team at Nanyang Technological University in Singapore [this month used on-device learning](https://arxiv.org/abs/2401.11968) to counter cyber threats by having each individual device train its own local version of an AI-based "intrusion-detection system" or IDS, which is a common cybersecurity program.

Instead of the client devices having to interact with a central server, the team was able to download an initial draft of the IDS code and then fine-tune it for local security conditions. Not only is such training more specific to a local security threat, it also prevents the passing of sensitive security information back and forth over the network, where it could be intercepted by malicious parties.

Apple is [rumored to be eyeing greater on-board AI functionality](https://www.zdnet.com/article/how-apples-ai-advances-could-make-or-break-the-iphone-16/) for iOS devices and has offered clues to what could be completed in a mobile context. 

In [a paper in August](https://arxiv.org/abs/2308.08726), Apple scientists described a way to automatically learn the qualities of mobile apps, called the Never-ending UI Learner. The program runs on a smartphone and automatically presses buttons and undertakes other interactions to determine which kinds of controls a user interface requires. 

Apple

The aim is to use each device to automatically learn, rather than relying on a bunch of human workers who spend their time pressing buttons and annotating app functions.

The experiment was undertaken in a controlled setting by Apple staff. If the trial was attempted in the wild using real customers' iPhones, then "a privacy-preserving approach would be needed (e.g., on-device training)," the authors write.

Another mobile-based concept was [described by Apple scientists in 2022](https://arxiv.org/abs/2207.08988) in a paper titled "Training Large-Vocabulary Neural Language Models by Private Federated Learning for Resource-Constrained Devices". 

Their goal was to train speech-recognition AI on mobile devices using the federated learning approach. 

**Also:** [**Nvidia makes the case for the AI PC at CES 2024**](https://www.zdnet.com/article/nvidia-makes-the-case-for-the-ai-pc-at-ces-2024/)

Each person's device uses samples of interactions with a "voice assistant" (probably Siri) to train the neural net. Then, the neural network parameters developed by each phone are sent to the network, where they're aggregated to make one improved neural net.

The big takeaway from all these research efforts is that scientists are hard at work trying to find ways of compressing and dividing the work of training to make it feasible on battery-operated devices with less memory and less processing power than workstations and servers. 

Whether this research effort breaks through in 2024 remains to be seen. However, what's already clear is that the training of neural networks is going to move out of the cloud and, quite possibly, into the palm of your hand.

#### Artificial Intelligence

[How I used ChatGPT to scan 170k lines of code in seconds and save me hours of detective work](https://www.zdnet.com/article/how-chatgpt-scanned-170k-lines-of-code-in-seconds-and-saved-me-hours-of-work/ "How I used ChatGPT to scan 170k lines of code in seconds and save me hours of detective work")

[6 ways to write better ChatGPT prompts - and get the results you want faster](https://www.zdnet.com/article/6-ways-to-write-better-chatgpt-prompts-and-get-the-results-you-want-faster/ "6 ways to write better ChatGPT prompts - and get the results you want faster")

[6 digital twin building blocks businesses need - and how AI fits in](https://www.zdnet.com/article/6-digital-twin-building-blocks-businesses-need-and-how-ai-fits-in/ "6 digital twin building blocks businesses need - and how AI fits in")

[Google's Gems are a gentle introduction to AI prompt engineering](https://www.zdnet.com/article/googles-gems-are-a-gentle-introduction-to-ai-prompt-engineering/ "Google's Gems are a gentle introduction to AI prompt engineering")

* [How I used ChatGPT to scan 170k lines of code in seconds and save me hours of detective work](https://www.zdnet.com/article/how-chatgpt-scanned-170k-lines-of-code-in-seconds-and-saved-me-hours-of-work/ "How I used ChatGPT to scan 170k lines of code in seconds and save me hours of detective work")
* [6 ways to write better ChatGPT prompts - and get the results you want faster](https://www.zdnet.com/article/6-ways-to-write-better-chatgpt-prompts-and-get-the-results-you-want-faster/ "6 ways to write better ChatGPT prompts - and get the results you want faster")
* [6 digital twin building blocks businesses need - and how AI fits in](https://www.zdnet.com/article/6-digital-twin-building-blocks-businesses-need-and-how-ai-fits-in/ "6 digital twin building blocks businesses need - and how AI fits in")
* [Google's Gems are a gentle introduction to AI prompt engineering](https://www.zdnet.com/article/googles-gems-are-a-gentle-introduction-to-ai-prompt-engineering/ "Google's Gems are a gentle introduction to AI prompt engineering")

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
<li><a href="https://instagram-video-files.techidaily.com/new-expedient-techniques-to-spot-and-expel-deceptive-insta-connections-for-2024/"><u>[New] Expedient Techniques to Spot and Expel Deceptive Insta Connections for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-from-paper-to-cloud-preserving-old-family-photographs/"><u>[Updated] 2024 Approved From Paper to Cloud Preserving Old Family Photographs</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-masterful-video-starts-get-them-for-free/"><u>[Updated] Masterful Video Starts, Get Them for Free</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discovering-the-hidden-world-of-facebook-marketplace-how-to-access-it-now/"><u>Discovering the Hidden World of Facebook Marketplace – How to Access It Now</u></a></li>
<li><a href="https://technical-tips.techidaily.com/free-and-effective-unveiling-the-5-leading-malware-removal-utilities/"><u>Free and Effective: Unveiling the 5 Leading Malware Removal Utilities</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/guarded-communication-the-risks-of-ai-data-sharing/"><u>Guarded Communication: The Risks of AI Data Sharing</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-these-10-custom-gpt-variants-outshine-original-chatgpt-features/"><u>How These 10 Custom GPT Variants Outshine Original ChatGPT Features</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-successfully-fix-a-broken-motherboard-checksum-issue/"><u>How to Successfully Fix a Broken Motherboard Checksum Issue</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/inside-the-world-of-multi-screen-leveraging-pip-on-android-smartphones/"><u>Inside the World of Multi-Screen: Leveraging PiP on Android Smartphones</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-there-a-global-glitch-investigating-possible-outages-with-the-nintendo-switch-online/"><u>Is There a Global Glitch? Investigating Possible Outages with the Nintendo Switch Online.</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/spotify-trouble-here-are-13-fixes-to-get-your-tunes-running-again-in-android-auto-mode/"><u>Spotify Trouble? Here Are 13 Fixes to Get Your Tunes Running Again in Android Auto Mode</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-tutorial-building-a-homemade-projector-screen-from-scratch/"><u>Step-by-Step Tutorial: Building a Homemade Projector Screen From Scratch</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/syncing-emails-made-easy-adding-gmail-to-your-apple-watch/"><u>Syncing Emails Made Easy: Adding Gmail to Your Apple Watch</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-realme-11x-5g-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Realme 11X 5G | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-top-fdm-resin-and-economy-3d-printers-of-2024-your-comprehensive-list/"><u>Unveiling the Top FDM, Resin, and Economy 3D Printers of 2024: Your Comprehensive List</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-top-picks-best-free-tunes-streaming-apps-on-android-and-ios/"><u>Unveiling the Top Picks: Best Free Tunes Streaming Apps on Android & iOS</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-shrink-your-webm-videos-best-online-compression-services-for-2024/"><u>Updated Shrink Your WebM Videos Best Online Compression Services for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

