---
title: "Are We Really Forking Visual Studio Code Again?"
subtitle: "Fork fatigue, AI hype, and lessons we never seem to learn"
date: 2026-01-19
draft: false
slug: fork-fatigue-vscode-and-lessons-we-never-seem-to-learn
tags: ["vscode", "open-source", "ai", "software-history"]
---

I’ve been a developer long enough to remember when *this was the year of the Linux desktop*.

We heard it every year. The technology was there. The talent was there. The passion was definitely there. What never quite materialized was coordination — agreement on where collaboration should stop and competition should begin.

So when I look at what’s happening today around editors and AI tooling, I don’t feel outrage. I don’t feel betrayed. I mostly feel a familiar, slightly exhausted thought forming:

**C’mon guys… are we really doing this again?**

---

## A quick clarification up front

Nothing about what’s happening right now is dishonest.

Nobody is stealing code.  
Nobody is violating licenses.  
Nobody is acting in bad faith.

This is all legal. Ethical. Allowed. That’s actually what makes it interesting — and frustrating. This isn’t a morality problem. It’s a **coordination problem**.

---

## We’ve seen this movie before

Not always as forks, but as parallel foundations competing at the same layer:

- KDE vs GNOME  
- Emacs vs XEmacs  
- Vim vs Neovim  
- Flatpak vs Snap  
- RPM vs DEB  

Each of these made sense locally. Each had real motivations and smart people behind it. But collectively, the ecosystem paid for it — in fragmentation, duplicated effort, and momentum that never quite compounded. So when people say “this time it’s different", my reaction isn’t anger. It’s pattern recognition.

---

## VS Code actually solved something

Here’s the uncomfortable part.

Visual Studio Code is… good.

It’s fast.  
It’s boring in the right ways.  
It’s extensible.  
It mostly gets out of your way.

I never thought I’d move away from Vim — and yet here we are. VS Code became my go-to editor for simple things not because it was flashy or ideological, but because it reduced friction. It respected my time That’s not trivial. That’s *rare*.

Microsoft didn’t get there by accident. They came a long way from the antitrust era. They rebuilt trust. They open-sourced VS Code. They invested heavily in extensions. They allowed competitors to exist *inside* their platform. They did what a lot of us asked them to do.

---

## Forking isn’t evil — but it is easy

Here’s the hard truth:

It’s a lot easier to take the ball and go home.

Forking is decisive.  
Parallel projects feel empowering.  
You move fast.  
You don’t have to negotiate.  
You don’t have to compromise.

Working within a shared system is slower, messier, and often frustrating. But when the system is open, responsive, and healthy, **working within it is the right thing to do**. Forking should be the last step — not the first.

---

## And yes — this is all about AI

Let’s be honest about the backdrop.

A huge amount of this renewed forking energy exists **in the name of AI**.

AI-assisted coding changes the economics:

- tighter editor integration matters more  
- defaults matter more  
- UX matters more  
- control over workflows matters more  
- shipping fast matters more  

AI isn’t just another feature — it wants to sit *at the center* of the editor experience. And once something wants to live at the center, the temptation to own the whole stack becomes very strong. This isn’t a neutral evolution of tooling — it’s a **land grab driven by AI integration**.

---

## And notice the timing

For **years**, nobody felt the need to fork VS Code.

Not when it was growing fast.  
Not when the extension ecosystem exploded.  
Not when it became the de-facto editor across platforms.

For a long time, the model worked. Then suddenly — now — forks are everywhere. What changed wasn’t VS Code’s quality, openness, or extensibility. What changed was the **stakes**. AI moved from “nice add-on” to “core product,” and the editor became the control surface. If this platform was “good enough” for years but suddenly isn’t, maybe the platform isn’t the problem.

---

## Each fork makes progress — but not together

To be very clear: the developers working on these new editor forks are doing **great work**. Real problems are being solved. Interesting ideas are being explored. These aren’t hobby projects — in many cases they’re talented engineers working full-time, with clear assignments and real resources.

The issue isn’t effort or intent.The issue is **where that progress lands**. Each fork will add real improvements — but those improvements live in parallel silos. They benefit local users, but they don’t strengthen the shared foundation. Innovation continues. But compounding stops.

---

## Forks don’t just diverge — they fall behind

VS Code doesn’t stand still.

It keeps improving:

- performance  
- accessibility  
- polish  
- extension APIs  
- boring but critical maintenance  

Every fork inherits a permanent obligation to keep up. Forks often exist to move faster — and they often do, at first. But long-term, the cost of staying aligned with a fast-moving upstream cancels out much of that speed. That’s not a moral failing. It’s a systems reality.

---

## And to be fair: the extension APIs already go a long way

VS Code’s extension APIs are **extremely capable**.

You can do a *heckuva lot* without touching the editor core:

- deep language integrations  
- code actions and refactors  
- inline UI and decorations  
- command surfaces  
- background services  
- AI-driven workflows layered on top  

Plenty of sophisticated tools already exist entirely as extensions. If proposals were made upstream and rejected, fine — that’s how forks are born. If no serious attempt was made to work within the existing system, let’s just say the argument gets thinner.

---

## No matter what forks exist, the marketplace is still the center

No matter how many forks appear, one thing hasn’t changed:

**The VS Code Marketplace is where the extensions are.**

That’s where the ecosystem lives.  
That’s where tools are published.  
That’s where documentation points.

Forks may ship their own UX and defaults, but they still orbit the same extension universe. The center of gravity hasn’t moved.

---

## The marketplace reality (like it or not)

You can complain about the setup, but the reality is simple:

Microsoft owns the marketplace.  
They operate it.  
They secure it.

They also publish some of the **most important extensions** themselves — including first-class language tooling that is *not* available to every fork. Forks depend on the marketplace. The marketplace does *not* depend on forks. That asymmetry matters.

---

## If history is a guide: XEmacs

XEmacs started as a pragmatic fork. For a long time, it genuinely **looked better** — especially in X/Windows and early Windows environments.

But Emacs didn’t stand still. Over time, GNU Emacs caught up. Once that gap closed, the main reason to choose XEmacs quietly disappeared.

*Eagle-eyed readers may notice that the version numbers imply a couple of patch releases between 2009 and 2026. So yes — there was some activity in that gap. Call them the “mystery releases.” Whatever work happened there was clearly caretaker-level maintenance, not seventeen years of lockstep evolution.*

XEmacs didn’t fail dramatically. It just… faded. Most forks don’t die. They stop mattering.

---

## We’re watching it happen with Vim too

You can see a quieter version of this today in the Vim ecosystem.

Vim and Neovim coexist. Both are active. Both are “successful.” And yet the community is clearly split.

Plugins choose sides.  
Tutorials assume features.  
Compatibility becomes conditional.

Nobody did anything wrong. But compounding slowed.

---

## Forks are sometimes necessary — but not by default

To be clear, none of this is an argument against the right to fork. Forking is legal, ethical, and sometimes absolutely necessary — especially when a project is abandoned, closed off, or unwilling to evolve. But when a project is open, healthy, and actively improving, the harder and more responsible choice is often to stay inside the system and do the unglamorous work of making it better for everyone.

---

## Forking is a long-term commitment

This is really what all of this comes down to. Forking is easy to cheer for in the moment. It feels decisive. Empowering. There’s a lot of *rah rah rah* energy around it — especially when shiny new tech is involved.

But a fork isn’t a victory lap. It’s a **commitment**. Once you fork, you don’t just own your changes — you own *every upstream change you don’t take*. Forever. Rebases. Compatibility. Security fixes. Ecosystem drift. The unglamorous work that continues long after the excitement wears off.

It’s a bit like getting a dog. The first week is fun. Everyone’s excited. You post pictures. You talk about how great it’s going to be. Then come the early mornings. The vet bills. The long-term responsibility. The realization that this isn’t a phase — it’s a relationship. Forks are the same way.

Sometimes you absolutely need one. Sometimes it’s the right call. But going all-in on a fork should come *after* a long pause, not before it. Because once you do, you’re in it for the long haul — whether the crowd is cheering or not.

---

## So… what do we got here?

We’ve got a good editor.  
We’ve got a healthy platform.  
We’ve got talented people doing real work.

And we’re standing at the moment where we decide whether to **build on that win** — or slowly fracture it in the name of speed and AI urgency.

No villains.  
No conspiracies.

Just a tired question from someone who’s been here before:

**Are we really doing this again?**

*This post happens to use VS Code as its lens, but the warning applies to any fork of a healthy, active project.*