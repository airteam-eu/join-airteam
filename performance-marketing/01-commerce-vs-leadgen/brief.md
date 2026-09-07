# Challenge 01: Shop purchase vs certified upgrade

**Required.** About 90 minutes.

## Context

AIR TEAM sells boxed avionics and headsets on [airteam.eu](https://www.airteam.eu). AIR TEAM Service installs and certifies upgrades in Kunovice ([upgrade & installation](https://airteam.services/professional-avionics-upgrade-and-installation/)). Same brand, two P&Ls.

A Performance Max campaign that treats a GTN Xi install enquiry as a shop checkout will burn budget and annoy the crew. A Search campaign that sells a Bose A30 like a QuietComfort will rank for the wrong people.

## Use these three URLs (do not swap them)

1. [Bose A30 aviation headset (GA plug)](https://www.airteam.eu/p/bose-a30-headset-anr) — product page, add to cart.
2. [Garmin GDU 116B AXIS 11.6" display](https://www.airteam.eu/p/gdu-116b) — unit for sale, and the page also offers installation. That split is the point.
3. [Avionics upgrades & installations](https://airteam.services/professional-avionics-upgrade-and-installation/) — quote / “request now”, Part-145 work.

Read the live pages. Use the price you see. Do not invent list prices, stock figures, or STC status.

Group websites (e-shop, service, intel, Bose repair): see the [root README](../../README.md#public-group-websites).

## Task

Build a small, reusable procedure (prompts, a script, or a checklist you would run again next month) that takes a URL like the three above and outputs a campaign call.

For **each URL** fill:

| Field | What we want |
|-------|----------------|
| Program | Shop purchase **or** upgrade enquiry. One label. If the page is mixed, say so and pick the **primary** conversion anyway. |
| KPI | ROAS / purchase value **or** CPL / qualified enquiry. Not both in one campaign. |
| Primary conversion in Google Ads | Purchase **or** form submit (or a named equivalent). |
| Campaign type | Search and/or PMax. If PMax, say what must **not** be the goal. |
| RSA or asset notes | 3–5 headlines or PMax text themes. Character limits if Search. |
| Negatives | At least a handful, including the obvious off-audience terms. |

Also write **four lines** on merchandising: if we feature this SKU next week, we change feed labels / listing groups. We do not spin up a second PMax to “push” it.

## What to submit

`pipeline/` — the prompt, skill, or script.  
`output/` — the table for all three URLs (markdown or sheet). Raw is fine.

## Shape of a passing output

```
URL 1 — Bose A30
  Program: shop purchase
  KPI: purchase ROAS
  Primary conversion: Purchase
  Type: PMax / Shopping + brand Search (your call, with a reason)
  Headlines: ...
  Negatives: bose qc, quietcomfort, gaming headset, ...

URL 2 — GDU 116B AXIS
  Program: [you decide; argue it]
  Primary conversion: [one]
  Note: unit-only checkout vs "request installation" must not share a goal

URL 3 — Upgrade landing
  Program: upgrade enquiry
  KPI: CPL on a form
  Primary conversion: form submit — not Purchase
  Headlines: upgrade / certified install / Part-145 — not "buy a glass cockpit"
```

## Video (with challenge 02 or 03)

Walk the three URLs. Say out loud which conversion you would set as primary and why. If you used a prompt, paste an input and show the output live.

## What fails this challenge

- One campaign, one report, shop ROAS and lead CPL mixed.
- “Buy” / “sale” language on the install page.
- Bose treated as consumer audio.
- A new PMax “just for the push.”
- Skipping URL 2 because it is awkward.
