# Valerio Zanzarelli

**AI & full-stack engineer — LLM agents in production · Node.js · Flutter · Python**
CTO & sole engineer at [InkConscious](https://inkconscius.eu) · Fuerteventura, Spain (UTC+0) · open to remote work

---

### What I build

In five months of 2026 I built, alone, a 13-repository production ecosystem — **~5,000 commits, 4,300+ automated tests, 4 apps on 5 platforms**.

- **AI booking agent (production).** Runs complete WhatsApp/Instagram conversations for tattoo studios: intake, GPT-vision reading of reference images into a self-calibrating pricing engine, PDF quotes, calendar booking with atomic slot locks, Stripe deposits, one-tap human handoff. Claude/GPT model matrix with per-model cost billing, anti-loop caps, evals and end-to-end conversation replays in CI, GDPR controls.
- **Ops Central — multi-agent engineering system.** A Claude "foreman" routes investigator / implementer / tester / reviewer workers across models by cost and risk ($0.01–1 per run), with GPT fallback, diff/apply/rollback and an audit log. Plus an MCP tool server (Gmail, Calendar) and a Playwright browser microservice with human handoff.
- **Backend:** Node.js/Fastify (~317K LOC, 120 routes, 2,850 tests), PostgreSQL/SQLite, Redis + BullMQ, Stripe, S3, WebSockets; GitHub Actions + Codemagic multi-OS builds, OTA distribution.
- **Apps:** Flutter studio app (161K LOC, iOS · Android · macOS · Windows · Web, offline-first sync, AES-256-GCM encrypted backups, 6 languages) and a Swift/Metal GPU drawing engine.

The InkConscious code is private (it's a commercial product) — **happy to give a live walkthrough of the code, the agent and its evals.**

### Public projects

| Repo | What it is |
|---|---|
| [mind-runtime](https://github.com/valeriozanzarelli-debug/mind-runtime) | CEREBRUM — brain-inspired runtime in Python/PyTorch (CUDA): spiking neural field, dopamine-gated STDP, predictive coding, webcam vision, local HTTP API |
| [particle-sim](https://github.com/valeriozanzarelli-debug/particle-sim) | Particle simulation in Rust |
| [ELEMENTI](https://github.com/valeriozanzarelli-debug/ELEMENTI) | Applied statistics: Markov/AR models, permutation-null tests and Monte Carlo backtests on 156 years of draw data |

### Stack

`Claude API` `OpenAI Agents SDK` `MCP` `multi-agent orchestration` `evals & guardrails` · `Node.js` `Fastify` `PostgreSQL` `Redis` `Stripe` · `Flutter` `Dart` `Swift/Metal` · `Python` `PyTorch` · `GitHub Actions` `Docker` `Playwright` `Linux`

Before software: 5 years of industrial maintenance, PLC programming and machine wiring (Iveco, AGR Filtri, Emmecitecnica).

**Languages:** Italian (native) · Spanish (fluent) · English (professional)
**Contact:** valerio.zanzarelli@gmail.com
