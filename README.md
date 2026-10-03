### Aadarsh Upadhyay

capad · [capad.fyi](https://capad.fyi) · [oss@capad.fyi](mailto:oss@capad.fyi) · [@aadarsh_io](https://x.com/aadarsh_io) · [LinkedIn](https://www.linkedin.com/in/aadarshupadhyay/)

I build the tools that should not need to exist. The ones that do frustrated me into building better ones: small, fast, free, and yours to keep. Most of what I ship is open source and keyless by default.

I came up through full-stack web work and kept drifting lower: web unlockers, git internals, on-device Android. Software engineer and architect. Most recently I designed and built [ComplyV](https://capad.fyi) (formerly Compliance Sarathi) at Appson, Jan–31 Jul 2026: an agentic compliance assistant whose writes are propose-then-confirm, re-checked on the server, and audit-logged. Before that, the Wordibly transcript editor. Finishing a BCA (Honours) at The Maharaja Sayajirao University of Baroda, expected 2028.

## Now

| | |
| --- | --- |
| **[searchts](https://github.com/capad-xyz/searchts)** | Keyless web layer for agents. PyPI **0.13.0**, CLI + MCP. |
| **Hare** | Review-and-report GitHub App, dogfooded on searchts. Not a SaaS. |
| **[Grove](https://github.com/capad-xyz/grove)** | Git review beside the AI editor. |
| **[GlyphMaps](https://github.com/capad-xyz/GlyphMaps)** | Next turn on the Nothing Glyph Matrix. |
| **[Dooper](https://github.com/capad-xyz/beep-beep-oss)** | Self-hostable inbox. Repo is `beep-beep-oss`. |

## Featured

**[searchts](https://github.com/capad-xyz/searchts)** — Fetch a URL or admit you cannot. Escalating unlocker (fingerprinted curl, Jina relay, stealth Chromium), fail-loud on thin pages and login walls. Decodes ChatGPT, Claude, Gemini, Grok, and Poe share links into the full conversation. CLI, MCP 2.x, Claude Code skill. `uvx --from "searchts[mcp]" searchts`. Python, MIT, [0.13.0 on PyPI](https://pypi.org/project/searchts/).

**[GlyphMaps](https://github.com/capad-xyz/GlyphMaps)** — Google Maps next-turn on the 137-LED Glyph Matrix of a Nothing Phone (4a) Pro, so the phone can sit face down. No Maps API key. Skips the throttled Glyph Toy path, holds the matrix only while navigating, then gives it back. Signed APK, v1.0.0. Kotlin, AGPL-3.0.

**[Grove](https://github.com/capad-xyz/grove)** — A free git review companion beside the editor: lane-drawn commit graph, real diffs, find-in-diff, live refresh, worktree-first when several agents are in flight. Electron, React, TypeScript, headless Node git engine. GPL-3.0, alpha.

**[Dooper](https://github.com/capad-xyz/beep-beep-oss)** — Self-hostable universal inbox: Synapse, mautrix bridges, a Tauri 2 client. Phase 1 verified on real bridged WhatsApp (login, inbox, history, optimistic send, session persistence). Product name Dooper; repo `beep-beep-oss`. AGPL-3.0.

**[burncard](https://github.com/capad-xyz/burncard)** — Local AI usage telemetry for Claude Code and Codex, computed from your own logs. `npx burncard`. TypeScript.

**Hare** — A review-and-report GitHub App (`@hare`) I dogfood on searchts. Summary, severity findings, inline bubbles, grounded in the diff and CI. Comment only. Not a SaaS, and not a CodeRabbit claim. Hare Bot is the separate chat-side template.

Also: [capad.fyi](https://capad.fyi) (Next.js, liquid-glass, Sanity), a Halls of Residence register prototype at [msu.capad.fyi](https://msu.capad.fyi), CoffeeBreath (a Rainmeter widget that takes its color from the album art), and a glass Discord voice overlay.

## Elsewhere

Contributor on [wmux](https://github.com/amirlehmam/wmux), not my project. As of 2 Oct 2026: 4 merged PRs (#135, #138, #153, #258) and 8 closed issues, mostly diff-pane freezes, CLI timeouts, and agent-browser install discovery.

## What I work in

| Area | Tools |
| --- | --- |
| Web | React, Next.js, TypeScript, Tailwind, Node, Express, MongoDB |
| Agents | Python, MCP, custom skills, AGENTS.md, runbooks |
| AI shipping | Propose-then-confirm writes, multi-provider LLMs, usage and cost accounting |
| Desktop | Electron, Tauri, React |
| Mobile | Kotlin, Android |
| Infra | Cloudflare Workers, GitHub Actions, AWS, git |

<details>
<summary><b>Also comfortable in</b></summary>

<br>

React Three Fiber, GSAP, Motion, WebGL, PostgreSQL, Firebase, Sanity, Rust and Kotlin with AI assist, Docker, Figma.

</details>

## How I work

- Proof first. A throwaway benchmark greenlights the approach before integration.
- Reverse-engineer when there is no API: Maps notifications, bot-wall fingerprints, bridge behavior.
- Ship with CI, a real release (PyPI, a signed APK), and a plain write-up.
- License picked on purpose: MIT, GPL, or AGPL.

## Reach me

Portfolio [capad.fyi](https://capad.fyi) · email [oss@capad.fyi](mailto:oss@capad.fyi) · or open an issue on any repo above.
