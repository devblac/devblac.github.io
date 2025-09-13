+++
date = '2025-09-13T12:55:18-03:00'
draft = false
title = 'I Hate the Gym, So I Built a Fitness App with Spec Coding'
subtitle = 'How my nephew, the gym, and a new coding paradigm collided into one project.'
description = "A personal story about building LiftFire, a gym tracker app, with Kiro IDE — and my thoughts on the future of vibe coding, spec coding, and AI-assisted development."
author = 'DevBlac'
tags = ['fitness', 'spec-coding', 'developer-experience', 'personal', 'vibe', 'code', 'software engineering', 'kiro', 'AI', 'develop']
categories = ['General']
+++

---

**TL;DR**:
I built **LiftFire**, a gym tracker for my nephew and me, using a new workflow called **spec coding**. Instead of code-first, it’s driven by `.md` steering files, spec requests, and vibe-triggered hooks.
- Small apps can work with ~50 specs.
- Real-world apps may need **500+ specs + 800+ vibes**.
- Specs = big rocks, vibes = details, **humans = the real difference**.
The future isn’t one-sentence apps, it’s AI agents collaborating with people. Commitment is the hard part — coding just makes it easier.

---

I find weightlifting so boring I’d rather debug legacy PHP.
But when my nephew said yes to going with me, I built an app to make sure neither of us quit.

This is the story of **LiftFire**, a gym tracker I built with [Kiro IDE](https://kiro.dev) which implements **spec coding**.
It’s part fitness struggle, part dev diary, and part glimpse into the future of building software with AI.

---

## Coding is easy. Commitment is hard.

As I spend most of my life behind screens, so I try to balance it:
- Eat protein.
- Skip sugar.
- Run in the park.
- Lift weights at the gym.

The truth? I hate weightlifting. It’s repetitive, it’s boring, and I’d rather debug legacy PHP than do another set of curls.

But the result is undeniable: after a workout, my brain feels 400% sharper. It rewires my mood, my focus, my life.

So what makes the boring worth it? **Going with someone else.**
Friends said no. Colleagues said no. Family said no.
Then my nephew said yes.

That was the spark. If we were going to do this together, I wanted an app that would keep us both accountable.

---

## Why another gym app?

I tried plenty. They almost all fell short.

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

## [Screenshot Placeholder: Example of product.md / steering file]

*“Cleaner than my kitchen. Don’t zoom in or you’ll see TODOs multiplying.”*  

---

## The LiftFire MVP  

The MVP is real. A basic tracker that will soon be on Google Play as an APK.

But I’m halfway through more ambitious features:
- A **social feed** where friends can add each other.
- Sharing workouts, goals, and milestones.
- A gamified layer to make workouts less boring and more communal.

And yes — there’s a roadmap live at [kirogym.netlify.app](https://kirogym.netlify.app).
It’s not just a roadmap; it’s also where I’ll explain new features as they roll out.

---

## [Screenshot Placeholder: Roadmap site at kirogym.netlify.app]

*“Publishing your roadmap online = zero excuses. My nephew checks it more than I do.”*

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
- Gym with my nephew? Life-changing.
- Coding alone? Fine.
- Coding with spec coding workflows? Amplified.

Collaboration is the superpower — in the gym and in the IDE.

---

## Closing  

If you want the **technical breakdown** (steering files, hooks, vibe requests), I wrote a focused [dev.to post](#).

But this story was about *why*.
Why I chose the gym.
Why my nephew matters.
Why spec coding matters.

Because in the end:
**Commitment is the real challenge. Coding just makes it easier.**