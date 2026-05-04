# Developer EQ Sprint

> A 2-week, 10-exercise program for engineers who can ship code but freeze in the meeting after.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made by ChaosKyle](https://img.shields.io/badge/made%20by-ChaosKyle-9333ea)](https://developereq.com)

## What is this?

The Developer EQ Sprint is a free 2-week program designed for engineers who:

- Close Jira tickets faster than the team but watch less technical people get promoted past them
- Have strong opinions in code reviews and zero opinions in standups
- Walk out of every 1:1 thinking "what was the point of that?"
- Know they should "network more" and have no idea what that actually means

**10 exercises. 15 min/day. No tools. No accountability buddy. Just you and the work.**

## Pick your format

This repo ships the same sprint three ways. Pick what works for you:

### 📘 PDF Workbook (traditional)

Download the fillable PDF — print it, write in it, do the work.

→ [Download from developereq.com/workbook](https://developereq.com/workbook) (email-gated; you also get drip emails through the sprint)

→ Or grab the markdown source: [`workbook.md`](./workbook.md)

### 🤖 Claude Code Skill (recommended for AI-native devs)

The skill version uses your AI to coach you through each day — reads your git log, drafts your follow-up messages, helps extract metrics for your promotion brief. Zero copy-paste.

**Install:**

```bash
mkdir -p ~/.claude/skills && curl -o ~/.claude/skills/dev-eq.md https://raw.githubusercontent.com/ChaosKyle/developer-eq-sprint/main/dev-eq.md
```

**Run:**

```
/dev-eq
```

Claude Code will track your progress in a local `.dev-eq-sprint.md` file — your notes never leave your machine.

### 💬 Generic AI Prompts (Cursor, ChatGPT, Gemini, anything)

Standalone prompts you paste into any AI. One per day.

→ [`prompts/`](./prompts/) — start with [`00-sprint-planning.md`](./prompts/00-sprint-planning.md)

## The sprint at a glance

```
Sprint 0   → Sprint Planning (Sun)     — Self-audit + set sprint goals
Week 1     → Mon-Fri (5 standups)      — Foundations
Week 1 Retro → Sat                     — What worked, what didn't
Week 2     → Mon-Fri (5 standups)      — Pressure & practice
Sprint Demo → Sat                      — Show your work, plan next sprint
```

### Sprint backlog

**Week 1: Foundations**
1. The Skill Tree Audit
2. The 1:1 Reset
3. Standup Volume
4. Code Review as Communication
5. Async vs. Sync

**Week 2: Pressure & Practice**
6. The Calm Voice
7. The Disagreement Playbook
8. The Networking Algorithm
9. The Promotion Ask
10. The Follow-Up Superpower

## Privacy

- The Claude Code skill runs **entirely locally**. Your sprint notes live in a `.dev-eq-sprint.md` file in whatever directory you ran `/dev-eq` from. Nothing leaves your machine.
- The skill may read your local `git log` if you opt in (Day 1, Day 4) to ground exercises in your real work. It never sends git data anywhere.
- The PDF download from developereq.com is email-gated. We use [Resend](https://resend.com) for delivery and don't sell or share your email. Unsubscribe link in every email.

## What's next

If the sprint clicked and you want to go deeper:

| Format | Price | What you get |
|---|---|---|
| **The Book** | $20 | All 16 chapters. Each exercise in this sprint, expanded with stories, frameworks, and the playbooks I used. |
| **The Live Cohort** | $500 | 4 weeks, Tuesday nights 7pm CST, max 20 people, lifetime Discord access. The sprint exercises run in a room of other engineers. |

→ [developereq.com](https://developereq.com)

**At DevOps Days?** Use code **`DEVOPSDAYS`** for $100 off the cohort.

## Contributing

Bug reports, typo fixes, and translation PRs welcome. For larger changes (new exercises, structural rewrites), open an issue first to discuss.

This repo intentionally does **not** accept PRs that add additional exercises beyond the 10 — the constraint is the product. Two weeks. Ten standups. That's it.

## License

[MIT](./LICENSE) — code and content free to use, fork, remix.

"Developer EQ" name and logo are not licensed for commercial use.

## Author

Built by **Kyle (ChaosKyle)** — kyle@ksbdigital.com — [developereq.com](https://developereq.com)

If you used this and shipped something, I'd love to hear it. Tag me. Send me an email. The follow-up superpower works both ways.

---

If this repo helped you, ⭐ it. The signal is what helps other engineers find it.
