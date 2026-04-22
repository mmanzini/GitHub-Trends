# weft

A programming language designed for AI systems. **LLM calls, human-in-the-loop pauses, databases, agents, and APIs are first-class language primitives** with end-to-end type safety, durable execution, and a visual graph view.

- **Repo:** [WeaveMindAI/weft](https://github.com/WeaveMindAI/weft)
- **Stars:** ~890 (2026-04-20)
- **Created:** 2026-04-15
- **Language:** Rust

## Why It Matters
- The most philosophically distinct entry in the recent agent ecosystem — instead of "AI in your existing language," it asks **what should a language for AI workflows actually look like?**
- Treats agent coordination as a **language design problem**, not a framework problem.
- Durable execution baked in = no need to bolt on workflow engines (Temporal, Inngest, etc.) for long-running agent tasks.
- Visual graph view suggests a hybrid text + visual programming model.

## Distinguishing Primitives
- **LLM call** as a typed expression — not an SDK function.
- **Human-in-the-loop pause** as a language construct — durable wait, not a callback.
- **Agents and APIs** as types/effects with end-to-end checking.

## Key Takeaways
- Early but ambitious — likely a leading indicator for "AI-native programming" as a category.
- Rust implementation = serious about runtime quality.
- A natural counter-position to harness-style approaches like [[claw-code]] and [[browser-harness]].

## Related
- [[agent-frameworks-overview]]
- [[claw-code]]
- [[mempalace]] — durable state often pairs with durable execution
