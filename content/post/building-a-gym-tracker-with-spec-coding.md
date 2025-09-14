+++
date = '2025-09-13T12:55:18-03:00'
draft = false
title = 'I Hate the Gym, So I Built a Fitness App with Spec Coding'
subtitle = 'How my nephew, the gym, and a new coding paradigm collided into one project.'
description = "A personal story about building LiftFire, a gym tracker app — and my thoughts on the future of vibe coding, spec coding, and AI-assisted development."
author = 'DevBlac'
tags = ['fitness', 'spec-coding', 'developer-experience', 'personal', 'vibe', 'code', 'software engineering', 'kiro', 'AI', 'develop']
categories = ['General']
+++

---


**TL;DR:**  
I built **LiftFire**, a gym tracker for my nephew and me. It started as a way to make boring workouts less painful — and turned into my first real test of **spec coding**, a workflow where documents steer the build instead of just raw code.  

The surprise? It felt like the future: less busywork, more meaning. Coding gets easier — but commitment, whether in the gym or in software, is still the real challenge.  


---

I find weightlifting so boring I’d rather debug legacy PHP.
But when my nephew said yes to going with me, I built an app to make sure neither of us quit.

This is the story of **LiftFire**, a gym tracker I built with [Kiro IDE](https://kiro.dev) which implements **spec coding**.
It’s part fitness struggle, part dev diary, and part glimpse into the future of building software with AI.


![Spec Coding](https://github.com/devblac/devblac.github.io/blob/main/assets/20250913-gymtracker-futurespecs.png?raw=true)

---

## Coding is easy. Commitment is hard.

As I spend most of my life behind screens, so I try to balance it:
- Eat protein.
- Skip sugar.
- Run in the park.
- Lift weights at the gym.

![Trying to work-life balance](https://raw.githubusercontent.com/devblac/devblac.github.io/refs/heads/main/assets/20250913-gymtracker-balance.png)

The truth? I hate weightlifting. It’s repetitive, it’s monotonous, but the result is undeniable: after a workout, my brain feels 400% sharper. It rewires my mood, my focus, my life.

So what makes the boring worth it? **Going with someone else.**
Friends said no. Colleagues said no. Family said no.
Then my nephew said yes.

That was the spark. If we were going to do this together, I wanted an app that would keep us both accountable.

---

## Why another gym app?

I downloaded half a dozen fitness apps. Some buried me in menus, others felt like they were built for bodybuilders only. None struck the balance I wanted.  

- Too cluttered.
- Too minimal.
- No gamification.
- No real social accountability.

What I wanted was simple:  
- **Easy tracking** → log sets in seconds.
- **Gamification** → milestones, achievements, challenges.
- **Social layer** → friends, feeds, progress sharing.

So I built one: **LiftFire**.

---

## [Screenshot Placeholder: LiftFire UI - exercise list / tracking screen]  

*“Yes, it’s simple — but it actually gets used. Unlike that half-finished Rust side project we don’t talk about.”*

---

## From vibe coding to spec coding  

When I first saw **vibe coding**, it felt magical: *“create a site with one sentence.”*
But here’s the problem: one-sentence apps don’t scale.

The real breakthrough came with **spec coding** — a workflow where:
- **Steering files** (`product.md`, `tech.md`, `security.md`, `structure.md`) act as living docs that guide the code.
- **Spec requests** define requirements, designs, and tasks in plain language.
- **Hooks** (or *vibe requests*) trigger tests, commits, or formatting manually or automatically when conditions are met.

It wasn’t about replacing me. It was about letting me think like an architect while the system handled the glue.

---

## My take on scaling

> For a **small site**, ~50 spec requests are plenty.
> For a **real-world app** with frontend, backend, DB, AWS, etc., you’ll need **500+ specs** and **700+ vibe requests**.

Specs move the big rocks.
Vibes hammer the details.
It’s architecture vs. carpentry.

But here’s the thing: the **professional supervising the build** changes everything. Human knowledge and context are part of the equation, shaping the outcome in ways no spec can capture alone. At least yet.

---


![Specs, agent hooks and agent steering](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/liwy1aa8ladf4zl38l4e.jpg)

*“Cleaner than my kitchen. Don’t zoom in or you’ll see TODOs multiplying.”*  

---

## The LiftFire MVP  

The MVP is real. A basic tracker that will soon be on Google Play as an APK.

But I’m halfway through more ambitious features:
- A **social feed** where friends can add each other.
- Sharing workouts, goals, and milestones.
- A gamified layer to make workouts less boring and more communal.

And yes — there will be a roadmap live at [kirogym.netlify.app](https://kirogym.netlify.app) in the next days.
It’s not just a roadmap; it’s also where I’ll explain new features as they roll out.

---

## The future of coding

Vibe coding was the first wave: cool demos,one-sentence sites.
Spec coding is the next wave: robust software built by humans + AI in collaboration.

And beyond that? I believe the future is **AI agents for each part of the process**:
- One for macro vision.
- One for context.
- One for each subsystem.

It requires more effort up front, but delivers **stronger software, faster, with fewer people involved in the mechanics** and potencially more secure, which is a very common pain point in vibe coding. 

But don’t get me wrong — people are still the key. Without human judgment, vision, and long-term stewardship, there’s no lasting value. AI can build parts, but humans give meaning.

---

## Reflections

- Gym alone? Boring.
- Gym with my nephew? A commitment I actually kept.
- Coding alone? Fine.
- Coding with spec coding workflows? Next level.

Collaboration is the superpower — in the gym and in the IDE.


![Coding together](https://github.com/devblac/devblac.github.io/blob/main/assets/20250913-gymtracker-coding.png?raw=true)


---

## Closing  

If you want the **technical breakdown** (steering files, hooks, vibe requests), I wrote a focused [dev.to post](#).

But this story was about *why*.
Why I chose the gym.
Why my nephew matters.
Why spec coding matters.

Because in the end:
**Commitment is the real challenge. Coding just makes it easier.**
And if there’s one lesson here, it’s this: collaboration, whether with family or with AI, is what keeps us going when motivation fades.