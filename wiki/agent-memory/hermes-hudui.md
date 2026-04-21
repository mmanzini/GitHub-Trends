# hermes-hudui

Web UI "consciousness monitor" for Hermes — an AI agent with persistent memory. Provides a dashboard for observing agent state, memory contents, and activity in real time.

- **Repo:** [joeynyc/hermes-hudui](https://github.com/joeynyc/hermes-hudui)
- **Stars:** ~900 (2026-04-15)
- **Created:** 2026-04-09
- **Language:** TypeScript

## Why It Matters
- Observability for agent **memory** specifically — not just token cost (see [[codeburn]]) but what the agent *remembers*.
- The "consciousness monitor" framing is provocative: as agents accumulate persistent state, watching that state becomes a UX problem of its own.
- Complementary to [[mempalace]]: one stores memory, the other lets you look at it.

## Key Takeaways
- Memory observability is an emerging companion category to memory storage.
- TypeScript dashboard — easy to fork as a UI shell for other persistent-memory agents.
- The need only exists if your agent has meaningful long-running state — a signal that more agents now do.

## Related
- [[mempalace]]
- [[codeburn]] — observability for cost, not memory
- [[agent-frameworks-overview]]
