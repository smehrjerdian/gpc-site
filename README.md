# Guerrilla Product Consulting

Public marketing site for Guerrilla Product Consulting.

## Live

- Custom domain: https://guerrillaproduct.xyz/
- Repo: https://github.com/smehrjerdian/gpc-site

## Stack

Static single-page site (`index.html`) with embedded brand assets. Served from the `main` branch root via GitHub Pages.

## DNS (Porkbun)

Apex `A` records for `guerrillaproduct.xyz`:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Optional apex `AAAA`:

- 2606:50c0:8000::153
- 2606:50c0:8001::153
- 2606:50c0:8002::153
- 2606:50c0:8003::153

`www` `CNAME` → `smehrjerdian.github.io`

After DNS propagates, GitHub Pages will issue HTTPS for the custom domain.
