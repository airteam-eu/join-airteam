# Challenge 02: Measurement spec

**Optional — pick this or challenge 03.** About 90 minutes.

## Context

Shop traffic lands on [airteam.eu](https://www.airteam.eu). Upgrade traffic lands on [airteam.services](https://airteam.services/professional-avionics-upgrade-and-installation/) (same operation as [service.airteam.eu](https://service.airteam.eu/en/)). If Google Ads only has a Purchase conversion, Search for Kunovice installs will optimise for headset checkouts.

You do not get GTM access. Spec it as if you were handing the sheet to whoever has the container.

## Task

Write a measurement spec for **two** journeys:

1. Customer buys a Bose A30 (or any in-stock headset) on the e-shop.
2. Aircraft owner submits an upgrade request on the Service site.

Build a repeatable way to produce the spec (prompt or template). Then run it once.

The output **must** include this table, filled in. Extra columns are fine; missing rows are not.

| Step | Shop purchase | Upgrade enquiry |
|------|----------------|-----------------|
| Page / domain | | |
| User event (what fires) | | |
| Google Ads conversion action (name + type) | | |
| Which campaign may use it as **primary** | | |
| GA4 event | | |
| UTM example (`source` / `medium` / `campaign` / `content`) | | |
| HubSpot: what object, what property, who should own it | | |
| What must **not** be primary for this journey | | |

UTM naming should be boring and stable. Inventing a twelve-level taxonomy is worse than four consistent parameters.

State what you would check if the corporate site and the service site do not share a tag: duplicate conversions, unattributed forms, Ads learning on the wrong action.

## What to submit

`pipeline/` — prompt or template.  
`output/` — the filled table plus a short “if tags are split” note.

## Video

Show the table. Pick one journey and talk through Ads → GA4 → HubSpot. No need to log into anyone’s account.

## What fails this challenge

- Upgrade Search using Purchase as the campaign-level goal.
- UTM that cannot tell shop from install.
- HubSpot treated as a dumping ground with no owner role.
- A tracking essay with no table.
