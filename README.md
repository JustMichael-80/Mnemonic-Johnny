# Mnemonic Johnny

> *"The sky above the port was the color of television, tuned to a dead channel."*
> — William Gibson, Neuromancer

The algo works against you. It always has. Engineered for engagement, optimized for addiction, designed to bury signal under an avalanche of noise so you keep scrolling. You were never the customer. You were the product.

---

## What It Is

Mnemonic Johnny works nights.

Johnny is an on-device AI agent that runs while you sleep — combing your social feeds, chat queues, connection requests, notifications, and DMs using computer vision and a personalized interest profile. By morning, it hands you a ranked digest of the 1% that actually mattered. The rest stays buried where the algo put it.

No API keys. No platform permission. No terms of service negotiation.
Just pixels, pattern recognition, and a night shift that never calls in sick.

---

## How It Works

Johnny uses Android's **AccessibilityService** and **MediaProjection** APIs — the same hooks used by screen readers and accessibility tools — to observe your screen with your explicit permission. Nothing leaves your device unless you choose to sync.

```
Screen Observation (Computer Vision / OCR)
        ↓
Content Parser (post / DM / notification / request classifier)
        ↓
Interest Profile Scorer (keyword + behavioral fingerprint)
        ↓
Ranked Digest Engine
        ↓
Morning Briefing → Push Notification + In-App Drop
```

The humanization layer runs the night session at natural human interaction speeds — randomized tap intervals, organic scroll velocity curves, session fatigue modeling — so the account behaves like an insomniac, not a bot.

---

## The Morning Briefing — The Drop

Every morning Johnny surfaces a tiered digest:

| Tier | Category | What It Contains |
|------|----------|-----------------|
| 🔴 | **Chats** | Active conversations requiring response. Agent drafts suggested replies. |
| 🟠 | **Chat Requests** | Unsolicited inbound DMs scored against your interest profile. |
| 🟡 | **Connection Requests** | Ranked by relevance, with one-line AI summary of each person. |
| 🟢 | **Tags & Mentions** | Public references to you, flagged by urgency and sentiment. |
| 🔵 | **Relevant Miscellany** | Feed content the algo buried that matches your interest profile. |
| ⚪ | **Aggregate** | Pattern-level view — emerging terms, trending voices in your interest graph. |
| ⬛ | **Summation** | 150-200 word plain English briefing written fresh each morning. |

Each category has three states: **Act Now**, **Review Later**, **Archived**. Johnny pre-sorts. You override. Johnny learns from your overrides.

---

## The Interest Profile — Johnny's Brief

Johnny doesn't just filter on keywords you set. It watches what you linger on, what you tap, what you ignore, and continuously refines your interest fingerprint. It also suggests new filter terms based on patterns it notices before you do.

You define the starting point. Johnny sharpens it over time.

---

## The Night Shift

Johnny runs its deep session between **2am–5am local time** — off-peak hours where:

- Account activity looks organic (insomniac, not bot)
- Platform throttling is minimal
- Content is stable for clean OCR pass
- You're not there to interrupt it

By the time your alarm goes off, Johnny's already clocked out. The Drop is waiting.

---

## Platform Support

| Platform | Status |
|----------|--------|
| Android 10+ | ✅ Primary target |
| X (Twitter) | ✅ Supported |
| LinkedIn | ✅ Supported |
| Instagram | 🔄 Planned |
| Discord | 🔄 Planned |
| Substack | 🔄 Planned |
| Slack | 🔄 Planned |
| Email (Gmail / Outlook) | 🔄 Planned |
| iOS | ⛔ Not currently supported |

iOS is a later fight worth having. For now: Android, sideload, no gatekeepers.

---

## Roadmap

### v0.1 — The Night Shift
- [ ] AccessibilityService + MediaProjection integration
- [ ] OCR content parser (posts, DMs, notifications)
- [ ] Basic keyword interest profile
- [ ] Humanization layer (tap timing, scroll physics, fatigue model)
- [ ] Morning push notification
- [ ] Digest UI — The Drop

### v0.2 — Johnny's Brief
- [ ] Behavioral interest profile (learns from user overrides)
- [ ] Agent-suggested keyword additions
- [ ] Per-category Act Now / Review Later / Archived triage
- [ ] Draft reply suggestions for chats

### v0.3 — The Aggregate
- [ ] Pattern-level weekly intelligence view
- [ ] Longitudinal relationship tracking ("what's changed in 30 days")
- [ ] Multi-platform digest merge
- [ ] Summation paragraph — daily AI-written briefing

### v1.0 — Johnny On Call
- [ ] Full platform suite
- [ ] On-device model fine-tuning from user behavior
- [ ] Cross-device sync (opt-in)
- [ ] Commercial licensing tier

---

## Architecture Philosophy

**On-device first.** Your interest profile, your behavioral data, your feed content — none of it touches a remote server by default. The processing happens on hardware you own.

**Platform agnostic.** Johnny reads pixels. It doesn't care what app is rendering them. One agent, every surface.

**Accessibility framing.** Legally and technically, Johnny is an accessibility tool. It amplifies your perception of your own feed. It doesn't publish, follow, or act publicly on your behalf without explicit confirmation.

**Signal over engagement.** The algo optimizes for time-on-app. Johnny optimizes for the opposite — get you what you need, get you out.

---

## Legal

© 2026 ChronoDyne Systems, Inc. All rights reserved.

Source code is made available for viewing and non-commercial personal use only. No permission is granted to use, copy, modify, merge, publish, distribute, sublicense, or sell this software or derivative works for commercial purposes without explicit written authorization from ChronoDyne Systems, Inc.

For licensing inquiries: legal@chronodynesystems.com

---

## A Note on Contributing

Johnny is early. Architecture is in motion. Watch this space.

---

*Mnemonic Johnny is a ChronoDyne Systems project.*
*Johnny works nights. You just read the drop.*
