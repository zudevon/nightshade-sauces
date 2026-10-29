# Nightshade Sauces — Website

One-page site for **Nightshade Sauces** (Est. 2024, Hutto, Texas) — small-batch fermented hot sauce, sold as numbered experiments at markets and festivals.

**Live at:** https://zudevon.github.io/nightshade-sauces/

## What's here

- `index.html` — the whole site (HTML + CSS + JS in one file, no build step needed)
- `assets/` — optimized photos from the booth (bottles, badge/sticker, awards, trophy)

## How to make changes

Everything is plain HTML — open `index.html` in any editor:

| What | Where |
|---|---|
| Flavors, descriptions, heat dots | `<!-- LINEUP -->` section |
| Story text | `<!-- STORY -->` section |
| Contact / social links | Search for `OWNER EDIT` in `index.html` |
| Prices / an order button | Add a button in the "Find us" section |

To change a photo, just replace the file in `assets/` (keep the same name).

## Deploying updates

1. Edit, then commit: `git add -A && git commit -m "Update flavors"`
2. Push: `git push`
3. GitHub Pages serves the new version automatically within ~a minute.

The site is deployed from the `main` branch via GitHub Pages (Settings → Pages).

---
*Co-built from the booth photos with Claude Code.*