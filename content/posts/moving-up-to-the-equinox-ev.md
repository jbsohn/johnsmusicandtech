---
title: "Keeping the Bolt And Moving Up to the Equinox EV"
date: 2026-07-06
draft: false
tags: ["EV", "Tech", "Automotive", "Chevy Equinox", "Chevy Bolt"]
categories: ["Tech & Cars"]
---

*Editorial Note: I started writing the draft for this post from the passenger seat during our massive Memorial Day road trip down to Austin, Texas. It is now past the 4th of July, and I am just now getting around to polishing it up and clicking the publish button... sigh. Better late than never.*

![Equinox EV](/images/Equinox-EV.jpg)

When I wrote my retrospective, [*Two Years With the Chevy Bolt: The Best Car I've Ever Owned*]({{< relref "posts/chevy-bolt-2-years.md" >}}), I praised how the electric drivetrain completely rewired my expectations of daily driving. I had taken a cautious first step with a 2023 model and walked away absolutely hooked. My only real regret back then? Wishing I had gone even bigger.

So, we did. But with a massive twist: **We kept the Bolt.** We didn't throw our favorite little go-kart under the bus. Instead, we officially graduated into a full, two-car EV household. For the quick city errands and the daily grind around Fort Wayne, the Bolt remains an incredibly fun, zippy, lightweight commuter car that is an absolute blast to drive.

But for the rest of our lives, we needed a whole new level of vehicle layout. Enter the **Chevrolet Equinox EV**.

---

### The Big Picture: Avoiding the Innovator's Dilemma

In the technology industry, we see this story play out in an endless loop: the corporate landscape is an absolute graveyard of giants who stood on the beach, watched a massive paradigm shift roll in, and convinced themselves the water wasn't rising.

Think of IBM completely missing the boat on how PC hardware commoditization would strip them of their computing monopoly. Think of Sun Microsystems treating Linux like a toy until it completely devoured their high-end Unix server business. Think of Silicon Graphics (SGI) looking down on Windows NT as a basic consumer operating system, entirely blind to the fact that standard PC graphics cards would render their proprietary, multi-million-dollar visualization workstations obsolete in a matter of years.

History is incredibly ruthless to incumbents who stick their heads in the sand, hoping the legacy engine powering their profits will last forever.

General Motors is a 118-year-old automotive titan traditionally known for moving with the speed of a continental plate. Yet, instead of clinging desperately to the internal combustion engine and praying the electric transition would just blow over, they stepped up to the challenge. They went all-in.

What makes this transformation fascinating is that GM implicitly realized they could no longer just be a traditional manufacturing company—to survive this pivot, **they had to become a tech company.** Engineering a modern electric platform, coordinating modular battery telemetry, and deploying over-the-air architecture requires a complete reinvention of a company's internal software DNA. For a massive legacy industrial giant to actively avoid the classic tech-disruption trap and execute a pivot of this scale is a fundamentally big deal. The Equinox EV is the direct fruit of a company that actually refused to be left behind.

---

### The Spec Sheet: Shifting to a Full Family SUV

On paper, the Equinox EV targets the ultimate consumer contract by breaking the 300-mile range barrier for a starting price of **$36,795** (before any federal or state tax incentives).

But stepping out of the Bolt and into the Equinox moves you completely out of a tight, subcompact commuter pod and drops you squarely into a mature, family-style midsize SUV platform. The physical upgrades are a massive, night-and-day leap:

* **A Real Back Seat:** Expansive cabin width, a completely flat floor, and true adult-friendly rear legroom mean passengers can actually sit comfortably without eating their knees.
* **Full Storage Space:** A massive, deeply practical cargo bay replaces the tight subcompact hatch, saving us from playing cargo Tetris every time we carry a couple of full-sized suitcases.

I’m typing the draft of this post right now from the passenger seat as we head back from a massive 2,000+ mile interstate road trip from Fort Wayne down to Austin, Texas, and back. Let me be perfectly clear: **I never would have used the Bolt for this trip.** The Bolt is a fantastic local tool, but trying to march it across state lines with its legacy 55kW fast-charging bottleneck would have been a form of psychological punishment. You would spend half the trip staring at a sluggish charging display.

But the Equinox EV? The experience isn’t much different than using a gas-powered car.

Let's be completely honest about the physics: plugging into a DC fast charger isn't *literally* as fast as shoving a liquid fuel nozzle into a gas tank. If you sit in the cabin and watch the battery percentage tick up, you'll notice the difference. But on a long-haul trip to Texas, you don't just sit there. By the time you pull up, plug in, walk inside, use the restroom, grab a coffee, and stretch your legs, the car is done charging right about the time you are ready to hit the road. It fits seamlessly into the natural cadence of a human road trip.

---

### The Infotainment Paradigm: Trusting the Machine

As a software developer, the in-dash software on the Equinox is a fascinating, mixed blessing.

In the Bolt, my phone projection setup was a power-user circus. To execute a smart road trip, I had to act as the human middleware—juggling CarPlay between Google Maps, PlugShare, and A Better Routeplanner (ABRP). I even had to buy an aftermarket OBD-II hardware adapter and plug it into my steering column just so my phone could read the car's live state of charge (SoC). It didn't take long to realize that the vehicle's native dashboard software should be doing all of this work.

The new GM dash does this brilliantly, which became incredibly obvious during our multi-state run to Austin. Because the Google Built-In ecosystem runs natively on the vehicle's underlying hardware, the software and the battery management system finally speak the same language.

The EV integration with Google Maps and charging is excellent. A few times on our 2,000+ mile trip, we looked at the stops the dashboard came up with and thought, *"Oh, we can definitely do that better ourselves."*

Nope. Every single time we tried to engineer an alternative route or find a better stop configuration, we fell flat. After exploring other options, we ended up coming right back to the vehicle's defaults. The onboard system simply knows more than you do. It tracks real-time telemetry, handles route strategy, and—critically—when it knows you are coming up to a charging station, **it automatically initiates battery thermal pre-conditioning**. By preparing the battery pipeline before you arrive, it maximizes your fast-charging speeds on the native NACS pipeline the exact moment you plug into a Supercharger. When it comes to EV routing functionality where it counts, the platform is amazingly great.

---

### The Catch: Banning the Monitored Interface (and the Voice Command Trap)

But here is the cold reality of user-facing implementation: by banning Apple CarPlay and Android Auto entirely, GM didn't just optimize battery telemetry—they volunteered to replace your entire smartphone universe. And that standalone system introduces some real everyday friction, particularly when you want to dive into your personal music collection or handle basic messaging on the road.

Because the car no longer acts as a clean, responsive external monitor for your phone, it creates an artificial isolation wall:

* **The Siloed App Sandbox:** You can download a native Apple Music app from the Google Play store onto the dash. But it operates inside a completely isolated Android wrapper. It is not a fluid extension of your phone; it cannot see your phone's local storage, meaning you have zero access to your offloaded tracks, un-synced files, or localized music shortcuts. CarPlay is sorely missed when you want to dive into your personal music collection.
* **The YouTube Music Loop from Hell:** Because the dash is built on Google's backbone, Google Assistant desperately wants to default to YouTube Music whenever you issue a voice command to play an album or a song. If you don't pay for their premium tier, the algorithm goes rogue, pulling down whatever random, highly compressed audio track or low-quality live bootleg file a random user uploaded to YouTube ten years ago. It was so incredibly frustrating on our trip that I eventually pulled the car over, dove into the application manager, and uninstalled YouTube Music entirely. The result? Total architectural stubbornness. Even when I explicitly instructed the car, *"Hey Google, play [Album] **on Apple Music**,"* the assistant would flatly reply: *"YouTube Music is not installed."* Grrr.
* **The Messaging Wall (The iOS Penalty):** Because there is no native iMessage integration on an Android-based dash, the system falls back to standard Bluetooth profiles to bridge text messages. If you are an iOS user, it represents a clunky, massive step backward into 2012 tech—completely stripping you of group threads, media integration, and native read states.
* **The Subscription Data Tax:** Banning phone projection cuts off your ability to leverage your phone’s cellular data stream. The native dash expects to stand alone, meaning once your initial trial ends, you are forced into a paid data subscription (like OnStar) just to run basic streaming apps or maps natively on the canvas. To be fair, new owners are give eight years of service for free.

---

### The Passenger's Perspective: Genuinely Loved Mechanicals

As I mentioned, I am in the passenger seat managing this post right now while my wife handles the driving on our way back to Indiana. Out of nowhere, looking out at the endless stretch of highway ahead, she just spoke up and said: *“I love this car.”*

And she’s entirely right. We genuinely love this car. Mechanically, structurally, and dynamically, the Equinox EV is an absolute triumph. The ride quality is exceptionally quiet, planted, and smooth—even when we are maintaining high interstate speeds for hours at a time. Acceleration on our base Front-Wheel Drive model is a bit softer off the line than the snappy, featherweight punch of our old go-kart Bolt, but it behaves like a mature, incredibly solid road tripper.

We chose to skip the high-priced Super Cruise package (it was out of our price range), but the standard lane-keep assistance and adaptive cruise tools handle regular long-haul highway driving beautifully without inflating our monthly car payment.

The vehicle is so physically good that a driver can look right past the missing phone projection and genuinely love the machine. But as the passenger acting as the "human middleware" trying to navigate the siloed voice command traps, missing messaging interfaces, and isolated media apps, the software friction is a real, localized barrier on an otherwise brilliant platform.

---

### The State of the Union Verdict

Ultimately, when the choice is between a slightly fragmented software experience or a stable, brilliantly built mechanical platform, the pragmatic driver is always going to choose the superior driving machine.

The Equinox EV is a massive upgrade, and the dash software is great at doing what a car *should* do—owning its own route and charging strategy. By pairing it alongside our trusty old Bolt, we didn't just find a replacement for our favorite car; we built the perfect, two-car electric driveway for the next generation.
