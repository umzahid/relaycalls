# Relay — AI receptionist for UK trades

Static marketing site for Relay.

- **Live:** <https://umzahid.github.io/relaycalls/>
- **Privacy:** <https://umzahid.github.io/relaycalls/privacy.html>

## Files

- `index.html` — landing page (inline CSS/JS, no external fonts or analytics)
- `privacy.html` — privacy notice
- `README.md` — this file

## Deploy

Push to `main`; GitHub Pages rebuilds automatically.

## Custom domain

When `relaycalls.co.uk` is registered:

1. Add `relaycalls.co.uk` under Settings → Pages → Custom domain.
2. DNS: apex A records to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`; `www` CNAME to `umzahid.github.io`.
3. Enable HTTPS.
4. Update canonical/`og:url` in `index.html` from `https://umzahid.github.io/relaycalls/` to `https://relaycalls.co.uk/`.
