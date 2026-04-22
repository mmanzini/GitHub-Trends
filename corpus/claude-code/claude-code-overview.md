# Claude Code Overview

Claude Code is Anthropic's official CLI / IDE-integrated coding agent powered by Claude. It is the centre of gravity for a fast-growing ecosystem of skills, plugins, harnesses, and tooling — much of which is showing up in GitHub trending data.

## Ecosystem Pillars
- **Skills** — reusable capability packages the agent can load. See [[agent-skills-overview]].
- **Cost & token observability** — tooling like [[codeburn]] and token-reduction tricks like [[caveman]].
- **Alternative harnesses** — community CLIs like [[claw-code]] (Rust) reimplement the experience.
- **Plugins** — design-system tooling like [[design-extract]] ships as a Claude Code plugin.
- **Domain-specific agents** — e.g. [[career-ops]] (job search), [[video-use]] (video editing).
- **Architecture exploration** — repos like [[openmythos]] reverse-engineer Claude's internals.

## Why It Matters
- Claude Code skills are emerging as a **packaging format** for agent capabilities — comparable to npm packages but for LLM behaviours.
- The community is willing to build *and* fork the platform: [[claw-code]] hit 100K stars faster than any repo in history, signalling appetite for open agent infrastructure.
- The same ecosystem dynamics (cost transparency, packageable skills) appear across [[ai-cost-management]] and [[agent-skills-overview]].

## Key Takeaways
- "Claude Code" is no longer just a tool — it's a platform with a packaging format (skills), a plugin model, a costing surface, and active competition from open-source harnesses.
- Trending repos increasingly tag themselves `claude-code` — useful signal for spotting new community work.
- For content creators: the official-vs-community story is fertile ground (see [[claw-code]]).

## Related
- [[agent-skills-overview]]
- [[codeburn]]
- [[claw-code]]
- [[caveman]]
