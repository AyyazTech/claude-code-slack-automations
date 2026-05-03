# Thread → Docs — Slack Prompt

**IMPORTANT:** Reply IN the thread you want documented (not in the channel). Claude reads the entire thread context.

Replace `OWNER/REPO` and adjust the file path:

```
@Claude write this thread up to /docs/<topic-name>.md in repo OWNER/REPO
When done, post the branch and PR link here.
```

## Example

```
@Claude write this thread up to /docs/stripe-webhook-retries.md in repo AyyazTech/slack-claude-demo
When done, post the branch and PR link here.
```

## Variations

**Architectural Decision Record (ADR) format:**
```
@Claude write this thread up as an ADR (Architectural Decision Record) at /docs/adr/<number>-<topic>.md in repo OWNER/REPO
Use the standard ADR template: Context, Decision, Consequences. When done, post the PR link.
```

**FAQ format:**
```
@Claude write this thread up as an FAQ entry at /docs/faq/<topic>.md in repo OWNER/REPO
Format as Q&A. When done, post the PR link.
```

**Post-mortem format:**
```
@Claude write this thread up as a post-mortem at /docs/postmortems/<incident-id>.md in repo OWNER/REPO
Include: timeline, root cause, what went well, what to improve, action items. When done, post the PR link.
```

---

📺 [Watch the tutorial](https://youtube.com/@AyyazTech) · 🔔 [Subscribe](https://youtube.com/@AyyazTech?sub_confirmation=1) · 🌐 [ayyaztech.com](https://ayyaztech.com)
