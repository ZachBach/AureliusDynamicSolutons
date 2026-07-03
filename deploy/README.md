# aureliusdynamic.com

Production site for **Aurelius Dynamic Solutions** — a single self-contained `index.html`. All styles, scripts, and fonts are inlined: no external requests at runtime, no analytics, no cookies, no build step.

## Deploy (GitHub Pages)

1. Settings → Pages → Deploy from branch (`main`, root).
2. Custom domain: `aureliusdynamic.com` (kept in `CNAME`) → Enforce HTTPS.
3. DNS at your registrar:
   - Apex `A` records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `www` `CNAME` → `<your-github-user>.github.io`

## Notes

- The contact form opens a pre-addressed email draft to `build@aureliusdynamic.com`. The site itself collects and transmits nothing.
- The three-engine widget and hero console are illustrative demos.

© MMXXVI Aurelius Dynamic Solutions LLC. Site content and brand assets: all rights reserved.
