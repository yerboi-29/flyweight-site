# Flyweight Aerospace — Marketing Site

Single-page public marketing site for **Flyweight Aerospace**, a heavy-lift Lighter-Than-Air (LTA) airship logistics venture (remote mine resupply + autonomous aerial survey).

## Stack & deploy
- One self-contained file: `index.html` (inline `<style>` and vanilla JS; Google Fonts: Inter + IBM Plex Mono). No build step.
- Repo: `github.com/yerboi-29/flyweight-site`. Hosted on **Vercel**, auto-deploys on push to **`master`**. Work directly on master.
- `assets/` holds the images (PNG) and SVGs referenced by the page.

## Voice / copy rules
- **No em dashes (—).** Brand voice. Use commas, colons, parentheses, or split sentences. En dashes in numeric ranges (e.g. 2,000–3,000 ft) are fine. A quick search for `—` should return nothing.
- Industrial, understated, confident; plain units. Hedge concept-stage claims once, not repeatedly per spec.

## Narrative structure (crawl / walk / run)
The page is built around a three-stage strategy. Keep it consistent everywhere it appears: the hero eyebrow, the stats band, the roadmap cards, the section labels ("Stage 0X · …"), the modal tags, and the "Where we are" list.
- **Stage 01 · Crawl** — compliant LTA test platforms. *Current stage* (the single highlighted roadmap card with the "We are here" badge).
- **Stage 02 · Walk** — 300 kg-class autonomous survey / remote-sensing airship. *First revenue.* The use-case gallery and its modals (mineral exploration, wildfire & disaster, infrastructure) live in this section.
- **Stage 03 · Run** — 50-tonne no-runway heavy-lift cargo for remote mine resupply. *The destination.*

## Source of truth
Research, data, and claims come from the sibling **`../LTA_vault`** wiki (an Obsidian-style knowledge base with its own agent schema in `LTA_vault/CLAUDE.md`). Cross-check numbers (cost/tonne, ice-road economics, payload, −40 °C buoyancy) against the wiki before changing them.

## Cautions
- **Team naming:** only James DiCorcia is a confirmed founder/CEO. Josh Cole and Nathan Longbotham are modeled/unconfirmed co-founders per the wiki; the Team section is intentionally anonymized. Do not add names without explicit confirmation.
- **Public page:** no fundraising specifics (round size, SAFE terms, named anchor investors). The footer carries "Not an offer of securities."
- Some `assets/` images may be unused after image swaps (e.g. `arctic_mining_site_with_airship.png`); confirm before deleting.
