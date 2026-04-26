# Agent Frameworks Overview

Frameworks and harnesses for building autonomous agents — the runtime layer underneath domain-specific [[agent-skills-overview|skills]]. The trending data shows four divergent design philosophies emerging:

1. **Minimalist self-healing** — tiny harnesses where the LLM writes its own missing helpers ([[browser-harness]]).
2. **Language-first** — a programming language whose primitives *are* agents, LLM calls, and human-in-the-loop pauses ([[weft]]).
3. **Vendor-alternative CLIs** — community Rust harnesses competing with first-party tools ([[claw-code]]).
4. **Domain-specific harnesses** — e.g. protocol reverse-engineering with built-in browser/MITM ([[anything-analyzer]]).

## What's in This Folder
- [[browser-harness]] — 592-line self-healing browser agent
- [[anything-analyzer]] — protocol/network analysis with embedded browser, MITM, MCP server
- [[claw-code]] — Rust CLI alternative to Claude Code (cross-link)

## Patterns Worth Noting
- **Less framework, more agent.** The [[browser-harness]] thesis: at 592 lines, the LLM can fill gaps faster than a maintainer can specify them. Suggests heavy frameworks may be the wrong abstraction.
- **MCP everywhere.** New tools ship MCP servers as a default integration layer (see [[anything-analyzer]], [[design-extract]]).
- **Self-healing.** The browser-harness pattern — agent writes its own missing helper functions mid-task — is novel enough to warrant a dedicated explainer.

## Key Takeaways
- The "framework" is collapsing toward minimal scaffolding plus self-extension.
- MCP is the de facto interop standard for trending tools.
- Vendor-neutral harnesses (Claude + OpenAI both supported) are the norm, not the exception.

## Related
- [[claude-code-overview]]
- [[weft]] — the AI-native language angle
- [[mempalace]]
