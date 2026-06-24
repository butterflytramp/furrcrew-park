# FurrCrew Park 🐾

A simple, cozy web toy: draw your own pet, name it, and let it loose in a shared park where it wanders, sits, sniffs, and greets the rest of the crew.

Built as a single self-contained `index.html` — no build step, no dependencies.

## Run locally
Just open `index.html` in any browser, or serve the folder:
```bash
npx serve .
```

## Deploy
It's a static site, so any static host works.

**Vercel** — import this repo at [vercel.com](https://vercel.com), no build settings needed.

**GitHub Pages** — Settings → Pages → Source: `main` / root.

## Notes
- Pets are saved per-device in `localStorage`. Making the park truly shared across all visitors needs a small backend (e.g. Supabase or a KV store).
- Colors use the FurrCrew brand palette: deep green, cream, brown, navy.

---
Part of [FurrCrew](https://furrcrew.in) — the connected operating backbone for pet care.
