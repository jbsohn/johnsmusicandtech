---
title: What AI Is Doing to Software Development (and What It Can’t Do Yet)
date: 2025-07-06
draft: false
slug: what-ai-is-doing-to-software-development
description: Reflections on how AI tools like ChatGPT are reshaping software development—from the bookshelf era to side-project breakthroughs.
---

## What AI Is Doing to Software Development (and What It Can’t Do Yet)

I started writing software just before the Internet changed everything. Back then, if you wanted to know how a Windows API worked, you didn’t Google it—you went to the bookshelf. Mine was packed with Microsoft documentation: thousands of pages in thick printed volumes. *Win32 Programmer’s Reference*, *MFC Library*, *SDK Tools*—it took up most of a shelf and all of your patience.

At the time, I was a full-time Visual C++ developer targeting Windows 3.1 and Windows NT. This was before MSDN went online, before modern IDEs gave you tooltips for everything, and definitely before anyone expected their build tools to talk back.

Then came the CD-ROM bookshelf. That felt futuristic at the time: all your documentation in one place, searchable across volumes! Of course, it was running off a 2x CD-ROM drive, and your hard drive didn’t have enough space to copy it locally. So you’d wait for the disc to spin up, click through painfully slow UI, and try to remember the exact function signature so you could find what you were looking for. It was better than flipping pages—but not by much.

And if you really got stuck, you could dial into CompuServe for official Microsoft support. At my job, we’d wait until 5 or 6 PM—after business hours—before logging in. It was too expensive during the day. You paid around $4.80 an hour for off-peak access, and as much as $12 an hour during business hours—and that was in 1994 dollars. Adjusted for inflation, that’s about $10 to $25 an hour today. So yeah, you thought twice before asking a question. You’d type your issue, wait, type a follow-up, wait again, and hope that someone from Microsoft or a fellow forum use knew the answer.

Then came the web.

It wasn’t great at first—mostly flat HTML pages and a few Knowledge Base articles. But it let us bypass CompuServe entirely. You didn’t need to wait until after 5 PM. You didn’t need a modem at all. You could search for solutions during the *day*, right from your desktop. That shift—from paid gatekeeper to open access—was massive. Not because the answers were always better, but because they were *available*.

And here’s the pattern:  
Each advance made our jobs easier.  
Each one chipped away at the friction.  
Each one let us spend less time searching and more time building.

That’s what AI is doing now. It's just the latest link in a long chain of developer productivity tools. But it feels different—because instead of finding answers for us, it tries to *be* the answer.

---

## AI Isn’t Magic—But It’s the Closest Thing We’ve Got

The first time I used an AI assistant in my development workflow, I didn’t expect much. I’d seen autocomplete before. I’d seen bad Stack Overflow answers. I figured this would be somewhere in between: confident, fast, and mostly wrong.

But then it worked.

I gave it a CMake error that had me spinning my wheels for an hour. It spotted the issue immediately, explained why it was happening, and showed me how to fix it. I copied the suggestion in with the same cautious optimism I usually reserve for wiring up production deploys—and to my surprise, it worked on the first try.

Since then, I’ve used AI tools for all kinds of things:
- Translating code between Swift, Kotlin, and C++.
- Writing unit tests I didn’t have time to hand-roll.
- Sketching out GitHub Actions workflows in one shot.
- Refactoring old crufty code just enough to make it understandable again.

Sometimes I don’t just ask AI for help—I challenge it. I’ll prompt it with a problem I already know how to solve, just to see if it can come up with a cleaner, simpler, or more modern approach. Sometimes it surprises me. Sometimes it reminds me why experience still matters. But it’s become part of how I keep learning—even on problems I thought I’d already solved.

The big thing AI changes isn’t *what* I do—it’s *how quickly* I can do it. It’s not replacing my brain. It’s just letting it focus on the parts that matter.

---

## Fewer Blocks, Faster Flow

When everything’s clicking, it feels like the best kind of pair programming: you stay in the zone longer, because your assistant doesn’t need breaks.

That friction—the kind that used to send you deep into MSDN archives or half-broken forum threads—is often just gone.  
What used to take an hour now takes ten minutes.  
What used to be “I’ll deal with that tomorrow” becomes “Might as well do it now.”

And yes, we *could* figure out all those obscure flags, shell incantations, and linker options on our own—we’ve done it for years.  
But now we don’t have to *waste* time doing it.  
AI doesn’t replace the knowledge. It just makes it *cheaper to apply*.

It’s not about writing more code.  
It’s about *thinking less about the boring parts* so we can focus on the interesting ones.

---

## The Trap: When It’s Confident and Wrong

Of course, AI still screws up. Sometimes in ways that are easy to spot—syntax errors, outdated APIs. But the more dangerous moments are when it’s *almost* right. The logic works, but not quite. The output looks plausible, but misses an edge case. And if you’re not careful, you won’t notice until something breaks in production—or worse, *doesn’t* break, but behaves subtly wrong.

That’s where experience still matters.

AI doesn’t think. It imitates. It predicts. The developer still needs to know what changes to accept into the codebase.

---

## It’s Been Revolutionary for Side Projects

The impact of AI at work is real—but where it’s been *revolutionary* is in my personal projects.

Like most developers with a day job, I only get so many hours in the evening to work on my own ideas. Before AI, that time could easily disappear down a rabbit hole of dependency issues, obscure build errors, or just wrestling with low-level glue code.

Now? I can actually *finish things*.  
I can ship a build. Write a parser. Build a CI pipeline.  
Not because I suddenly know more—but because I spend way less time fighting with things I already *sort of* understand.

AI doesn't do the creative thinking for me. But it clears the brush so I can see the path. And when you’ve only got 90 minutes of energy after dinner and bedtime routines, that’s everything.

---

## The Bottom Line: Tools, Not Talent

AI is the latest in a long line of tools that have helped us go faster and build better. From printed books to CD-ROMs to websites to autocomplete—and now this—it’s always been about reducing friction and extending what one developer can do in a day.

But tools aren’t talent. AI can’t make decisions. It doesn’t know your architecture. It doesn’t care about your users, your deadlines, or the weird constraints of your legacy codebase.

That’s still on us.

And honestly? I’m fine with that.

Because as long as I’m the one steering, I’m happy to have something in the passenger seat that knows what the not-so-obvious CMake flag is.

---

**Postscript:**  
This post itself was written with help from AI—specifically, ChatGPT. I had the ideas, the voice, and the stories, but without an assistant to help me organize my thoughts and keep the momentum going, I probably wouldn’t have taken the time to write it at all. Ironically, the same tool that helps me code faster after hours also helped me get this post out of my head and onto the page.
