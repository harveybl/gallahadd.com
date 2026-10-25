# gallahadd.com — repository index

Plain-markdown orientation for humans and coding agents. **This repository is PUBLIC and its content is published as a website**: keep this file free of anything private. Based on `main` at `a3e7f2a` (2026-10-21). `README.md` is authoritative.

Caution: the repo root is the site's output directory, so a `docs/index.md` merged into `main` would also be served from the site at `/docs/index.md`. It contains nothing sensitive, but consider whether you want it published.

## Purpose
Company website for Gallahadd Software LLC: static HTML, no build step. Hosts the homepage, per-app product/support pages, and the legal pages (privacy policies and terms) used by the apps (AI Todo Plus, SAFE Budget, Mobile Comfy Creator).

## Structure
| Path | What |
|---|---|
| `index.html`, `404.html`, `_redirects` | Homepage, not-found page, Cloudflare Pages redirects |
| `ai-todo-plus/` | AI Todo Plus product page and launch post |
| `legal/` | Legal pages (including archived earlier versions) |
| `privacy-ai-todo-plus.html`, `terms-ai-todo-plus.html`, `support-ai-todo-plus.html` | AI Todo Plus privacy, terms, support |
| `privacy-safebudget.html`, `terms-safebudget.html`, `support-safebudget.html` | SAFE Budget privacy, terms, support |

## Build and test
None: *unknown* beyond "Build command: none. Output directory: `/`" (README). No test suite or CI workflow in the repo.

## CI/CD (from `README.md`)
"Deployed by Cloudflare Pages from this repository: every push to `main` publishes to https://gallahadd.com." Pushes to `main` are therefore production deploys; use a branch (such as `docs/repo-index`) for anything unreviewed. Note: app releases that change legal copy deploy these pages (see the AI Todo Plus repo's `docs/RELEASING.md`).

## Recent notable changes (git log)
- 2026-10-21: AI Todo Plus 2.0 launch: product page, launch post, homepage card.
- 2026-10-19/20: AI Todo Plus privacy 4.0 and terms 2.0 for app 2.0; effective October 20, 2026; earlier privacy 3.2 and terms 1.1 archived for pre-2.0 versions.
- 2026-09: privacy updates for Calendar Sync, the AI Todo Plus AI service, and meal photos; homepage telemetry wording changed.
