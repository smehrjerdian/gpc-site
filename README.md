# Guerrilla Product Consulting

Public marketing site for Guerrilla Product Consulting.

## Live

- GitHub Pages: https://smehrjerdian.github.io/gpc-site/

## Stack

Static single-page site (`index.html`) with embedded brand assets. Served from the `main` branch root via GitHub Pages.

## Custom domain (later)

1. Add a `CNAME` file at repo root with the bare domain (one line).
2. In GitHub repo Settings → Pages, set Custom domain and wait for DNS check + HTTPS.
3. At Porkbun DNS:
   - Apex: `A` records to GitHub Pages IPs `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - Optional `AAAA` to `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`
   - `www`: `CNAME` to `smehrjerdian.github.io`
