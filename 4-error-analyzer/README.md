# 4. Error Analyzer

Paste any production error log in Slack — Claude reads the relevant code in your repo, finds the bug, and opens a PR with the fix.

📺 **See it in action:** [Watch the AyyazTech tutorial](https://youtu.be/_71wMqXeZAA)

---

## When to Use

- Production error fired in `#alerts` or `#bugs`
- Stack trace from Sentry/Datadog you want investigated fast
- "What broke?" Slack DMs with a log paste
- Replicating a customer-reported error

## Saves

~30-60 minutes per error. Goes from log → root cause → fix PR in one Slack message.

## Prompt

See [`prompt.md`](./prompt.md) — paste the error log directly in the channel.

## Routing

Routes to **Code mode** automatically.

## Requirements

- `@Claude` invited to the channel
- Claude GitHub App installed on the target repo
- Repo connected at claude.ai/code
- Stack trace must reference real file paths Claude can access in the repo

## Output

- Root cause analysis posted in Slack thread
- New branch with proposed fix
- PR opened automatically with description explaining the fix
- "Create PR" / "View Session" action buttons

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
