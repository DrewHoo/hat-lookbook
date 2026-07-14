# The Big-Head Hat Lookbook

A curated, single-page hat lookbook for a **size-8 head** (~25″ / 63.5 cm). Every listing was
opened in a live browser, checked for stock, read from the store's own product data, and graded
against a big head. Three vibes:

- **Patagonia-outdoorsy** — including the honest finding that Patagonia's line mostly caps at ~24″,
  and the one high-crown trucker that actually fits, plus the Patagonia-adjacent brands (Tilley,
  Sunday Afternoons, Oddjob) that genuinely size to an 8.
- **Crimson Tide, minus the MAGA** — Alabama hats that don't read as a bright-red structured cap,
  and none from the '47 brand. Cream-crown throwback fitteds, heritage plaid, washed denim.
- **Irreverent** — built off the Oddjob Big Dad Hat, the real "Solvem Probler" pun, and other dry
  embroidered graphics, with a "buy it Blank + add your own joke" bridge for guaranteed fit.

## The fit lens

Each hat is tagged **Fits your 8** (true size 8 / big-head sizing), **Opens to it** (an adjustable
that reaches ~25″), or **Measure first** (tops out right around the limit). Tap the chips to filter.

## Tech

One self-contained `index.html` — inline CSS/JS, data as a JS array, product images hot-linked from
source CDNs (Patagonia's non-hotlinkable images are committed under `img/`). No build step. Deployed
to GitHub Pages via `.github/workflows/deploy.yml` (static upload of the repo root).

Prices and stock were verified **13 July 2026** and drift over time — confirm at checkout, and
select size 8 (or XL) before paying. Non-commercial; all links are canonical product pages with no
affiliate wrappers or trackers.
