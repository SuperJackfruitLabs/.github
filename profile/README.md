# Super Jackfruit Labs

**A solo experimentation lab for AI agent infrastructure.** One person, several half-lit rooms, and a standing rule: *the lab never closes.*

Everything here starts as a question — *what if agent runtimes had a proper control plane? what if a chat client assumed half the room was a machine?* — and gets built until it either works or teaches me why it can't. What survives ships in the open.

🌐 [superjackfruit.com](https://superjackfruit.com/) · 👤 built by [@rakeshgangwar](https://github.com/rakeshgangwar)

---

## 🔭 What's on the bench

The through-line is **multi-agent systems that a human can actually operate** — the load-bearing, unglamorous parts: control planes, approval gates, runtime management, and the surfaces where one person meets a fleet of agents.

### [agentpod](https://github.com/SuperJackfruitLabs/agentpod) — *lit & steady · open for business*

A fleet/facilities console for agent runtimes. One place to manage the environments agents live in — filesystem, logs, terminal, config, health, lifecycle, cleanup, provisioning — across machines, harnesses, and NAT boundaries. **Attach-first**: point it at runtimes you already run, or let it provision new ones.

Go node-agent (dials out, no inbound ports) → Bun + Hono + Postgres hub → SvelteKit console. Ships descriptors for Hermes, OpenClaw, Claude Code, Codex, OpenCode and Pi. Self-hostable.

### [kaambaan](https://github.com/SuperJackfruitLabs/kaambaan) — *lit & steady · open for business*

A multi-tenant Kanban board that orchestrates **external** AI agents — running anywhere, under any harness — through pipeline stages with human approval gates. The board is the control plane; agents bring their own runtime.

**काम** (*kaam*, "work") + **बाण** (*bāṇ*, "arrow") — the arrows of work you fire toward Done. Built on Cloudflare Workers, Durable Objects, D1, Queues. Deployed at [kaambaan.dev](https://kaambaan.dev); P0 through P14 have shipped, tagged *First Flight*.

### [supermessage](https://github.com/SuperJackfruitLabs/supermessage) — *half-lit · enter at your own risk*

A cross-platform Matrix client built for rooms whose other occupants are agents as often as people. Agent-aware timeline rendering, approvals-from-chat, and a reading surface rather than a chat log — because agents write at length.

Tauri 2 + matrix-rust-sdk + Svelte 5, one codebase for iOS, Android, macOS, Windows, and Linux. The repo carries a code-grounded parity analysis against Element, Cinny, FluffyChat and Nheko that will tell you, honestly, when to use one of those instead.

---

More experiments — MCP servers, odd tools, and things that never fit a category — are catalogued over at [superjackfruit.com](https://superjackfruit.com/).

## 🧭 How the lab runs

- **Docs-first, then strict TDD.** The specification is the source of truth; code follows it.
- **Honest READMEs.** Status sections say what does *not* work yet, and point you elsewhere when something else is genuinely better today.
- **Attach-first and self-hostable.** Bring your own runtime, your own homeserver, your own infrastructure.
- **Open by default.** If it's useful outside my own machine, it ends up here.

## 🛠️ The usual stack

TypeScript · Rust · Go · Python · Svelte & SvelteKit · React · Tauri 2 · Bun + Hono · Cloudflare Workers, Durable Objects, D1 · Postgres · zod · Vitest

## 📫 Get in touch

Solo lab, open door. Issues and discussions on any repo are the fastest route — otherwise:

- LinkedIn: [Rakesh Gangwar](https://linkedin.com/in/rakeshgangwar01)
- Twitter: [@rakesh_gangwar1](https://twitter.com/rakesh_gangwar1)
- Email: [mail@rakeshgangwar.com](mailto:mail@rakeshgangwar.com)

---

*"The true potential of AI will be realized not through individual models, but through diverse ecosystems of specialized agents working in harmony."*

**walk in · browse the signs · everything's open**
