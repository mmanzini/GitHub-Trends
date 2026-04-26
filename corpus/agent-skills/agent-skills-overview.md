# Agent Skills Overview

"Agent skills" is the emerging packaging format for capabilities that LLM coding agents (primarily [[claude-code-overview|Claude Code]], also Codex and Cursor) can load and invoke. A skill is a self-contained bundle: instructions, helper code, sometimes prompts and assets, distributed as a Git repo or via registries like skills.sh.

## What's in This Folder
- [[fireworks-tech-graph]] — SVG/PNG technical diagrams
- [[darwin-skill]] — autonomous self-improving skill loop
- [[caveman]] — token-reduction skill (also relevant to [[ai-cost-management]])
- [[html-ppt-skill]] — HTML presentations with themes/layouts
- [[design-extract]] — extract design systems from any website
- [[video-use]] — agentic video editing
- [[uzi-skill]] — investment analysis skill distilling 51 professionals, 22 dimensions, 180 rules across A/HK/US markets
- [[huashu-design]] — HTML-native design skill for Claude Code (Chinese-native entry in the design-skill ecosystem)
- [[kami]] — document design system skill: six templates (one-pager, resume, slides, portfolio, letter, long-form doc)
- [[diagram-design]] — thirteen editorial-quality diagram types in HTML/SVG, no Mermaid

## Patterns Worth Noting
- **Domain-specific skills** dominate the trending list — investment analysis, video editing, design extraction. The skill format is being used to encode *expertise*, not just *tools*.
- **Multi-platform compatibility** — most new skills target Claude Code + Codex + Cursor simultaneously, treating "agent skill" as a portable abstraction.
- **Self-improving skills** — [[darwin-skill]] introduces a meta-skill: a skill that improves other skills.
- **Token efficiency as a skill** — [[caveman]] cuts tokens 65% through prompt-style transformation alone.

## Key Takeaways
- Skills are becoming a competitive surface: multiple repos compete for the same job (e.g. design extraction, presentation generation).
- Quality bar is rising fast — themes, layouts, animations are expected (see [[html-ppt-skill]]).
- The format itself is portable across vendors — cross-vendor compatibility is a feature, not an accident.

## Related
- [[claude-code-overview]]
- [[ai-cost-management]]
