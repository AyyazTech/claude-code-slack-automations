# 1. Standup Summarizer

Reads the last 24 hours of your `#standup` channel and posts a clean 3-bullet summary covering shipped, in-progress, and blocked items.

📺 **See it in action:** [Watch the AyyazTech tutorial](https://youtube.com/@AyyazTech)

---

## When to Use

- Morning catch-up after PTO
- Joining a new team mid-sprint
- "What did we ship yesterday?" Slack question
- Async-first teams where standups are written, not spoken

## Saves

~5 minutes per day per person reading 30+ standup messages.

## Prompt

See [`prompt.md`](./prompt.md) — copy-paste into your `#standup` channel.

## Routing

Routes to **Chat mode** (not Code) by default. This is a summarization task, not a coding task — the routing is correct.

If your routing mode is set to "Code only", append `Just summarize, no code action needed.` to force chat behavior.

## Requirements

- `@Claude` invited to the channel where you mention it
- Routing mode: **Code + Chat** (set in Claude App Home)

---

## 📺 Watch the Full Tutorial

[![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch%20Tutorial-red?logo=youtube)](https://youtube.com/@AyyazTech)

🔔 [Subscribe to AyyazTech](https://youtube.com/@AyyazTech?sub_confirmation=1) — best AI coding tools, models, and workflows.

🌐 [ayyaztech.com](https://ayyaztech.com) — more tutorials, scripts, and guides.

---

## ⭐ If This Helped You...

- ⭐ Star the [repo](https://github.com/AyyazTech/claude-code-slack-automations)
- 🔔 [Subscribe on YouTube](https://youtube.com/@AyyazTech?sub_confirmation=1)
- 🌐 Visit [ayyaztech.com](https://ayyaztech.com)
