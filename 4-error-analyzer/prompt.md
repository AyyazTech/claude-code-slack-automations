# Error Analyzer — Slack Prompt

Replace `OWNER/REPO` and paste the actual error log:

```
@Claude analyze this error and suggest a fix:

<paste error log here including stack trace>

Repo: OWNER/REPO
```

## Example

```
@Claude analyze this error and suggest a fix:

Error: Stripe webhook returned 503 Service Unavailable
  at processWebhook (src/webhooks/stripe.js:42)
  at handleRequest (src/router.js:88)
Stack trace shows retry attempted 5 times, all failed.

Repo: AyyazTech/slack-claude-demo
```

## Variations

**Investigate without fixing:**
```
@Claude analyze this error and explain the root cause. Do NOT make code changes — just diagnose:

<error log>

Repo: OWNER/REPO
```

**Fix + add a regression test:**
```
@Claude analyze this error, fix it, AND add a regression test that would have caught it:

<error log>

Repo: OWNER/REPO
```

**Multi-file investigation:**
```
@Claude this error spans multiple files. Trace it through the codebase, find where it originates, and propose a fix:

<error log>

Repo: OWNER/REPO
```

---

📺 [Watch the tutorial](https://youtube.com/@AyyazTech) · 🔔 [Subscribe](https://youtube.com/@AyyazTech?sub_confirmation=1) · 🌐 [ayyaztech.com](https://ayyaztech.com)
