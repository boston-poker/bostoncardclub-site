# bostoncardclub.com minimal policy site

This folder contains a minimal static site used for Google OAuth app verification:

- `index.html` (homepage)
- `privacy.html`
- `terms.html`

## Deploy plan (GitHub Pages)

1. Create repo under `boston-poker` org/user (e.g. `bostoncardclub-site`).
2. Commit + push these files.
3. Enable GitHub Pages (Settings → Pages → Deploy from branch → main / root).
4. Set Custom Domain to `bostoncardclub.com`.

## DNS (Namecheap)

A records for `@`:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

CNAME for `www`:
- `www` → `boston-poker.github.io`

Also add the TXT record Google Search Console gives you for domain verification.
