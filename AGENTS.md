# AGENTS.md

DoJo is currently a nearly empty repository: there is no application code, build, or test setup yet.

## Where things are

- `README.md` — project title only (`# DoJo`).
- `.github/workflows/formic-agent.yml` — the only workflow. It runs the Formic coding agent on `workflow_dispatch` and pushes work to a `formic-staging/` branch. Installed and replaced by Formic; don't edit by hand.
- `AGENTS.md` — this file. `CLAUDE.md` just imports it (`@AGENTS.md`).

## Conventions

- No build, lint, or test commands exist yet. When you add some, list them here.
- When you add a main directory (e.g. `src/`, `tests/`), add it here with one representative file or function.
