# 2. PR Reviewer

Paste any GitHub PR link in Slack — Claude clones the repo in a cloud session, reads the diff, and posts a review back in the thread. Optionally also comments on the GitHub PR itself.

📺 **See it in action:** [Watch the AyyazTech tutorial](https://youtu.be/_71wMqXeZAA)

---

## When to Use

- Async PR review when reviewer is in a different timezone
- "Quick second opinion" before merging
- Pre-review filter — let Claude catch the obvious bugs first
- Reviewing your own PR before requesting human review

## Saves

~30 minutes per PR. Catches missing tests, error handling gaps, security issues.

## Prompt

See [`prompt.md`](./prompt.md) — copy-paste into your `#engineering` channel.

## Routing

Routes to **Code mode** automatically — runs a Claude Code session in the cloud.

## Requirements

- `@Claude` invited to the channel
- Claude GitHub App installed on the target repo
- Repo connected at claude.ai/code

## Output

- Inline review summary in the Slack thread
- Optional GitHub line-by-line comments (ask for it explicitly)
- "View Session" + "Create PR" action buttons

---

## 📺 Watch the Full Tutorial

[![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch%20Tutorial-red?logo=youtube)](https://youtu.be/_71wMqXeZAA)

🔔 [Subscribe to AyyazTech](https://youtube.com/@AyyazTech?sub_confirmation=1) — best AI coding tools, models, and workflows.

🌐 [ayyaztech.com](https://ayyaztech.com) — more tutorials, scripts, and guides.

---

## ⭐ If This Helped You...

- ⭐ Star the [repo](https://github.com/AyyazTech/claude-code-slack-automations)
- 🔔 [Subscribe on YouTube](https://youtube.com/@AyyazTech?sub_confirmation=1)
- 🌐 Visit [ayyaztech.com](https://ayyaztech.com)
