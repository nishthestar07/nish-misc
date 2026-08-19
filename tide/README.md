# Tide

Weight tracking with lifting programs and built-in form guidance. One self-contained HTML file —
no build step, no dependencies.

Live: https://nishthestar07.github.io/nish-misc/tide/

## Publishing
1. This folder lives at `tide/` in `nishthestar07/nish-misc` (branch `main`).
2. Repo → Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
3. Give it a minute, then open the URL above. On iPhone: Share → Add to Home Screen.

## Status
Prototype. All data is in-memory — it resets on reload, and there are no accounts.
See `../design_handoff_tide_app/backend/` for the Postgres schema, API spec and the Supabase
path to making it persist while staying hosted here.
