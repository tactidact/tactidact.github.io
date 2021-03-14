---
title: "Apple M1 Macbook Air"
date: 2021-02-20T22:22:08+05:00
slug: ""
description: ""
keywords: []
draft: false
tags: [Apple, Apple Silicon, Apple M1, MacBook, MacBook Air]
math: false
toc: false
---

So I've had an M1 powered MacBook Air, my first Mac, for close to over a month now. And it's been a life changing experience.

<!--more-->

I've been considering the Apple ecosystem for quite a few years now. Having been using Windows for my desktop OS needs since as far back as I can remember, and Android for my mobile needs from the early days of the smartphone era kicked off by the iPhone in 2007.

The first Mac that I came across in my youth, was a PowerBook G4 my cousin owned when I was 13 or 14. I'd sneak into his room while he was away to mess around with it and to play a few levels of Halo CE on it. I still have vivid memories of the artwork on the OS X box that came with it, with the bold and imposing X floating in front of a swirling purple galaxy. 

I'd been Mac curious since that first experience, and had a few run ins with Macs later which further piqued my interest. Sharing a few classes with someone in 2014 who had a 2011 13" MacBook Pro. Later helping a less technically savvy friend setup their brand new 2015 15" MacBook Pro. 

By 2017 I'd made up my mind that I would like my next computer to be a Mac laptop, but fortunately or unfortunately, that period was smack dab in the middle of the infamously unreliable butterfly keyboard era. That put at least the MacBook Pros out, since I was not willing to deal with an unreliable and finicky keyboard that I might have to bring in for costly service often. The MacBook Air at the time had been barely updated with minor dated processor spec bumps every few years and still had a non-Retina screen. 

So by the time the Air had been updated with the current modern redesign and the butterfly keyboard had been bid adieu on the Pro line, the Apple Silicon transition seemed imminent. So I waited. It came with a bang and it's been everything Apple promised and more.

I have the 2020 MacBook Air with Apple M1 chip with 8-core CPU, 8-core GPU, 16-core Neural Engine. It's equipped with 16GB of unified memory and a 1TB SDD. From day one it's been a consistent and snappy performer. Native apps open near instantly, with some heavier apps like Garageband or Affinity Photo taking a beat to open as you would expect on any system. 

Intel apps running under Rosetta 2 upon first launch take a few bounces in the dock to launch that may seem to take unusually long, but every subsequent launch is speedy enough to be functionally indiscernible from native apps. The thing that's surprised me most with regards to app support, is how well the vast majority of Intel apps simply run. And even for the few apps that have had issues, updates are coming faster than you'd think from developers. Of the vast majority of apps that I run, only a small handful have yet to ship an Apple Silicon build either in beta or stable channels[^1]. Those apps being namely [Discord](https://discord.com) and [Skype](https://www.skype.com/). Despite this, the M1 does a magnificent job of running them and making them feel close to if not entirely as responsive as native apps.

I don't think I can speak fondly enough of Rosetta 2 if I tried. It is truly a marvel of vertical integration that Apple was able to build hardware level emulation of Intel x86 into the M1. Granted it only supports x86-64 emulation, since Apple already dropped support for x86-32 apps across the board as far back as macOS Catalina last year. A clever move by Apple to take the PR blow early to make an easier time for themselves down the line[^2].

We've all seen Craig demonstrate the instant wake of these new M1 powered Macs and I'm happy to say the claims are entirely factual. This MacBook is awake at all times thanks to the big.LITTLE architecture of the M1, the efficiency cores keep ticking away even with the lid is closed. And the screen lights up every time without fail as soon as the lid is parted even half an inch from the chassis. 

You can see this from simply checking your router's DHCP client list. The MBA never drops off WiFi and is constantly connected, able to pickup Continuity and Handoff requests at light speed. With my Air asleep and tucked into a drawer I was able to send it a tab from Chrome on my desktop, and the next time I lifted the lid, a notification was already there waiting for me on the lock screen telling me my tab had been received. I had to just brush the Touch ID sensor and begin working without any friction whatsoever.

Even battery life, the ever present specter that haunts the lives of laptop users is refreshingly of little concern here. In the best case scenario where I was using largely native apps and performing mixed productivity tasks such as writing, browsing the web, watching streaming video, working on this website and teaching myself some Java in IntelliJ IDEA, I routinely got 12-13 hours of solid use of the 15 hours that Apple promises for web browsing on this machine. I'd expect this kind of endurance from an iPhone or iPad, but to get it from a MacBook is truly incredible and a game changer for how much work I can get done without nary a moment of battery anxiety. It's so good in fact that sometimes I've questioned truly how much time has passed since I began working because the battery indicator on my menu bar is still completely full.

The thing that makes this computer a joy to use, is not in fact it's raw performance in terms of how high it can score on any synthetic benchmark or how fast it crushes a video encode or Xcode compile. It's in how fluid and effortless it feels to use on a day to day basis. From every animation to interaction it responds to my inputs almost as if it's read my mind and began launching that app or file before I even clicked on its icon.

Apple Silicon has brought to the Mac one of the core elements that made the iPhone and iPad a joy to use that the Mac lacked, the ability to be instantly responsive and always awake. Balancing performance and power efficiency in such a way to make it seem simply magical. And in no Mac is this better personified than in the fan less MacBook Air. It wakes instantly, does what you command in the blink of an eye dutifully, and never even makes a whisper doing so. Backed by the full capability of macOS, this is the most delightful computer I've ever used. 

Nothing I've seen in Intel's 10th generation lineup of thin and light laptops that I've tried comes close to even capturing this feeling. Don't get me wrong, Intel laptops are also very good and capable computers. But at this point I think I'm led to the conclusion that at least as far as low power silicon is concerned, ARM is the answer. Apple has handily bested Intel in this segment, and I can't wait to see what Qualcomm, AMD and others that are foraying into the ARM laptop space can come up with[^3]. Not to mention what Apple has in the can for the next stage of their transition...


[^1]: [Is Apple silicon ready?](https://isapplesiliconready.com) is an excellent resource for quickly checking at a glance if apps or packages run natively, under Rosetta 2 or not at all on Apple Silicon. Since it is community run, it can sometimes be a bit behind so always double check the developer's website if you can too for the most up to date information.

[^2]: Similarly to how the headphone jack was removed on the iPhone 7 to suffer the negative round of headlines and press early rather than with next year's iPhone X.

[^3]: Dependent of course on if Microsoft can figure out their x86-64 emulation story. Currently even x86-32 emulation on Windows on ARM is significantly less performant than Rosetta 2 on the M1.