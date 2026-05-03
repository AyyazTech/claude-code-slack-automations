# Claude Code in Slack — 5 Free AI Automations

> Complete setup + 5 free AI automations using Anthropic's official **Claude in Slack** app. No webhooks. No paid Slack AI tier. No custom code. Just `@Claude` mentions in Slack — running on your existing Claude Pro plan.

[![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch%20Tutorial-red?logo=youtube)](https://youtube.com/@AyyazTech)
[![Subscribe](https://img.shields.io/badge/Subscribe-AyyazTech-red?logo=youtube)](https://youtube.com/@AyyazTech?sub_confirmation=1)
[![Website](https://img.shields.io/badge/Website-ayyaztech.com-06B6D4)](https://ayyaztech.com)

📺 **Watch the full tutorial:** [Claude Code in Slack — Complete Setup + 5 Free AI Automations (2026)](https://youtube.com/@AyyazTech) *(link will be updated after the video is published)*
🔔 **Subscribe to AyyazTech:** [@AyyazTech](https://youtube.com/@AyyazTech?sub_confirmation=1) — best AI coding tools, models, and workflows
🌐 **More content:** [ayyaztech.com](https://ayyaztech.com)

---

## 🎯 What You'll Build

5 free Slack AI automations using Anthropic's Claude Code in Slack:

| # | Automation | What It Does |
|---|-----------|--------------|
| 1 | **Standup Summarizer** | Reads `#standup` channel from yesterday → posts a 3-bullet brief |
| 2 | **PR Reviewer** | Paste a GitHub PR link → AI review back in the thread |
| 3 | **Thread → Docs** | Turn any technical Slack thread into a Markdown doc committed to GitHub |
| 4 | **Error Analyzer** | Paste any error log → Claude finds the bug AND opens a fix PR |
| 5 | **Standup From Git** | Claude reads YOUR yesterday's commits → posts your standup automatically |

All 5 work with the **official Anthropic "Claude in Slack" app** — no custom server, no webhooks, no paid integrations.

---

## ⚡ Prerequisites

- **Claude plan** with Claude Code access: Pro ($20/mo), Max, Team, or Enterprise (Free plan does NOT include Claude Code)
- **Slack workspace** where you have admin or "install apps" permission
- **GitHub repo** you want Claude to read/write to (for demos 2, 3, 4, 5)

---

## 🚀 Setup (5 minutes)

### 1. Install Claude in Slack

Visit: https://slack.com/marketplace/A08SF47R6P4 → click **Add to Slack** → authorize for your workspace.

### 2. Connect Your Anthropic Account

In Slack sidebar → click **Apps** → **Claude** → **Connect Account** → log in with your Anthropic account.

### 3. Set Routing Mode

In Claude App Home → set routing mode to **"Code + Chat"** (NOT "Code only" — Demo 1 needs chat mode).

### 4. Install the Claude GitHub App on Your Repo

Visit: https://github.com/apps/claude-code-anthropic → **Install** → choose **Only select repositories** → tick the repo Claude should work on.

Required permissions: Contents (read/write), Pull requests (read/write), Issues (read/write).

### 5. Connect Repo at claude.ai/code

Go to https://claude.ai/code → Settings → Connected Repositories → confirm your repo appears.

### 6. Invite @Claude to Your Channels

In each channel where Claude will work:

```
/invite @Claude
```

### 7. Verify

Type `@Claude hello` in any channel. If it replies, setup is complete.

---

## 📂 Folder Structure

Each folder below is one of the 5 automations. Each is independent — fork the whole repo or copy any single folder.

```
claude-code-slack-automations/
├── README.md                       ← you are here
├── .env.example                    ← optional environment template
├── 1-standup-summarizer/           ← Demo 1: channel summary
├── 2-pr-reviewer/                  ← Demo 2: PR review
├── 3-thread-to-docs/               ← Demo 3: thread → Markdown
├── 4-error-analyzer/               ← Demo 4: error log → fix PR
└── 5-git-to-standup/               ← Demo 5: commits → standup post
```

Each folder contains:
- `README.md` — what it does + when to use it
- `prompt.md` — the exact `@Claude` prompt to copy-paste in Slack

---

## 🛠️ Common Gotchas

| Issue | Fix |
|---|---|
| Wrong repo selected by Claude | Click **Change Repo** button OR include `owner/repo` in your prompt |
| Routed to Chat instead of Code | Click **Retry as Code** OR set routing mode to "Code only" |
| Rate limit hit | Sessions count against your Claude plan — upgrade to Max for heavy use |
| "I can't see your repo" | Install Claude GitHub App at github.com/apps/claude-code-anthropic on the specific repo |
| Direct push to main | Expected — Claude uses PR flow always (cloud session limitation) |

Full troubleshooting in the [video tutorial](https://youtube.com/@AyyazTech).

---

## 📺 Watch the Full Tutorial

[![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch%20Tutorial-red?logo=youtube)](https://youtube.com/@AyyazTech)

🔔 [Subscribe to AyyazTech](https://youtube.com/@AyyazTech?sub_confirmation=1) — best AI coding tools, models, and workflows.

🌐 [ayyaztech.com](https://ayyaztech.com) — more tutorials, scripts, and guides.

---

## ⭐ If This Helped You...

- ⭐ **Star this repo** to help others discover it
- 🔔 [**Subscribe on YouTube**](https://youtube.com/@AyyazTech?sub_confirmation=1)
- 🌐 **Visit** [ayyaztech.com](https://ayyaztech.com) for more content
- 🐛 Found a bug or want a new automation? **Open an issue** OR comment on the [YouTube video](https://youtube.com/@AyyazTech)

---

## 📜 License

MIT — fork freely, ship faster.
