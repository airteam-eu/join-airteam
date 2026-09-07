# Challenge 01: PPC — poptávka, ne levný klik

**Typ:** analytické · **Čas:** cca 45 minut

## Kontext

AIR TEAM v e-shopu a na webu přivádí poptávky na avioniku a vybavení kokpitu (Smart Supply). Stejné vyhledávací dotazy ale míří na **dva světy**:

- **GA / pilot** — často kratší rozhodování (headset, Garmin do malého stroje, e-shop)
- **Partner / MRO** — delší rozhodování, opakované nákupy, servis a díly do provozu

Obchod potřebuje vědět, koho dostal. Levný klik, který nikdo nevezme, je ztráta.

Část Search provozu je šum: spotřební Garmin (hodinky), nabídky práce u aerolinek, hračky / drony mimo náš sortiment. Viz [fixtures/noise-vs-intent.md](./fixtures/noise-vs-intent.md). Katalog: [airteam.eu](https://www.airteam.eu).

## Úkol

Navrhněte **Google Ads Search** tak, aby cílem byla **kvalifikovaná poptávka**, kterou obchod vezme — ne maximum konverzí za každou cenu.

1. **Struktura účtu** — kampaně a ad groups. Oddělte GA vs. partner tam, kde to dává smysl.
2. **Měření** — jaké konverze sledujete, příklady UTM (`source`, `medium`, `campaign`, `content`), co je „dobrý lead“.
3. **Šum** — co vyloučit (negativa, publika) a co posílit v prvním týdnu.
4. **30 dní** — jedna priorita a jak poznáte, že to zabírá. Bez vymyšleného ROAS; stačí logika a kill kritéria.

Ostrý Google Ads účet nestavíte. Žádné fiktivní rozpočty v Kč, které „vypadají firemně“.

## Deliverables

Do `output/`:

| Soubor | Obsah |
|--------|--------|
| `account-structure.md` | Strom kampaní / ad groups |
| `measurement.md` | Konverze + UTM příklady |
| `30-day-priority.md` | Jedna sázka + kdy to vypnout |

## Co hledáme

Kvalita poptávky a předání obchodu. Ne „snížíme CPC“.
