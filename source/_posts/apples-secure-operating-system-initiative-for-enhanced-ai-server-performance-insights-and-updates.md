---
title: Apple's Secure Operating System Initiative for Enhanced AI Server Performance – Insights & Updates
date: 2024-10-30T21:32:06.474Z
updated: 2024-11-05T19:22:54.144Z
tags:
  - apple
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/apple/    https://www.zdnet.com/a/img/resize/d6a9b3ca2f0c5c61dfb103b6bd4799793df261d7/2024/06/18/6c43cb6c-2ff7-4e6d-b41b-01bc5ab86ca3/private-cloud-compute-splash.png?width=170&height=96&fit=crop&format=pjpg&auto=webp
---

## 1. Apple's Secret Project: Crafting an Encrypted Operating System for Enhanced AI Data Center Security – Unveiled Insights

![private-cloud-compute-splash.png](https://www.zdnet.com/a/img/resize/6a55f443c4975694c93bbe4b1a6e34788d588daa/2024/06/18/26e555de-1eb0-40f8-80a2-d9c874a9adcd/private-cloud-compute-splash.png?auto=webp&width=1280)

Apple

During last week's introduction of [Apple Intelligence](https://www.zdnet.com/article/every-new-feature-apple-unveiled-for-iphone-ipad-mac-and-more-this-fall-including-ai/), Apple software engineering head Craig Federighi announced that the company will run some [generative AI models](https://www.zdnet.com/article/what-is-generative-ai-and-why-is-it-so-popular-heres-everything-you-need-to-know/) in a secure cloud computing environment.

Called [Private Cloud Compute](https://www.zdnet.com/article/heres-how-apples-keeping-your-cloud-processed-ai-data-safe-and-why-it-matters/) (PCC), the service will be subject to scrutiny by outside security experts. Federighi said: "Just like your iPhone, independent experts can inspect the code that runs on these servers to verify this privacy promise." The goal is to verify Apple's privacy promises, including that user data will never be stored on PCC servers and will be expunged from memory once a request is fulfilled. 

**Also:** [**Here's how Apple's keeping your cloud-processed AI data safe (and why it matters)**](https://www.zdnet.com/article/heres-how-apples-keeping-your-cloud-processed-ai-data-safe-and-why-it-matters/)

Federighi did not go into detail about how security researchers will inspect or audit the PCC servers, but [a subsequent Apple blog post](https://security.apple.com/blog/private-cloud-compute/) states the PCC servers will run a distinct version of the company's operating system software that researchers will be allowed to inspect. 

"When we launch Private Cloud Compute, we'll take the extraordinary step of making software images of every production build of PCC publicly available for security research," the Apple Security Engineering and Architecture and collaborating teams wrote.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

The blog post goes on to say that Apple will "periodically also publish a subset of the security-critical PCC source code, \[and\] in a first for any Apple platform, PCC images will include the sepOS firmware and the iBoot bootloader in plaintext, making it easier than ever for researchers to study these critical components."

Apple emphasizes that its devices "will be willing to send data only to PCC nodes that can cryptographically attest to running publicly listed software" as a means to ensure its privacy and security guarantees. 

Apple makes various promises about the safety and security of using Private Cloud Compute to process some AI tasks.

Apple

Apple provided little detail about the nature of the server software, other than the fact that it is a derivation of the iOS and MacOS operating systems. 

The servers will run on Apple's own computer chips, analogous to the iPhone, iPad, and Mac, powered by "a new operating system: a hardened subset of the foundations of iOS and macOS tailored to support large language model (LLM) inference workloads while presenting an extremely narrow attack surface. This allows us to take advantage of iOS security technologies such as [Code Signing](https://support.apple.com/guide/security/app-code-signing-process-sec7c917bf14/web) and [sandboxing](https://support.apple.com/guide/security/security-of-runtime-process-sec15bfe098e/web)."

**Also:** [**Apple's AI extravaganza left out 2 key advances - maybe next time?**](https://www.zdnet.com/article/apples-ai-extravaganza-left-out-2-key-advances-maybe-next-time/)

Apple's iOS and macOS are based on a combination of open-source technologies such as the [Darwin](https://en.wikipedia.org/wiki/Darwin%5F%28operating%5Fsystem%29) operating system, developed at Apple in the 1990s, [freeBSD](https://en.wikipedia.org/wiki/FreeBSD), and closed-source software developed at Apple.

It's unclear when developers will get a look at the new software. In the blog post, Apple researchers say they will give security researchers a "first look" at the software "soon." A note on [Apple's developer site](https://developer.apple.com/apple-intelligence/) says Apple Intelligence will be available "in an upcoming beta" without mentioning anything specific about PCC timing.

ZDNET's Maria Diaz [speculates](https://www.zdnet.com/article/heres-every-iphone-model-that-will-support-apples-latest-ai-features-for-now/) that iOS 18 betas will become available in July, although [Apple's website states](https://www.apple.com/apple-intelligence/) in a footnote that "Apple Intelligence will be available in beta on iPhone 15 Pro, iPhone 15 Pro Max, and iPad and Mac with M1 and later, with Siri and device language set to US English, as part of iOS 18, iPadOS 18, and macOS Sequoia this fall."

#### Apple

[iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")

[My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")

[We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")

[6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

* [iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")
* [My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")
* [We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")
* [6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-complete-control-over-clips-with-powerdirectors-latest-24-updates/"><u>[New] In 2024, Complete Control Over Clips with PowerDirector's Latest '24 Updates</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/uick-launch-long-growth-the-10-best-youtube-business-channels/"><u>[New] Quick Launch, Long Growth The 10 Best YouTube Business Channels</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ace-your-next-interview-with-expert-advice-on-responding-to-any-questions-insights-by-zdnet/"><u>Ace Your Next Interview with Expert Advice on Responding to Any Questions? - Insights by ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/artificial-intelligence-proficiency-vs-augmented-skills-influencing-employer-priorities-with-your-knowledge-zdnet/"><u>Artificial Intelligence Proficiency Vs. Augmented Skills: Influencing Employer Priorities with Your Knowledge | ZDNet</u></a></li>
<li><a href="https://tech-haven.techidaily.com/avoiding-data-retention-by-chatgpt-strategies-and-tips/"><u>Avoiding Data Retention by ChatGPT: Strategies and Tips</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/crafting-an-impactful-cover-letter-as-a-software-developer-strategies-that-make-you-stand-out-google/"><u>Crafting an Impactful Cover Letter as a Software Developer: Strategies That Make You Stand Out (Google)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/essential-tips-and-avoidances-in-crafting-an-impressive-cybersecurity-cv-insights-from-zdnet/"><u>Essential Tips & Avoidances in Crafting an Impressive Cybersecurity CV: Insights From ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/evaluating-mbas-for-career-growth-are-the-advantages-greater-than-the-expenses-expert-analysis-by-zdnet/"><u>Evaluating MBAs for Career Growth: Are The Advantages Greater Than The Expenses? - Expert Analysis by ZDNet</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/everywheres-top-app-by-apple/"><u>Everywhere's Top App by Apple</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guiding-force-of-stack-overflow-unveils-secrets-to-dominating-as-number-one-for-developers-techdigest/"><u>Guiding Force of Stack Overflow Unveils Secrets to Dominating as Number One for Developers | TechDigest</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-generative-ai-is-transforming-careers-in-tech-essential-insights-zdnet/"><u>How Generative AI Is Transforming Careers in Tech: Essential Insights | ZDNet</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-beyond-zoom-the-intricacies-of-iphone-xs-lens-tech/"><u>In 2024, Beyond Zoom The Intricacies of iPhone X's Lens Tech</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-turn-off-find-my-iphone-15-pro-when-phone-is-broken-drfone-by-drfone-ios/"><u>In 2024, How to Turn Off Find My iPhone 15 Pro when Phone is Broken? | Dr.fone</u></a></li>
<li><a href="https://os-tips.techidaily.com/lower-cost-repairs-await-apples-newest-iphone-the-15-pro/"><u>Lower Cost Repairs Await Apple's Newest iPhone: The 15 Pro</u></a></li>
<li><a href="https://games-able.techidaily.com/playstation-plus-vs-xbox-games-galore/"><u>PlayStation Plus vs Xbox Games Galore</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/revitalizing-tech-teams-with-ai-combatting-job-burnout-and-alert-fatigue-in-information-technology-careers-zdnet/"><u>Revitalizing Tech Teams with AI: Combatting Job Burnout and Alert Fatigue in Information Technology Careers | ZDNET</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-to-enhancing-your-linkedin-profile-with-new-skills-and-certifications-zdnet/"><u>Step-by-Step Guide to Enhancing Your LinkedIn Profile with New Skills and Certifications | ZDNet</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-6-benefits-of-mastering-chatgpt-for-job-hunters-and-employees/"><u>Top 6 Benefits of Mastering ChatGPT for Job Hunters and Employees</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-itel-p40plus-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Itel P40+ | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886019/19272" target="_top" id="1886019">
  <img src="//a.impactradius-go.com/display-ad/19272-1886019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886019/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

