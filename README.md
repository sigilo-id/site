# sigilo.id

The Sigilo marketing site.

Deployed via Cloudflare Pages from this repo's `main` branch.
Every commit to `main` triggers an automatic redeploy.

## Local preview

This is a single static HTML file with no build step. Open it directly,
or run any static server:

```sh
python3 -m http.server 8080
# then open http://localhost:8080
```

## Structure

- `index.html` — the entire landing page (intentionally a single file)
- `_headers` — Cloudflare Pages security headers
- `_redirects` — Cloudflare Pages redirect rules (placeholders for now)

## Brand

Sigilo (n., Sp./Pt.) — secrecy; discretion; the practice of keeping a
matter unspoken. From Latin *sigillum*, "a small seal."
