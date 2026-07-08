<div align="center">

# Aurelius Dynamic Solutions

**Code shaping the world — one line at a time.**

The official landing site for Aurelius Dynamic Solutions LLC — a single, self-contained web experience with zero runtime dependencies.

[aureliusdynamic.com](https://aureliusdynamic.com) · [Contact](mailto:build@aureliusdynamic.com)

</div>

---

## Overview

This repository contains the production source for the Aurelius Dynamic Solutions marketing site. The entire experience — markup, styling, scripts, and fonts — is delivered from a single [`index.html`](index.html) file. There is no build step, no framework, and no external runtime footprint.

## Highlights

- **Single-file architecture.** The complete site is one self-contained `index.html`; every style, script, and font is inlined. No bundler, no dependencies, no install.
- **Privacy by design.** No external requests at runtime, no analytics, no cookies, and no backend. The contact form opens a pre-addressed email draft to `build@aureliusdynamic.com` — the site itself collects and transmits nothing.
- **Fully responsive.** Layouts, typography, and interactions adapt from mobile through ultrawide displays.
- **Interactive by default.** Features a live hero console (try `help` or `solve <your problem>`), a simulated three-engine pipeline demo, scrollspy navigation, animated counters, and an engagement-brief form.

## Getting Started

The site is fully static and requires no tooling.

```bash
# Clone the repository
git clone https://github.com/<your-org>/AureliusDynamicSolutions.git
cd AureliusDynamicSolutions
```

Open `index.html` in any modern browser — that is the entire stack. For a local server that mirrors production paths, you may optionally run:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is deployed via **GitHub Pages** from the repository root.

1. **Pages:** Settings → Pages → Deploy from branch (`master`, root).
2. **Custom domain:** `aureliusdynamic.com` (configured in [`CNAME`](CNAME)) with **Enforce HTTPS** enabled.
3. **DNS** (at your registrar):
   - Apex `A` records → GitHub Pages IP addresses
   - `www` `CNAME` → `<your-github-user>.github.io`

## Project Status

Actively maintained. Certain content — including team profiles and console/demo output — is illustrative and provided for demonstration purposes rather than as live data.

## License

Released under the [MIT License](LICENSE).

Copyright © 2026 Aurelius Dynamic Solutions LLC. The **Aurelius** name, wordmark, and hexagon mark are used for identification and demonstration; no trademark rights are granted.

---

<div align="center">

*Solve · Validate · Ship · Repeat*

</div>
