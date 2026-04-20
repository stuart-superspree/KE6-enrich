# KE6 Enrich

A single-file HTML Progressive Web App prototype for King Edward VI College's enrichment programme.

## Run locally

Open `index.html` in any browser, or serve with a simple HTTP server:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Deploy

This repo auto-deploys to Railway on push to `main`. Railway serves `index.html` via Caddy.

## Files

- `index.html` — the entire app (HTML + CSS + JS in one file, ~237KB)
- `railway.json` — Railway deploy config
- `nixpacks.toml` — tells Railway's build system to install Caddy

Built by Superspree.
