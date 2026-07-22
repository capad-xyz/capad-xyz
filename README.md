### Hi, I'm Aadarsh (aka "capad", just the name I like to go by online)

I build developer tools and desktop apps: small, fast, genuinely-free software for people who live in a terminal and an editor. Most of what I make is open source and keyless by default.

I came up through full-stack web work and kept drifting lower in the stack, toward the close-to-the-metal things: web unlockers, git internals, on-device Android hacks. I like building the unglamorous infrastructure that other tools quietly lean on.

By day I'm a software engineer and architect on production SaaS. Most recently I designed and built an agentic AI compliance platform end to end: a tool-calling assistant with safety-gated write actions (propose-then-confirm, server-side re-validation, audit logging), a deterministic statutory-deadline engine, and a multi-provider LLM layer (OpenAI / Gemini / Claude) with cost accounting and admin-governed model routing. Before that: transcription, document-AI / OCR, and AI avatar platforms across React, React Native, Node, Python, MongoDB, and AWS.

Right now I'm building an open web-retrieval layer for AI agents, local AI usage telemetry, a git review companion, and a few things for the Nothing Phone.

## Featured projects

**[searchts](https://github.com/capad-xyz/searchts)** - The missing layer between AI and the web. An escalating open-source unlocker (browser-fingerprinted fetch, JS-render relay, stealth browser) plus keyless read / search / transcribe / grab across the open web, GitHub, YouTube, Reddit, Twitter, LinkedIn, and RSS. Ships as a CLI, an MCP server, and a Claude Code skill. Python, MIT, on PyPI.

**[burncard](https://github.com/capad-xyz/burncard)** - Accurate local AI usage telemetry for Claude Code and Codex: see what your agent sessions actually used and cost, computed from your own logs on your own machine. `npx burncard`. TypeScript.

**[Grove](https://github.com/capad-xyz/grove)** - A genuinely-free git review companion that sits beside your AI editor: a custom SVG commit graph, real diffs (even on merge commits), blame, instant spotlight search, and a worktree-first dashboard for when several agents are running at once. Rust + Tauri + Svelte 5, GPL-3.0.

**[GlyphMaps](https://github.com/capad-xyz/GlyphMaps)** - Mirror Google Maps turn-by-turn directions onto the 137-LED Glyph Matrix on the back of a Nothing Phone (4a) Pro, so you glance at the back of your phone instead of the screen. Built on a reverse-engineered notification pipeline and an unthrottled matrix path the official API doesn't give you. Shipped v1.0.0, signed APK on Releases. Kotlin, AGPL-3.0.

**[beep-beep-oss](https://github.com/capad-xyz/beep-beep-oss)** - An open-source, self-hostable universal chat client: all your messaging networks in one native inbox, nothing gated behind a paywall. Beeper's core architecture rebuilt in the open: Matrix homeserver + mautrix bridges + a native Tauri / Rust client. Already a working two-way WhatsApp messenger. AGPL-3.0, in progress.

Smaller delights: CoffeeBreath (a Rainmeter music widget that pulls the accent color from the current album art and breathes with the song), a glass Discord voice overlay for the desktop, and [capad.fyi](https://capad.fyi), a from-scratch Next.js + WebGL portfolio.

## What I work in

Day to day I reach for:

| Area              | Tools                                        |
| ----------------- | -------------------------------------------- |
| Agents, libraries | Python, TypeScript, MCP                      |
| Desktop apps      | Rust, Tauri, Svelte, TypeScript              |
| Mobile            | Kotlin, Android                              |
| Web platforms     | React, Next.js, Node, Express, MongoDB       |
| Infra, tooling    | Cloudflare, AWS, GitHub Actions, git, ffmpeg |

<details>
<summary><b>The fuller toolbox</b> (also comfortable in)</summary>

<br>

- **Web:** React, Next.js, Redux, Node, Express, Tailwind, Material UI, HTML, CSS
- **Motion and graphics:** GSAP, Motion, Lenis, SVG, WebGL (React Three Fiber)
- **Data:** MongoDB, PostgreSQL, Firebase, Sanity
- **AI:** multi-provider LLM integration (OpenAI, Gemini, Claude), agentic assistants with safety-gated actions, MCP servers, Claude Code skills, LLM training work
- **Languages:** TypeScript, JavaScript, Python, Rust, Kotlin, Lua, C
- **Build and tooling:** Docker, Webpack, npm, PyPI, Vercel, Git (GitHub / GitLab / Bitbucket)
- **Design:** Figma, Canva

</details>

## How I work

- Proof-first: a throwaway benchmark or prototype greenlights the approach before any integration.
- Reverse-engineering when there is no API: Maps' notification format, bot-wall fingerprints, bridge behavior.
- Everything ships with CI, real releases (PyPI, signed APKs), and a plain-English write-up.
- Free and open by default: MIT, GPL, or AGPL, chosen deliberately per project.

## Off the clock

I tinker with my Nothing Phone (custom Glyph Matrix experiments), build in public, and have a soft spot for tools that do one thing fast and then get out of the way.

## Reach me

- Portfolio: [capad.fyi](https://capad.fyi)
- Email: hi@capad.fyi
- Or open an issue on any of the repos above
