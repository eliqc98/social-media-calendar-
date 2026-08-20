# Content Ecosystem Calendar

A single-file planning app for Elizabeth's content across TikTok, Instagram, and LinkedIn — built around the "one story, three engines" framework:

- **Audience Growth (target 55%)** — Career, Studies & Learning, Lifestyle, Mindset, Representation & First-Gen, Money & Financial Literacy. This is the trust engine that grows reach.
- **Empower LATAM UK (target 25%)** — mentee stories, impact stats, advocacy. Turns audience into community.
- **Orinti / Founder (target 20%)** — agency journey, client work, mostly LinkedIn. Turns reputation into clients.

## Weekly posting plan

Content is planned per channel, 6 posts a week total:

| Channel | Cadence | Slots |
|---|---|---|
| **LinkedIn** | 3 posts/week | 2× Orinti (marketing agency) + 1× **your choice**: Empower LATAM UK (social impact) or personal growth (Mindset) |
| **Instagram + TikTok** | 3 posts/week, cross-posted | 1× financial literacy, 1× skill (tech/AI/business), 1× entrepreneurship & career — all educational |

The third LinkedIn slot isn't locked to one or the other — Batch Prep offers separate "from idea bank" / "new idea" buttons for each option, so you pick whichever fits that week. The 59% Growth / 33% Orinti / 8% ELUK objective-balance target on the dashboard assumes that choice runs roughly even over time; ELUK's real share will track however often you actually pick it.

## What's inside

- **Dashboard** — the objective-balance chart (is a month running heavier on Orinti than the plan calls for, or light on ELUK?) and this week's channel-plan checklist, broken out by LinkedIn vs. Instagram+TikTok.
- **Calendar** — a Monday–Sunday week planner. Schedule an idea from the bank onto a day, or write a new one on the spot. "This week's balance" shows the platform mix (a cross-posted idea can count toward more than one platform).
- **Batch Prep** — the Friday/Monday production workflow. One card per slot in the week's plan (2 Orinti + 1 personal growth/ELUK on LinkedIn, financial literacy + a skill + entrepreneurship on Instagram/TikTok), each with its own script textarea and a 4-stage status control (Idea → Scripted → Filmed → Posted). Write scripts here on Fridays; work down the same list on Mondays and mark each one off as you record it. Stat tiles at the top show what still needs a script vs. what's ready to record.

  **Batch Prep is organized by prep day, Calendar by post day** — they're deliberately different clocks. A card's **Prep day** is editable right on the card and drives which week it shows up in here; **Posts on** is read-only on the card (change it from Calendar or the full editor instead). Picking or adding something from an empty slot sets its prep day to the week you're viewing and defaults its post day one week later, matching a prep-one-week-ahead rhythm — so "this week" in Batch Prep is naturally "next week" on the Calendar.
- **Idea Bank** — 165 seeded ideas pulled from Elizabeth's own notes, tagged by pillar, objective, platform, format, language, and production status. Filterable, editable, exportable.

Data is stored in your browser's local storage — nothing leaves your device. Use **Export JSON** to back up, **Import JSON** to restore, or **Export CSV** to hand the plan to someone else (e.g. an editor or VA).

## Running it

It's a single static HTML file with no build step and no dependencies.

- **Locally:** open `index.html` directly in a browser.
- **Hosted:** serve the repo with any static host (GitHub Pages, Netlify, Vercel) — point it at `index.html`.

## Customizing

Everything — pillars, objectives, platforms, formats, statuses, target percentages, the starter idea bank — lives at the top of the `<script>` block in `index.html`, so it's easy to extend as the content strategy evolves.
