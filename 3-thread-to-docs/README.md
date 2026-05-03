# 3. Thread → Docs to GitHub

Turn any technical Slack thread (e.g., a debate about how to implement something) into a structured Markdown doc, committed to a branch in your GitHub repo with a PR ready to merge.

📺 **See it in action:** [Watch the AyyazTech tutorial](https://youtube.com/@AyyazTech)

---

## When to Use

- Architectural decisions made in Slack threads (preserve them as ADRs)
- Bug post-mortems discussed in `#incidents`
- Technical Q&A threads that should become FAQ entries
- Deep-dive engineering threads worth documenting

## Saves

~30 minutes per doc. Eliminates "we discussed this in Slack but never wrote it down" drift.

## Prompt

See [`prompt.md`](./prompt.md) — reply IN the thread you want documented.

## Routing

Routes to **Code mode** automatically.

## Requirements

- `@Claude` invited to the channel where the thread exists
- Claude GitHub App installed on the target repo
- Repo has a `/docs/` folder (or the prompt creates one)

## Output

- New file at `/docs/<topic>.md` on a fresh branch
- "Create PR" button in Slack
- Branch + commit URL posted in the thread (if you ask for it)

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
