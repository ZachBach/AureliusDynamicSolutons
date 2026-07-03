# Aurelius Dynamic Solutions — aureliusdynamic.com

> Code shaping the world — one line of code at a time.

The production landing site for **Aurelius Dynamic Solutions**, open-sourced as a **test concept**. Fork it, study it, build on it.

## What it is

- **One file.** The entire site is a single self-contained `index.html` — every style, script, and font inlined. No build step, no dependencies, no framework install.
- **Zero surface area.** No external requests at runtime, no analytics, no cookies, no backend. The contact form opens a pre-addressed email draft to `build@aureliusdynamic.com`; the site itself collects and transmits nothing.
- **Interactive.** A live hero console (try `help` or `solve <your problem>`), a simulated three-engine pipeline demo, scrollspy navigation, animated counters, and a mock engagement-brief form.

## Run it

Open `index.html` in a browser. That's the whole stack.

## Deploy (GitHub Pages)

1. Settings → Pages → Deploy from branch (`main`, root).
2. Custom domain: `aureliusdynamic.com` (kept in `CNAME`) → Enforce HTTPS.
3. DNS at your registrar:
   - Apex `A` records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `www` `CNAME` → `<your-github-user>.github.io`

## Status

Test concept — expect sharp edges. Team profiles are placeholders, and all console/demo output is illustrative, not real telemetry.

## License

Released under the [MIT License](LICENSE).

The **Aurelius** name, wordmark, and hexagon mark appear for demonstration; no trademark rights are granted.

---

*Solve · Validate · Ship · Repeat*
