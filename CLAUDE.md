# GitHub Trends – Project Instructions

## Git Workflow

**Preferred:** commit and push directly to `main`.

```
git add <files>
git commit -m "..."
git push -u origin main
```

**If the harness forces you onto a `claude/...` feature branch** (and forbids pushing elsewhere), then after pushing and opening the draft PR:

1. Mark the PR as ready for review (`update_pull_request` with `draft: false`).
2. Enable auto-merge with squash (`enable_pr_auto_merge` with `merge_method: "SQUASH"`).

Auto-merge is enabled on the repo and there are no required checks, so the PR will land on `main` immediately. Do this on every session that opens a PR — no need to ask.

## What This Repo Does

Generates a daily GitHub trending digest at `trending/YYYY-MM-DD-trending.md`. Each file covers:
- Top 10 repos created in the last 7 days (sorted by stars)
- Top 5 repos created in the last 30 days (sorted by stars)

Repos relevant to AI agents, Claude Code, LLM tooling, or developer experience are flagged `[AI/DEV]`.
