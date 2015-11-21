---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: "If you've been plugged into the Virtual Reality scene for the past two years you probably heard of GameFace Labs, a company working on the first true \"console on your face.\" Today I paid them a visit."
datePublished: '2015-11-21T14:58:47.133Z'
dateModified: '2015-11-21T14:58:39.245Z'
title: "Hands on with GameFace Labs' Latest Prototype"
author: []
sourcePath: _posts/2015-11-20-hands-on-with-gameface-labs-latest-prototype.md
published: true
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
url: hands-on-with-gameface-labs-latest-prototype/index.html
_type: Article

---
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/d0729e3c-c144-4f68-8609-c0c8929a8f58.jpg)

# 

# 

# Hands on with GameFace Labs' Latest Prototype

If you've been plugged into the Virtual Reality scene for the past two years you probably heard of GameFace Labs, a company that over the past couple of years has been working on the first true wireless, self-contained "console on your face." Today I paid them a visit. 

by Augmentl ([@augmentl][0]) on November 20th, 2015\.

The kind folks over at [GameFace Labs][1] ([@gamefacelabs][2]) hosted an open day in London to demonstrate their latest prototype hardware to devs and VR enthusiasts alike. As a member of the latter group I of course jumped at the opportunity as soon as the call went out on Reddit. On my way there I must admit that I did not really know what to expect. How would their HMD live up to their ambitious goals? How can we even really define what makes a console-like experience when mobile VR is advancing so rapidly? 

I'd first spoken to to the GameFace Labs team a couple of years back, when the Samsung GearVR was not yet announced and the DK1 was the best thing a VR enthusiast could get their hands on. Back then, the thought of a fully self contained VR headset capable of console-like gaming feats (["Like two Xbox-360's strapped to your face"][3]) was an ambitious dream - and arguably still is. So how had the GameFace hardware evolved in the face of a Mobile VR explosion? I was keen to find out. 
> 
> Like two Xbox-360's strapped to your face

The demo session was held in a well appointed flat near Euston, in London, lovingly populated by some impressive Dr Who memorabilia. This was not the team's permanent location, but rather a convenient space for a bit of demo action. The flat also sported a spacious living room area where the team gave their guests the opportunity to also experience one of the few HTC Vive headsets in the UK, an added bonus my impressions of which I'll discuss separately. 

At face value, the GameFace device looks like a robustly built, 3D printed prototype sporting two rather unusual features: a set of air vents for a small fan and an external battery pack. These are currently artefacts of the prototype's Nvidia Tegra K1 platform, whose power requirements in the context of the prototype build ended up somewhat exceeding the team's original expectations. 
I was in fact told that, contrary to the advertised 5W power draw, the K1 was normally pulling closer to 12W, occasionally peaking at 20W. The GameFace team hopes to address this aspect as they continue to iterate the prototype. 

Despite the physical bulk added by these constraints, I did not find the headset to be particularly heavy or uncomfortable, although I can't say whether that would have held true in a longer demo session. The same can't be said of the IPD which, not being adjustable in the current prototype, did cause some minor eye strain. The belt-clipped battery pack, while unusual, was not an issue and stayed neatly out of the way. I got to try a number of short demos on the GameFace hardware, from a lovely undersea scene in which I was surrounded by frolicking Dolphins, to a tour of the solar system, to a tabletop action game reminiscent of the classic Bomberman. These were a mix of Cardboard and custom demos, running on the headset's stock Android OS with a custom launcher UI. I was able to control most of these experiences with standard Bluetooth gamepad, whereas others required nothing more than gazing in the right direction. 

The device's screen is sharp and bright, with vivid colours, deep blacks and no visible black smearing. The screen door effect was present but easy to ignore. Having previously used a GearVR, I can confirm that at least visually the screen appears similar if not identical to that used in the Samsung Galaxy Note 4 powering the GearVR Innovator Edition. The perceived field of view is also very similar, not quite yet the 140º GameFace Labs are [ultimately aiming for.][3]
Low persistence was however clearly absent, which made the scene blur somewhat in response to rapid head movements. This is exacerbated by the overall latency of the system with regards to head tracking, which I found to be surprisingly lagging behind my experience of the GearVR. Indeed, despite the clarity of the display and the demo experiences appearing to run at a suitable frame rate, even small head movements resulted in that laggy, "swimmy" feeling that is closely associated with a higher risk of motion sickness in VR systems.

I'd guess I was experiencing something in the region of 100ms latency, a far cry from the accepted 20ms minimum for VR. GameFace claim the prototype's display runs at 60Hz full persistence, but I suspect they need to achieve a much closer integration between display drivers and IMU to reduce the overall motion-to-photon latency to an acceptable level. Much of the required performance improvements should be achievable in software, and GameFace Labs seem confident they can achieve their goals. These performance challenges however also highlight the advantage companies like Samsung have in this space, being able to optimise system latencies at all levels of the hardware stack, right down to the chipset (or in the case of QUALCOMM Snapdragon powered models, by having the sway needed to force QUALCOMM into optimising their SoC's as required).

> The team say they're close to completing their integration with Valve's Lighthouse technology

In terms of tracking, the GameFace headset currently features only simple rotational head tracking, the same as any mobile VR solutions currently on the market. That however is about to change, as the team say they're close to completing their integration with Valve's Lighthouse technology - as used in the HTC Vive - which will give their headset full positional tracking. 
GameFace Labs have also been experimenting with a wireless Softkinetic-like depth sensor mounted towards the user. Such a solution would ultimately allow for full body and hand tracking without the need for hand-held peripherals, but in my brief testing I experienced considerable latency and inconsistent hand tracking. Together with this solution's purported accuracy limitations - a centimetre as opposed to sub-millimetre - this tracking implementation seems more like an interesting experiment and less like a viable solution when compared to Valve's Lighthouse's more robust and accurate technology. 
> 
> Can the model of mobile VR represented by the GearVR and, to a lesser extent, the various iterations of Cardboard-like mobile head mounts, truly be challenged by a small, if highly motivated, independent startup? 

Overall, the GameFace remains the same ambitious undertaking it was two years ago, but one that is somewhat more difficult to place in the context of a post-GearVR world. While the team's future aspirations encompass 4K screens, Fresnel optics and much higher system performance, their device raises some interesting questions as to the future of mobile VR: can the model of mobile VR represented by the GearVR and, to a lesser extent, the various iterations of Cardboard-like mobile head mounts, truly be challenged by a small, if highly motivated, independent startup?

GameFace Labs say they will be showcasing a more refined iteration of their hardware at CES 2016\. If they are to truly stand out at the event, they will need to make significant progress in tackling system-wide latency issues, and perhaps showcase a first pass at their Lighthouse positional tracking integration. I for one wish them the best, and will be watching closely to see whether the unorthodox choices they have embarked on for their hardware will ultimately live up to their sizeable ambitions.

****

**Correction:** The original version of the article mistakenly mentioned Nvidia's Tegra X1 as the GameFace prototype's core platform. This has been amended to Nvidia Tegra K1\. 

[@augmentl
][4]

[0]: http://twitter.com/augmentl
[1]: http://gamefacelabs.com/
[2]: http://twitter.com/gamefacelabs
[3]: http://gamefacelabs.com/features.html
[4]: http://www.twitter.com/augmentl