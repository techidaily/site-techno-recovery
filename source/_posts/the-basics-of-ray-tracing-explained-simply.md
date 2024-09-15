---
title: The Basics of Ray Tracing Explained Simply
date: 2024-09-12T16:22:40.031Z
updated: 2024-09-15T16:21:55.080Z
categories:
  - BestProducts
description: This Article Describes The Basics of Ray Tracing Explained Simply
excerpt: This Article Describes The Basics of Ray Tracing Explained Simply
thumbnail: https://www.lifewire.com/thmb/1-Yp1JIoL4O5iudaQ-YSTZFzypk=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/raytracingstarwars-b548b699b36b4bb8b4334d66a964ede9.jpg
---

## The Basics of Ray Tracing Explained Simply

Close 

 Games are more vivid than ever. This article explains how ray tracing makes the difference.  

## What is Ray Tracing? 

 Ray tracing is a technique for[ rendering](https://www.lifewire.com/what-is-rendering-1954) computer graphics that creates an image by tracing rays' path through a scene. The rays can interact with objects in the scene, bouncing off them and gaining properties, such as color.

## How Ray Tracing Works 

 Ray tracing emulates real-world lighting. The light we see is the result of photons emitted from energy sources, like the sun. Photons can bounce and scatter as they collide with objects. A mirror is all you need to see this in action. Light hitting a mirror creates a reflection.

 Ray tracing simulates this. The number of rays traced is paltry compared to the real world, where millions of photons bounce across our field of view. Modern games trace somewhere between one and four rays per pixel. Still, that's enough to simulate the real world.

![Vending machines in the game Cyberpunk 2077](https://www.lifewire.com/thmb/x9KVYNkfR_Bw9Oh5se9jeI8JiMQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/cyberpunk2077-2c97987534994d32afabd764b09bd682.jpg) 

CD Projekt Red

 Tracing the path of a ray also lets it interact with the game world. A ray that bounces off a red object can be influenced by that color, casting a red glow nearby. Rays can scatter in different ways based on the properties a game’s artists give to objects, allowing realistic semi-reflective or rough surfaces.

 Ray tracing is a significant step forward for 3D graphics. It creates a realistic image by simulating the path of rays as they move through a game.

 This leads to lighting that can interact with the environment even when the environment isn’t visible to the player. Ray tracing doesn’t require purpose-built hardware to function, but it's only practical on a video card or game console that can accelerate ray tracing because it's very demanding.

##  Ray Tracing vs. Rasterization 

 You may still be confused even if you understand this explanation. Reflections were present in past games, even those now several decades old. How is ray tracing different?

 Past 3D games, and most modern games, use rasterization. Rasterization combines the elements of a 3D game world visible to the player into a 2D image. It only renders what should be visible to the player, as any performance used to generate what the player can’t see is wasted. However, this creates a problem.

![Ray tracing in Battlefield 5](https://www.lifewire.com/thmb/r2mdM8eBZAKw6HdVsRn7mgJq7zQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/rtxraytracebattlefield5-50d78dc8c3a14f9cb996f5d83b2a3726.jpg) 

Nvidia

 Let’s return to the example of a mirror. The player's environment and the player character aren’t visible to the player (in a first-person game, at least). With rasterization, there’s nothing for the mirror to reflect.

 Of course, mirrors exist in modern games. They render the scene twice. One pass is from the player’s point of view, while another is from a different perspective. That doubles the performance needed to render a scene, however.

 Screen space reflections, a technique in popular 3D game engines, use on-screen data to create a reflection. This technique is ideal for reflective surfaces at an angle to the player’s perspective, such as water. However, reflected objects disappear if the item reflected moves off-screen.

 Ray tracing doesn’t share these problems because, unlike rasterization, it can trace outside the player's perspective.

 Also, in games that allow rays to interact with surfaces, ray tracing can display realistic color bleed and semi-reflective surfaces difficult for rasterization to handle.

[ What to Look For in a Gaming PC ](https://www.lifewire.com/what-to-consider-before-buying-a-gaming-pc-5221042) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135370/19272" target="_top" id="2135370">
  <img src="//a.impactradius-go.com/display-ad/19272-2135370" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135370/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  What Hardware Does Ray Tracing Require? 

 Ray tracing isn't a new idea.[ Computer scientists experimented with ray tracing in the early 1980s](https://news.developer.nvidia.com/ray-tracing-from-the-1980s-to-today-an-interview-with-morgan-mcguire-nvidia/) , creating static images with realistic lighting, reflections, and shadows. Unfortunately, they took hours to render.

 A video game needs real-time ray tracing at 30 frames per second or higher. That’s only possible with a video card designed to accelerate ray tracing.

![Nvidia RTX 3080 graphics card on a black background](https://www.lifewire.com/thmb/QGQ2tBbyAIp9z2q6B2ZLBc7rQyU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/nvidiartx3080-43baad1d3a1e415a8e3760e81b0c5de0.jpg) 

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139116/17108" target="_top" id="2139116">
  <img src="//a.impactradius-go.com/display-ad/17108-2139116" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139116/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-all-you-need-to-know-understanding-video-aspect-ratios-on-youtube/"><u>[New] In 2024, All You Need to Know Understanding Video ASPECT RATIOS on YOUTUBE</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-expert-fb-media-downloader-enhanced-firefox-support/"><u>[New] In 2024, Expert FB Media Downloader Enhanced FireFox Support</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-snapstream-app-rating-analysis-for-2024/"><u>[Updated] SnapStream App Rating Analysis for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/demystifying-lg-channels-the-crucial-facts-you-cant-miss/"><u>Demystifying LG Channels – The Crucial Facts You Can't Miss</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-repair-your-computers-malfunctioning-optical-drive/"><u>How To Repair Your Computer's Malfunctioning Optical Drive</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-voice-commands-a-guide-to-enable-siris-text-to-speech-on-iphone-and-mac/"><u>Mastering Voice Commands: A Guide to Enable Siri's Text-to-Speech on iPhone & Mac</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Motorola Moto G34 5G | Dr.fone</u></a></li>
</ul></div>

