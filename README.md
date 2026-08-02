# apps-docs

Legal, privacy and support pages for apps published by [Sébastien Allamand](https://github.com/allamand).

Served via GitHub Pages at **https://apps.allamand.com**.

## Structure

```
/                  → Jekyll site root
CNAME              → apps.allamand.com
_config.yml        → Jekyll config
index.md           → Landing (app portfolio)
pocketreader/      → PocketReader (privacy, terms, support)
funearner/         → FunEarner (privacy, terms, support)
shared/            → Reusable snippets (empty for now)
```

## Adding a new app

1. Create `newapp/` at the root.
2. Add `privacy.md`, `terms.md`, `support.md`.
3. Link them from `index.md`.
4. Commit + push — GitHub Pages redeploys automatically.

## DNS

`apps.allamand.com` is a CNAME to `allamand.github.io`.
The `CNAME` file at the repo root tells GitHub Pages to serve this domain.
