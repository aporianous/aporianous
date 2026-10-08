# Aporia Nous

**I build local-first AI — the language, the runtime, and the agents on top.**

## Flagship

- **Morpheus** — a small, sovereign programming language: its own lexer, parser,
  AST and interpreter, a `prophesy` (Monte Carlo) primitive, and self-modifying
  functions. **Open-core** — the language and tooling are open; the engine is
  private. → [repo](https://github.com/aporianous/morpheus) · [interactive tutorial](https://aporianous.github.io/morpheus/)
- **Perseus** — a **local-first AI runtime**. It runs on hardware
  you own, answers with a **confidence score you can check**, and **refuses
  when it doesn't know**. → [interactive demo](https://github.com/DrSinister31/perseus-demo) · [aporianous.com](https://aporianous.com)

## Also

- Agent memory & retrieval (deterministic, model-free)
- Data pipelines, backend APIs & Docker
- Automation, bots & MCP

## Selected work

**2026-06**
- **Dockerized community backend** — a Docker Compose stack: a FastAPI service (Steam OAuth, player tracking, teleport API), a Discord bot, SQLite with persistent volumes, an RCON bridge, health checks, and CI/CD auto-build to Docker Hub. → [Web-Link-Host-Isle](https://github.com/DrSinister31/Web-Link-Host-Isle)
- **Discord app legal pages** — Privacy Policy + Terms published as a single GitHub Pages document for a Discord app. → [Privacy-TOS](https://github.com/DrSinister31/Privacy-TOS)

**2026-07**
- **Proximity-voice installer + Discord verification** — a one-click installer that sets up and configures a Mumble voice server for a game community, pre-connects clients, and ties each user to their Discord account via a bot-issued 6-digit code. → [Sinister-s-Park-Mumble](https://github.com/DrSinister31/Sinister-s-Park-Mumble)

**2026-08**
- **Morpheus — language + toolchain** (see Flagship). Open-core language; the native engine is private.
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