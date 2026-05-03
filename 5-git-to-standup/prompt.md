# Standup From Git — Slack Prompt

Replace `OWNER/REPO` with your repo:

```
@Claude generate my standup from yesterday's commits in repo OWNER/REPO
Group as: Shipped / In Progress / Blockers. Post directly here.
```

## Example

```
@Claude generate my standup from yesterday's commits in repo AyyazTech/slack-claude-demo
Group as: Shipped / In Progress / Blockers. Post directly here.
```

## Variations

**Multi-day standup (post-weekend):**
```
@Claude generate my standup covering the last 3 days of my commits in repo OWNER/REPO
Group as: Shipped / In Progress / Blockers. Post directly here.
```

**Specific time window:**
```
@Claude generate my standup from my commits in repo OWNER/REPO since 9am yesterday Pakistan time
Group as: Shipped / In Progress / Blockers.
```

**With PR context:**
```
@Claude generate my standup from yesterday's commits AND open PRs in repo OWNER/REPO
Group as: Shipped (merged) / In Progress (open PRs) / Blockers (failing CI). Post directly here.
```

**Filter by your git email:**
```
@Claude generate my standup from commits authored by me (email: yourname@example.com) in the last 24 hours in repo OWNER/REPO
Group as: Shipped / In Progress / Blockers. Post directly here.
```

---

📺 [Watch the tutorial](https://youtu.be/_71wMqXeZAA) · 🔔 [Subscribe](https://youtube.com/@AyyazTech?sub_confirmation=1) · 🌐 [ayyaztech.com](https://ayyaztech.com)
