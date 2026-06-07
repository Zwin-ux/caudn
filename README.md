# Caidoon / AI Encounters Engine

Workspace for an AI encounters engine. The active implementation lives in `Caidoon/`.

## What is here

- `Caidoon/packages/`, `services/`, and `adapters/` - core workspace areas.
- `Caidoon/package.json` - pnpm workspace scripts for build, test, lint, and dev.
- `Caidoon/docker-compose.yml` and `docker/` - local service/deployment support.
- `Caidoon/README.md`, `TEST_RESULTS.md`, `AI-TEST-RESULTS.md`, and `COMPLETION_REPORT.md` - implementation and verification notes.

## Run locally

```bash
cd Caidoon
pnpm install
pnpm test
pnpm dev
```

## Status

Prototype workspace with test reports and handoff notes. Any AI calls or service-backed flows require environment values from `.env.example` before they can be exercised honestly.
