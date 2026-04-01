# AION Broker Intelligence

Internal deal sourcing platform for **AION Succession Partners** — 375 UK M&A advisors and business brokers, searchable and filterable, built to drive systematic outreach for B2B vertical software acquisition mandates.

## Quick Start

**Locally:** Open `index.html` in any browser. Password: **AION2025**

**GitHub Pages (live URL):**
1. Create a new **private** GitHub repo (e.g. `aion-broker-intel`)
2. Push this folder:
```bash
git init && git add . && git commit -m "AION Broker Intel v6"
git remote add origin https://github.com/USERNAME/aion-broker-intel.git
git push -u origin main
```
3. Settings → Pages → Source: `main` branch, `/ (root)` → Save
4. Live in ~60 seconds at `https://USERNAME.github.io/aion-broker-intel/`

> **Note on OG preview image:** For WhatsApp to show the preview card, update the `og:image` meta tag in `index.html` to use the full absolute URL once you know your GitHub Pages domain:
> ```html
> <meta property="og:image" content="https://USERNAME.github.io/aion-broker-intel/og-image.png">
> ```

## Changing the Password

```bash
# Generate SHA-256 hash for your new password
echo -n "YourNewPassword" | sha256sum
```
Find `const PW_HASH = '...'` near the bottom of `index.html` and replace the hash.

## Folder Structure

```
aion-broker-intel/
├── index.html        ← entire app, self-contained (~527KB)
├── icon.png          ← 512×512 favicon / bookmark icon / Apple touch icon
├── favicon-32.png    ← 32×32 browser tab favicon
├── icon.svg          ← SVG source for the icon
├── og-image.png      ← 1200×630 WhatsApp / social share preview image
├── .gitignore
└── README.md
```

## What's Inside

- **375 firms** — iTABB, Axial, curated research, enriched via Companies House
- **B2B SaaS scoring** (0–100) surfaces tech-specialist advisors
- **EV range filters** — Sub-£2m / £2m–£10m / £10m–£50m / Over £50m
- **305 contact emails** with confidence badges
- **AI outreach drafting** — personalised cold emails as Wernher Pikali
- **CRM tracking** — pipeline status persisted in localStorage
- **People intelligence** — CH directors + scraped team pages merged

---
*Built by G2G Advisory · Private & Confidential*
