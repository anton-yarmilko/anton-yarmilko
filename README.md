# Hi, I'm Anton 👋

Python/backend developer with 4+ years in production technical support (NCR Voyix Aloha POS), including one year as Team Lead in a 24/7 environment.

- 🔧 I build support automation used daily: PowerShell remote diagnostics, configuration validation, deployment and firewall/API workflows
- 🤖 I develop and operate an internal AI-assisted knowledge platform (Flask + RAG over a custom Aloha/NCR knowledge base) used by ~30 people every day
- 🎲 I'm building a mobile app for «Bureau», a bar in Vinnytsia I co-own: games with online multiplayer, accounts and bills on Expo / React Native + Supabase, synced with Poster POS
- 🐧 I run a self-hosted Linux server for AI and automation experiments

## Selected projects

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

📫 taboopip@gmail.com · [LinkedIn](https://www.linkedin.com/in/anton-yarmilko/)
