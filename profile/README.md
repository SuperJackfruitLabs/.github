# Super Jackfruit Labs

**A solo experimentation lab for AI agent infrastructure.** One person, several
half-lit rooms, and a standing rule: *the lab never closes.*

[![Lab: independent](https://img.shields.io/badge/lab-independent-555)](https://github.com/rakeshgangwar)
[![Products: open source](https://img.shields.io/badge/products-open_source-blue)](https://github.com/orgs/SuperJackfruitLabs/repositories?type=public)

Everything here starts as a question — *what if agent runtimes had a proper
control plane? what if a chat client assumed half the room was a machine?* —
and gets built until it either works or teaches me why it can't. What survives
ships in the open.

[superjackfruit.com](https://superjackfruit.com/) · built by [@rakeshgangwar](https://github.com/rakeshgangwar)

## What's on the bench

The through-line is **multi-agent systems that a human can actually operate**:
runtime management, work orchestration, approval gates, and the surfaces where
one person meets a fleet of agents. Each product has its own scope and maturity;
its README and releases are the place to check current support and limitations.

| Product | What it does | Start here |
|---|---|---|
| [AgentPod](https://github.com/SuperJackfruitLabs/agentpod) | Manage agent runtimes, sessions, environments, and lifecycle across machines. Go node-agent, Bun/Hono hub, SvelteKit console. | [Setup and status](https://github.com/SuperJackfruitLabs/agentpod#readme) · [Releases](https://github.com/SuperJackfruitLabs/agentpod/releases) |
| [Superpipeline](https://github.com/SuperJackfruitLabs/superpipeline) | Coordinate external agents through boards, pipeline stages, runs, and human approval gates. Cloudflare Workers, Durable Objects, and D1. | [Setup and status](https://github.com/SuperJackfruitLabs/superpipeline#readme) · [Docs](https://docs.superpipeline.dev) |
| [Supermessage](https://github.com/SuperJackfruitLabs/supermessage) | Matrix chat for people and agents, with a shared Rust core, Tauri/Svelte desktop, SwiftUI iOS, and Compose Android clients. | [Platform status](https://github.com/SuperJackfruitLabs/supermessage#readme) · [Desktop releases](https://github.com/SuperJackfruitLabs/supermessage/releases) |
| [SuperMD](https://github.com/SuperJackfruitLabs/supermd) | A native Rust/GPUI Markdown editor with plain files, live formatting, wiki links, backlinks, and a workspace graph. | [Features and screenshots](https://github.com/SuperJackfruitLabs/supermd#readme) · [Downloads](https://github.com/SuperJackfruitLabs/supermd/releases) |

Supermessage has public desktop builds for Linux, macOS, and Windows; native
mobile source is separate from mobile store availability. Read its release and
platform notes before choosing a build.

SuperMD is the writing tool in the suite: this lab spends a great deal of time
in Markdown, and it is where a Rust-native UI stack gets tested against the
needs of a real application.

## How the lab runs

- **Docs-first, with tests.** Specifications and checks should agree with the code.
- **Honest READMEs.** Distinguish implemented features, available builds, and plans.
- **Attach-first and self-hostable.** Bring your own runtime, homeserver, and infrastructure where the product supports it.
- **Open by default.** Useful experiments belong where others can inspect and use them.

## Get in touch

Repository issues are the fastest route for product questions.

[LinkedIn](https://linkedin.com/in/rakeshgangwar01) ·
[Twitter](https://twitter.com/rakesh_gangwar1) ·
[Email](mailto:mail@rakeshgangwar.com)

*walk in · browse the signs · everything's open*
