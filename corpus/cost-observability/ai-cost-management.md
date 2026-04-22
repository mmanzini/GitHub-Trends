# AI Cost Management

A small but recurring trending category: tools and techniques for understanding and reducing AI coding spend. Two complementary patterns dominate the trending data:

1. **Observability** — see where tokens go. [[codeburn]] is the breakout example: TUI dashboard across Claude Code, Codex, and Cursor.
2. **Reduction** — change *how* you prompt to use fewer tokens. [[caveman]] cuts ~65% by rewriting prompts in minimal style.

## Why This Is a Trend
- AI coding costs were invisible for the first wave; now devs are heavy users with monthly bills, and the abstraction is leaking.
- Multi-tool workflows (Claude Code + Cursor + Codex) make per-tool dashboards inadequate — multi-vendor observability is now table stakes.
- Cost-reduction skills are one of the easiest ways to demonstrate ROI on prompt engineering.

## Key Takeaways
- Observe first, then optimize: [[codeburn]] before [[caveman]], not the other way around.
- ~65% token reduction (the [[caveman]] claim) is workload-dependent — measure on your own traffic.
- Cost is now a first-class concern in agent design, not an afterthought.

## Related
- [[codeburn]]
- [[caveman]]
- [[claude-code-overview]]
- [[darwin-skill]] — can optimize skills against a cost rubric, not just quality
