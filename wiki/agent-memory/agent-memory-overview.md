# Agent Memory — Overview

Persistent memory for LLM agents — the community's **sharpest current pain point** based on trending velocity. [[mempalace]] hit ~46K stars in 11 days; no other agent-tooling category in the recent trending data climbed that fast.

## The Two Layers
1. **Storage** — vector-backed memory with MCP integration so any compatible harness picks it up. [[mempalace]] is the breakout: ChromaDB-backed, MCP-native, "best benchmarked" claim.
2. **Observability** — UI surfaces that let humans see what an agent remembers. [[hermes-hudui]] frames it as a "consciousness monitor."

## Why It Matters
- As agents accumulate long-running state, **what they remember** becomes as load-bearing as **what they can do**.
- MCP-native delivery is now the expected packaging — no integration code for users of [[claude-code-overview|Claude Code]], Cursor, Windsurf, etc.
- Memory pairs naturally with [[browser-harness]]-style self-extending agents (persist learned helpers) and [[weft]]-style durable execution.

## Key Takeaways
- Memory is the bottleneck holding back agent quality once cost and capability stop being the binding constraints.
- Storage and observability are emerging as **distinct** companion categories.
- Verify "best benchmarked" claims on your workload — vector-store performance is highly query-pattern dependent.

## Related
- [[mempalace]]
- [[hermes-hudui]]
- [[browser-harness]]
- [[weft]]
- [[codeburn]] — observability for cost; structurally analogous to memory observability
