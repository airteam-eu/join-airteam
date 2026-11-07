# Challenge 04: One promotion, two languages, one agent

**Pick 02, 03 or 04.** About 90 minutes.

## Context

We run four promotions a year. Each one needs the same pack: offer rules, e-mails, ads and posts, written natively in seven languages (cs, en, de, pl, fr, it, es), plus a plan for who gets the e-mail and who does not. An AI agent drafts the pack. A person writes the brief, checks the output and fixes the brief when the agent gets something wrong.

We want to see how you brief an agent and how you check it, not how fast you can paste a chatbot answer.

## The promotion (hypothetical, not a real offer)

- **"Spring days"**, 10 days, **−15 % on PilotStyle pilot gear**.
- Product set: the [PilotStyle collection](https://shop.airteam.eu/collections/brand-pilotstyle) on our shop. Pick 3 products to feature. Use the prices you see.

## Task

1. **Write the agent brief** (`pipeline/`): a skill file or prompt that takes *promotion name, dates, discount, product set* and returns a publish pack. Put the rules and a QA checklist inside it, so the next promotion needs only new inputs.
2. **Run it** with any AI tool and keep the first output as it came out. Then fix it into the final pack (`output/`):
   - **Offer rules:** what is in and out, whether it stacks with other codes, what happens to customers who have their own B2B prices.
   - **One e-mail** in English and in **one more of our languages you can judge**: subject of at most 50 characters, a preheader, a body of at most 150 words. Written natively in each language, not translated.
   - **Two social posts** (Facebook/Instagram), one per language.
   - **Google Ads:** 5 headlines of at most 30 characters and 2 descriptions of at most 90 characters.
   - **Send plan:** who gets the e-mail, who does not (a customer who bought yesterday, B2B accounts, people who got an e-mail from us two days ago), and at most 2 e-mails per person for the whole promotion.
3. **QA notes** (`output/`): what the first output got wrong and the rule you added to the brief so it does not happen again.

## Rules the pack must follow

- **EU price rule (Omnibus):** any "was" price you show is the lowest price of the previous 30 days. If you cannot know it from the live page, do not show a "was" price; say so in the QA notes.
- No fake urgency: a 10-day promotion is not "today only".
- No invented prices, stock or delivery promises. No competitor names.

## What to submit

`pipeline/`: the brief or skill and any prompts.
`output/`: the first raw output, the final pack, the send plan and the QA notes.

## Video (with challenge 01)

Show one live run of your brief and one correction you made to it. Say why the e-mail goes to the people in your send plan and not to the rest.

## What fails this challenge

- Copy in the second language that reads like a translation.
- A strike-through price with nothing behind it.
- Three or more e-mails per person, or one send to everyone with an address.
- Agent output passed on without a single check.
- A discount that also lands on B2B accounts with their own prices.
