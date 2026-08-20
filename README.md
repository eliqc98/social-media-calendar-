# Content Ecosystem Calendar

A single-file planning app for Elizabeth's content across TikTok, Instagram, and LinkedIn — built around the "one story, three engines" framework:

- **Audience Growth (target 55%)** — Career, Studies & Learning, Lifestyle, Mindset, Representation & First-Gen, Money & Financial Literacy. This is the trust engine that grows reach.
- **Empower LATAM UK (target 25%)** — mentee stories, impact stats, advocacy. Turns audience into community.
- **Orinti / Founder (target 20%)** — agency journey, client work, mostly LinkedIn. Turns reputation into clients.

## Weekly posting plan

Content is planned per channel, 6 posts a week total:

| Channel | Cadence | Slots |
|---|---|---|
| **LinkedIn** | 3 posts/week | 2× Orinti (marketing agency) + 1× Empower LATAM UK (social impact) |
| **Instagram + TikTok** | 3 posts/week, cross-posted | 1× financial literacy, 1× skill (tech/AI/business), 1× entrepreneurship & career — all educational |

This is what drives the 50% Growth / 33% Orinti / 17% ELUK objective-balance target on the dashboard.

## What's inside

- **Dashboard** — the objective-balance chart (is a month running heavier on Orinti than the plan calls for, or light on ELUK?) and this week's channel-plan checklist, broken out by LinkedIn vs. Instagram+TikTok.
- **Calendar** — a Monday–Sunday week planner. Schedule an idea from the bank onto a day, or write a new one on the spot.
- **Idea Bank** — 165 seeded ideas pulled from Elizabeth's own notes, tagged by pillar, objective, platform, format, language, and production status. Filterable, editable, exportable.

Data is stored in your browser's local storage — nothing leaves your device. Use **Export JSON** to back up, **Import JSON** to restore, or **Export CSV** to hand the plan to someone else (e.g. an editor or VA).

## Running it

It's a single static HTML file with no build step and no dependencies.

- **Locally:** open `index.html` directly in a browser.
- **Hosted:** serve the repo with any static host (GitHub Pages, Netlify, Vercel) — point it at `index.html`.

## Customizing

Everything — pillars, objectives, platforms, formats, statuses, target percentages, the starter idea bank — lives at the top of the `<script>` block in `index.html`, so it's easy to extend as the content strategy evolves.
