# Challenge 03: Lead quality loop

**Optional — pick this or challenge 02.** About 90 minutes.

## Context

Paid traffic creates HubSpot contacts. Some should check out on the e-shop. Some should become a sales enquiry for an MRO upgrade or airline / DOA work. Some are support tickets. Some are junk.

Sales should not hunt every form fill. Marketing should not drip on a pile of unqualified contacts “because we have them.”

You do not get our HubSpot portal. Use the synthetic rows in [`sample-leads.md`](./sample-leads.md) (CSV copy: [`sample-leads.csv`](./sample-leads.csv)). Names and firms are fake.

## Task

Build a small ruleset you could paste into a HubSpot workflow discussion (if/then, not a novel). Then run it on the sample file.

For each row: route, score band (hot / warm / ignore), owner **role** (not a person’s name), and one next step.

Roles you may use:

- E-shop / no sales ticket
- MRO upgrade sales (GA, business jets, Kunovice install)
- Airline / DOA sales
- Customer support (ticket, not a deal)
- Ignore / do not nurture

Also write a short note (half a page max) for the case “sales did not close”: what marketing is allowed to send, and what is spam. Do not design a five-email sequence. Do not “reactivate” ignore-band contacts.

## What to submit

`system/` — the rules (prompt, script, or bullet if/then).  
`output/` — the scored table for every sample row.

## Video

Walk two rows that should **not** go to sales, and one that should. Explain how a bad Google campaign would have created the junk row.

## What fails this challenge

- Everything becomes a sales lead.
- A nurture idea aimed at the old unqualified pile.
- Mixing shop orders into an MRO pipeline.
- Real people’s names, or invented HubSpot internal IDs from a leaked screenshot.
