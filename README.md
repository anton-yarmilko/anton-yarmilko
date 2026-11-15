# Hi, I'm Anton 👋

**Customer Support Lead · AI-first support automation · Python**

I lead support teams and build the automation myself.

📁 **Personal page:** [anton-yarmilko.github.io](https://anton-yarmilko.github.io)

4+ years in 24/7 technical support for US restaurant clients (NCR Voyix Aloha POS), including a full year as Team Lead of a 9+ agent shift: schedules, onboarding and training, quality review, SLA and CSAT tracking.

- 🤖 I built and run an internal AI knowledge system (LLM + RAG over a custom Aloha/NCR knowledge base, with a feedback loop) used by ~30 colleagues every day
- 🧭 I design AI-first support: the AI handles the repetitive questions, people handle what needs judgment, and every answer is reviewed before it ships
- 🔧 I write PowerShell automation used in daily operations: remote diagnostics, configuration validation, deployment and firewall/API setup
- 🎲 I build BÜRO, an iOS/Android app for a bar in Vinnytsia I co-own (React Native, Supabase, 331 tests)
- 🐧 I run a self-hosted Linux server for AI and automation experiments

8,000+ support interactions · English B2 · open to remote roles in support leadership, AI support automation and Python/backend.

## Selected projects

### flight-claims-support-agent — AI first-line support for claims

A Claude skill for a flight-compensation claims service with a deterministic safety layer: Python triage decides whether the AI may answer or must hand off (money, legal threats, GDPR, upset customers, weak matches), and an EU261 eligibility check gives the amount. Evals of real-style messages and 26 tests run in CI.

Python · Claude skills · pytest · GitHub Actions

[Source & docs](https://github.com/anton-yarmilko/flight-claims-support-agent)

### one-system — Codex, Claude Code and Hermes as one team

My daily multi-agent setup: a shared skill registry symlinked into every agent, a task bus, agent-to-agent delegation, cost-aware routing across quotas and free models, and an ordered review pipeline (architect → coder ↔ reviewer → tester → security).

Bash · Python · Node.js · Claude Code · Codex · OpenRouter

[Source](https://github.com/anton-yarmilko/one-system)

### BÜRO — mobile app for a bar I co-own

iOS, Android and web app for a bar in Vinnytsia, styled as a friendly parody of bureaucracy: board games, tournaments, darts scoring, a "find company" board and a certificate of the day. Built solo with AI coding agents: ~15,600 lines of TypeScript, 331 tests, Supabase with row-level security, Poster POS integration.

Expo · React Native · TypeScript · Supabase · Playwright

[Live demo](https://anton-yarmilko.github.io/buro-app/) · [Showcase](https://github.com/anton-yarmilko/buro-app)

### bureau-api — Tournaments & Elo ratings

A FastAPI service for the Bureau bar app: knockout and round-robin brackets with seeding by rating, per-game Elo ratings and a leaderboard. Concurrent results are applied exactly once via row locks; the test suite runs on SQLite and PostgreSQL in CI, together with Alembic migration checks and a Docker build.

Python · FastAPI · SQLAlchemy 2 · Alembic · PostgreSQL · pytest · Docker · GitHub Actions

[Source & docs](https://github.com/anton-yarmilko/bureau-api)

### Aloha RAG Demo — Support Knowledge Base

A Python/Flask retrieval demo using synthetic NCR Aloha-style troubleshooting data only. It ranks Markdown knowledge-base sections with a lightweight TF-IDF-style retriever and returns the matching text with source metadata through `/ask`. The public demo runs locally without an LLM; it does not expose the internal workplace platform or proprietary content.

[Source & local setup](https://github.com/anton-yarmilko/aloha-rag-demo)

### NEXUS — Responsive Digital Studio Website

A non-commercial React/Vite implementation of a supplied Figma design, with responsive layouts, accessible navigation, reduced-motion support, contact validation, automated tests, and security headers. An independent portfolio implementation, not a commercial agency. Contact-message delivery from the new hosting origin has not yet been verified.

[Live demo](https://nexus-anton.pages.dev/) · [Source](https://github.com/anton-yarmilko/nexus-digital-solutions)

### Exyr — Landing Page Concept

An independent, non-commercial React/Vite implementation of a supplied Figma landing-page design. Includes responsive layouts, reduced-motion support, pricing interactions, email-inquiry preparation, and automated checks. Product screens and prices are illustrative; this is not a released remote-access service or a subscription offer.

[Live demo](https://exyr-anton.pages.dev/) · [Source](https://github.com/anton-yarmilko/exyr-landing-page)

## Contact

📫 taboopip@gmail.com · [LinkedIn](https://www.linkedin.com/in/anton-yarmilko/) · [Personal page](https://anton-yarmilko.github.io)
