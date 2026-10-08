# Aporia Nous

**Local-first AI, autonomous agents, and the systems underneath them.**

I build the parts of a system that have to be fast, local and correct — memory
and retrieval, native performance engines, data pipelines, and agent automation
— and I measure what I ship.

- Agent memory & retrieval (deterministic, model-free)
- Backend & API services (FastAPI, Docker, RCON, CI/CD)
- Automation & bots (Discord, workflows, MCP)

## Selected work

**2026-06**
- **Dockerized community backend** — a Docker Compose stack: a FastAPI service (Steam OAuth, player tracking, teleport API), a Discord bot, SQLite with persistent volumes, an RCON bridge, health checks, and CI/CD auto-build to Docker Hub. → [Web-Link-Host-Isle](https://github.com/DrSinister31/Web-Link-Host-Isle)
- **Discord app legal pages** — Privacy Policy + Terms published as a single GitHub Pages document for a Discord app. → [Privacy-TOS](https://github.com/DrSinister31/Privacy-TOS)

**2026-07**
- **Proximity-voice installer + Discord verification** — a one-click installer that sets up and configures a Mumble voice server for a game community, pre-connects clients, and ties each user to their Discord account via a bot-issued 6-digit code. → [Sinister-s-Park-Mumble](https://github.com/DrSinister31/Sinister-s-Park-Mumble)

**2026-08**
- **Morpheus — a small language + native compiler** — designed and implemented a language (lexer, parser, AST, interpreter, VM) plus a native compiler that emits C++; used for the performance-critical parts below. *Proprietary core — described, not published.*
- **TB-scale data pipeline** — streamed a 1.16 TB corpus at ~72 MB/s across 33 concurrent streams with zero rate-limit failures, an additive checkpoint/resume ledger, and de-duplication gates. *Proprietary core.*

**2026-09**
- **Semantic memory & retrieval engine** — local, deterministic, no model weights: ~98% of related queries answered and ~90% of unrelated queries refused, at ~162 ms/query on a sub-GB store. *Proprietary core.*
- **Emergent knowledge graph** — 60,630 nodes / 17,264 modules built from embedding kNN and quality-gated. *Proprietary core.*

**2026-10**
- **intake** — turns a folder of messy documents into clean records and a task list, validated with a human-review flag, optionally posting a summary to Discord/Slack. → [intake](https://github.com/aporianous/intake)
- **Live web product** — Next.js static site on Vercel with CDN, custom routing, analytics, and DNS (SPF/DKIM/DMARC). → [aporianous.com](https://aporianous.com)
- **AI agent automation** — a phone/chat receptionist that books appointments, multi-step email/SMS follow-ups, an MCP integration, and a CRM.

## Contact

- Website — https://aporianous.com