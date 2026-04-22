# wterm

A terminal emulator for the web. Built with a Zig/WASM parser and React + vanilla JS integration packages. From Vercel Labs.

- **Repo:** [vercel-labs/wterm](https://github.com/vercel-labs/wterm)
- **Stars:** ~2.1K (2026-04-20)
- **Created:** 2026-04-14
- **Language:** TypeScript

## Why It Matters
- Vercel Labs entry into web terminals — signals continued investment in browser-as-OS workflows.
- Zig + WASM for the parser = serious performance posture; this isn't a toy.
- Plausible primitive for browser-based UIs that need to surface real terminal output (logs, REPLs, agent CLIs) — though that connection is inferred, not stated by the project.

## Key Takeaways
- React and vanilla JS adapters out of the box.
- Zig/WASM parser core.
- Possible pairing with browser-based agent UIs (see [[browser-harness]]) — speculative, not endorsed by the project.

## Related
- [[rattles]] — terminal *output* primitive (spinners) on the native side
- [[browser-harness]]
