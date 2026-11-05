# Thameen — Landing Page

A bilingual (English / العربية) marketing site for **Thameen for Investment & Real Estate
Development** — ثمين للاستثمار والتطوير العقاري — based in Riyadh.

- **Static site, no build step.** Just `index.html` + `assets/`.
- Scroll animations via **GSAP** (loaded from CDN at runtime).
- EN ⇄ AR language toggle with full RTL support.

## Deploy

### 1 — GitHub (account: `aimanenmgrz1-prog`, repo: `ThameenWebsite`)
Create an empty repo named `ThameenWebsite` at <https://github.com/new> (no README/licence),
then from this folder:

```bash
git push -u origin main
```

The `origin` remote is already set to `https://github.com/aimanenmgrz1-prog/ThameenWebsite.git`.

### 2 — Vercel (account: `aimanenmgrz1-prog`)
1. Go to <https://vercel.com/new> while signed in as **aimanenmgrz1-prog**.
2. **Import** the `aimanenmgrz1-prog/ThameenWebsite` repo.
3. Framework Preset: **Other** (static — no build command, no output dir).
4. **Deploy.** You'll get a URL like `thameen-website.vercel.app`.

Every future `git push` to `main` auto-deploys.

## Before going live
The contact details, address and licence numbers are **placeholders**. Replace them with verified
values before publishing — in `index.html` search for:

- `+966 11 000 2746` and `966110002746` (phone / WhatsApp)
- `hello@thameen.example` (email)
- `Al Olaya St … Riyadh 12213` (address, EN + AR)
- `Add CR number`, `Add REGA licence no.`, `Add VAT number` (compliance card)

Real-estate advertising in Saudi Arabia requires a valid **REGA** licence. The architectural
images are illustrative concepts, not photographs of completed projects.
