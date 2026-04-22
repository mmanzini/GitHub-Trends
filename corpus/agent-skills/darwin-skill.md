# darwin-skill

Autonomous skill optimization system: evaluate → improve → test → keep or revert. Inspired by Andrej Karpathy's "autoresearch" idea and Darwinian ratchet mechanisms — only changes that measurably improve a scoring rubric are retained. Compatible with Claude Code, Codex, and skills.sh.

- **Repo:** [alchaincyf/darwin-skill](https://github.com/alchaincyf/darwin-skill)
- **Stars:** ~1.2K (2026-04-19), trended throughout the week
- **Created:** 2026-04-13
- **Language:** HTML

## Why It Matters
- A **meta-skill**: it improves *other* skills. Recursive AI / agents-improving-agents — a content-heavy angle for AI commentary.
- The ratchet mechanism (only-keep-improvements) is the same evolutionary safety pattern used in much larger ML loops; applying it to skill files is a fresh framing.
- Validates the idea that skills can be treated as **optimizable artefacts**, not static configs.

## How It Works (At a Glance)
- Define a scoring rubric for the target skill.
- Run an iterative loop: propose a change → evaluate against the rubric → keep if better, discard otherwise.
- Repeat indefinitely; the ratchet guarantees monotonic improvement on the chosen metric.

## Key Takeaways
- Self-improving agent tooling is real and shipping.
- Ratchet mechanism = no regressions on the scored axes.
- Pairs well with cost tooling like [[codeburn]] — improvements can be measured against token/cost budgets, not just task quality.

## Related
- [[agent-skills-overview]]
- [[claude-code-overview]]
- [[codeburn]]
