# Guerrilla Product Consulting

Public marketing site for Guerrilla Product Consulting.

## Live

- https://sayeed.work/gpc-site/
- Canonical GitHub Pages path redirects there: https://smehrjerdian.github.io/gpc-site/

Repo: https://github.com/smehrjerdian/gpc-site

## Stack

Static single-page site (`index.html`) with embedded brand assets. Served from the `main` branch root via GitHub Pages.

Because the user site `smehrjerdian.github.io` uses the custom domain `sayeed.work`, project Pages for this account currently publish under `https://sayeed.work/<repo>/`.

## Custom domain on its own apex (later)

When you want a dedicated Porkbun domain (for example `yourdomain.com`) pointed only at this site:

1. Add a root `CNAME` file containing only that domain name.
2. In this repo Settings → Pages, set Custom domain and enable HTTPS once DNS verifies.
3. At Porkbun DNS:
   - Apex `A` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - Optional apex `AAAA` → `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`
   - `www` `CNAME` → `smehrjerdian.github.io`
