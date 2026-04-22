# design-extract

Extract any website's complete design language — colors, typography, spacing, shadows, and more — with a single `npx` command. Ships as both a CLI and a Claude Code plugin, with an MCP server and multi-platform emitters (iOS SwiftUI, Android Compose, Flutter, WordPress, Tailwind v4, Figma variables, shadcn/ui).

- **Repo:** [Manavarya09/design-extract](https://github.com/Manavarya09/design-extract)
- **Stars:** ~1.1K (2026-04-20)
- **Created:** 2026-04-15
- **Language:** JavaScript
- **Topics:** agent-skill, claude-code-plugin, cli, design-system, design-tokens, figma, mcp-server, playwright, shadcn-ui, tailwind, web-scraping

## Why It Matters
- Closes the loop on [[awesome-design-md]]: that repo provides hand-curated DESIGN.md files; this one *extracts* a DESIGN-like token set from any live site.
- Ships as **three packaging formats simultaneously**: npx CLI, Claude Code plugin, and MCP server — the emerging pattern for agent-first dev tools.
- Multi-platform emitters mean the extracted system travels to native app stacks, not just web — broad surface area.
- Includes WCAG remediation — design quality meets accessibility baseline.

## Key Takeaways
- Uses Playwright under the hood to render + introspect the target page.
- MCP server makes it usable from Claude Code, Cursor, and Windsurf out of the box.
- DTCG tokens as the interchange format — standard, cross-tool portable.

## Related
- [[awesome-design-md]]
- [[agent-skills-overview]]
- [[claude-code-overview]]
- [[fireworks-tech-graph]] — sibling "skill as visual generator"
- [[html-ppt-skill]] — sibling visual-output skill
