# Challenge 02: HubSpot — skóre, kategorie, co dál

**Typ:** systém · **Čas:** cca 45 minut

## Kontext

Poptávka z webu nebo PPC spadne do CRM. Obchod nemá čas hádat, jestli je to pilot, škola, nebo MRO. Když se obchod **neuzavře**, nesmí vzniknout černá díra — potřebujeme další krok podle typu zákazníka.

Ve firmě platí čisté předání: obchodník má vidět kontext, skóre a doporučený další krok. Nestavíte živý HubSpot portál.

## Úkol

Pracujte s **8 fiktivními leady** v [fixtures/leads.md](./fixtures/leads.md).

Pro **každý** lead uveďte:

- kategorii (např. GA / škola / partner-MRO / nejasný / mimo scope)
- skóre 0–100 a **proč**
- akci teď: **předat obchod** / **hold** / **nurture** / **předat jinam**

Pak navrhněte **2 cesty** (ne deset e-mailů):

- **A — GA / koncový:** poptávka byla, obchod se neuzavřel
- **B — partner / MRO:** totéž

Každá cesta: trigger, max **3 kroky**, co nabídnout jako další (produkt vs. servis podle veřejného portfolia na [airteam.eu](https://www.airteam.eu)), kdy eskalovat na člověka.

## Deliverables

Do `output/`:

| Soubor | Obsah |
|--------|--------|
| `scoring.md` | Tabulka všech 8 leadů |
| `journeys.md` | Cesta A a cesta B |
| `sales-handoff.md` | Co přesně uvidí obchodník (kontext, skóre, doporučený krok) |

Pravidla pište tak, aby šla později zapsat do HubSpotu (listy, skóre, workflow) — ne jako esej.

## Co hledáme

Systém, který obchod unese. Ne „pošleme newsletter“.
