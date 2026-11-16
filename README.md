# Kortix Marketing Factory

A reference for one Kortix loop: one marketing agent with a skill library for
content (changelog, blog posts, social, video, design), AEO, SEO and GEO, and
performance marketing. It works 24/7 and ships drafts; a person publishes.

This repository is meant to be **read and adapted**, not copied as is.

## Add it to your repository

Paste this into Claude Code, Codex or Cursor in your repository (or your
website's repository):

```text
Set up the Kortix Marketing Factory on this repository with me.
Read https://kortix.com/setup.md (curl -fsSL https://kortix.com/setup.md) and follow it step by step. The template is marketing.
Ask all your questions in one message. Never print a secret value.
```

## What it runs

| Area | Skills | Started by |
| --- | --- | --- |
| Content | `changelog`, `blog-post`, `social`, `video` (HyperFrames), `design` | merged pull requests, weekly schedules |
| Search | `aeo-seo` (AI answers, SEO, GEO) | weekly audit, daily answer pages |
| Paid | `performance` (Google Ads, Meta, LinkedIn; read-only) | weekly report, daily watch |
| Market | `competitor-intel` | weekly digest |
| Everything | `brand`: voice, visual system, claims | loaded first by every skill |

Files: `marketing.yaml` (agent and triggers), `agents/marketing.md`,
`marketing.json` (site, channels, approval policy), `skills/`, and
`ADAPTING.md` (what an agent asks and checks when it adapts this).

## Defaults

- Drafts only: pull requests and issues. It never merges, posts, publishes,
  emails, or edits an ad campaign.
- Paid channels are read-only; budget and bid changes are proposals.

Kortix is open source: https://github.com/kortix-ai/suna
