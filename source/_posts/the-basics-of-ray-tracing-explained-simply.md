---
title: The Basics of Ray Tracing Explained Simply
date: 2024-11-20T07:29:17.513Z
updated: 2024-11-24T17:07:01.285Z
categories:
  - BestProducts
description: This Article Describes The Basics of Ray Tracing Explained Simply
excerpt: This Article Describes The Basics of Ray Tracing Explained Simply
thumbnail: https://www.lifewire.com/thmb/1-Yp1JIoL4O5iudaQ-YSTZFzypk=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/raytracingstarwars-b548b699b36b4bb8b4334d66a964ede9.jpg
---

## The Basics of Ray Tracing Explained Simply

Close 

 Games are more vivid than ever. This article explains how ray tracing makes the difference.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What is Ray Tracing? 

 Ray tracing is a technique for[ rendering](https://www.lifewire.com/what-is-rendering-1954) computer graphics that creates an image by tracing rays' path through a scene. The rays can interact with objects in the scene, bouncing off them and gaining properties, such as color.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Ray Tracing Works 

 Ray tracing emulates real-world lighting. The light we see is the result of photons emitted from energy sources, like the sun. Photons can bounce and scatter as they collide with objects. A mirror is all you need to see this in action. Light hitting a mirror creates a reflection.

 Ray tracing simulates this. The number of rays traced is paltry compared to the real world, where millions of photons bounce across our field of view. Modern games trace somewhere between one and four rays per pixel. Still, that's enough to simulate the real world.

![Vending machines in the game Cyberpunk 2077](https://www.lifewire.com/thmb/x9KVYNkfR_Bw9Oh5se9jeI8JiMQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/cyberpunk2077-2c97987534994d32afabd764b09bd682.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

CD Projekt Red

 Tracing the path of a ray also lets it interact with the game world. A ray that bounces off a red object can be influenced by that color, casting a red glow nearby. Rays can scatter in different ways based on the properties a game’s artists give to objects, allowing realistic semi-reflective or rough surfaces.

 Ray tracing is a significant step forward for 3D graphics. It creates a realistic image by simulating the path of rays as they move through a game.

 This leads to lighting that can interact with the environment even when the environment isn’t visible to the player. Ray tracing doesn’t require purpose-built hardware to function, but it's only practical on a video card or game console that can accelerate ray tracing because it's very demanding.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Ray Tracing vs. Rasterization 

 You may still be confused even if you understand this explanation. Reflections were present in past games, even those now several decades old. How is ray tracing different?

 Past 3D games, and most modern games, use rasterization. Rasterization combines the elements of a 3D game world visible to the player into a 2D image. It only renders what should be visible to the player, as any performance used to generate what the player can’t see is wasted. However, this creates a problem.

![Ray tracing in Battlefield 5](https://www.lifewire.com/thmb/r2mdM8eBZAKw6HdVsRn7mgJq7zQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/rtxraytracebattlefield5-50d78dc8c3a14f9cb996f5d83b2a3726.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Nvidia

 Let’s return to the example of a mirror. The player's environment and the player character aren’t visible to the player (in a first-person game, at least). With rasterization, there’s nothing for the mirror to reflect.

 Of course, mirrors exist in modern games. They render the scene twice. One pass is from the player’s point of view, while another is from a different perspective. That doubles the performance needed to render a scene, however.

 Screen space reflections, a technique in popular 3D game engines, use on-screen data to create a reflection. This technique is ideal for reflective surfaces at an angle to the player’s perspective, such as water. However, reflected objects disappear if the item reflected moves off-screen.

 Ray tracing doesn’t share these problems because, unlike rasterization, it can trace outside the player's perspective.

 Also, in games that allow rays to interact with surfaces, ray tracing can display realistic color bleed and semi-reflective surfaces difficult for rasterization to handle.

[ What to Look For in a Gaming PC ](https://www.lifewire.com/what-to-consider-before-buying-a-gaming-pc-5221042) 

##  What Hardware Does Ray Tracing Require? 

 Ray tracing isn't a new idea.[ Computer scientists experimented with ray tracing in the early 1980s](https://news.developer.nvidia.com/ray-tracing-from-the-1980s-to-today-an-interview-with-morgan-mcguire-nvidia/) , creating static images with realistic lighting, reflections, and shadows. Unfortunately, they took hours to render.

 A video game needs real-time ray tracing at 30 frames per second or higher. That’s only possible with a video card designed to accelerate ray tracing.

![Nvidia RTX 3080 graphics card on a black background](https://www.lifewire.com/thmb/QGQ2tBbyAIp9z2q6B2ZLBc7rQyU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/nvidiartx3080-43baad1d3a1e415a8e3760e81b0c5de0.jpg) 

Nvidia

 Nvidia’s RTX ray tracing relies on silicon called a Tensor Core. Tensor Cores are only found in RTX video cards. Nvidia’s GTX cards can render a game using ray tracing because, as said, ray tracing doesn’t require purpose-built silicon. However, performance is abysmal compared to RTX cards. And some games, like[ Minecraft with RTX ray tracing](https://www.lifewire.com/minecraft-gets-ray-tracing-update-windows-10-4802711) , require an RTX video card because of the specific way they enable ray tracing.

 AMD cards that accelerate ray tracing don’t have specific branding and don’t have dedicated silicon. Instead, they use hardware tweaks and software updates for better results. It’s more difficult to identify AMD cards that accelerate ray tracing, so pay attention to the details.

[  Xbox Series X vs Xbox Series S: How to Pick the Console Right for You ](https://www.lifewire.com/xbox-series-x-vs-xbox-series-s-5083862) 

 Sony’s[ PlayStation 5](https://www.lifewire.com/is-ps5-worth-it-8629161) and Xbox Series X and S have graphics hardware from AMD that can accelerate ray tracing. It’s up to developers to enable, however, and many games don’t. A notable example is[ _Cyberpunk 2077_ ](https://www.lifewire.com/cyberpunk-2077-has-everything-it-needs-to-be-great-5085210) , which supported RTX ray tracing on PC at launch but didn’t support ray tracing on next-gen consoles.

[ What Is an RTX Graphics Card? ](https://www.lifewire.com/rtx-graphics-card-8642473) 

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[ Subscribe ](https://www.lifewire.com/#) 

Tell us why!

 Other  Not enough details  Hard to understand 

 Submit 

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
<li><a href="https://article-posts.techidaily.com/new-eye-shadow-and-lips-tutorials-for-2024/"><u>[New] Eye Shadow & Lips Tutorials for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-essential-tips-for-harvesting-instagram-highlights/"><u>2024 Approved Essential Tips for Harvesting Instagram Highlights</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-key-steps-for-an-optimal-chromebook-zooming-experience/"><u>2024 Approved Key Steps for an Optimal Chromebook Zooming Experience</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unleash-the-power-of-words-crafting-impactful-documentary-narratives/"><u>2024 Approved Unleash the Power of Words Crafting Impactful Documentary Narratives</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>5 Easy Ways to Change Location on YouTube TV On Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/apple-showdown-m3-macbook-air-versus-m2-which-ultraportable-laptop-wins-for-tech-enthusiasts/"><u>Apple Showdown: M3 MacBook Air Versus M2 - Which Ultraportable Laptop Wins for Tech Enthusiasts?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-solutions-for-correcting-errors-related-to-coredll-not-found/"><u>Effective Solutions for Correcting Errors Related to Core.dll Not Found</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-how-to-terminate-your-paramount-premiere-membership/"><u>Guide: How to Terminate Your Paramount Premiere Membership</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-on-iphone-se-2022-without-password-by-drfone-ios/"><u>How to Delete iCloud Account On iPhone SE (2022) without Password?</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-integrating-royalty-free-songs-into-video-projects/"><u>In 2024, Integrating Royalty-Free Songs Into Video Projects</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-melodies-meet-graphics-adding-soundtracks-to-powerpoint/"><u>In 2024, Melodies Meet Graphics Adding Soundtracks to PowerPoint</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/iphone-16-innovations-unveiled-multi-dimensional-spatial-capture-and-slimmed-designs-across-every-model/"><u>IPhone 16 Innovations Unveiled: Multi-Dimensional Spatial Capture & Slimmed Designs Across Every Model</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/iphone-screenshot-capture-guide-mastering-screen-recording-features/"><u>IPhone Screenshot Capture Guide: Mastering Screen Recording Features</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-reasons-behind-the-move-towards-electric-automobiles/"><u>Unveiling the Reasons Behind the Move Towards Electric Automobiles</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/upcoming-m4-chips-powered-by-ai-set-to-transform-apples-entire-mac-lineup-anticipated-launch-dates-covered/"><u>Upcoming M4 Chips Powered by AI Set to Transform Apple’s Entire Mac Lineup – Anticipated Launch Dates Covered</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/why-you-should-consider-getting-an-apple-watch-a-wearable-tech-specialists-perspective-with-6-key-reasons/"><u>Why You Should Consider Getting an Apple Watch: A Wearable Tech Specialist's Perspective with 6 Key Reasons</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/zdnets-favorite-phones-how-our-team-chooses-and-utilizes-their-devices-daily/"><u>ZDNet's Favorite Phones: How Our Team Chooses and Utilizes Their Devices Daily</u></a></li>
</ul></div>

