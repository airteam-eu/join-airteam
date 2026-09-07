# Úkol 1 (povinný): PPC — poptávka, ne levný klik

**Čas:** zhruba 45 minut

## Kontext

Z webu a e-shopu k nám chodí poptávky na avioniku a vybavení kokpitu (Smart Supply). Stejné vyhledávání ale míří na **dva světy**:

- **Soukromý pilot / GA** — kratší rozhodování (headset, Garmin do menšího stroje, e-shop)
- **Partner / údržba (MRO)** — delší rozhodování, opakované nákupy, servis a díly do provozu

Obchod potřebuje vědět, koho dostal. Levný klik, který nikdo nevezme, je ztráta.

Část provozu z vyhledávání je šum: sportovní Garmin (hodinky), nabídky práce u aerolinek, hračky a drony mimo náš sortiment. Podklady: [fixtures/noise-vs-intent.md](./fixtures/noise-vs-intent.md). Veřejné weby skupiny jsou v [README](../README.md#veřejné-weby-skupiny) — e-shop, servis i intel.

## Úkol

Navrhněte **Google Ads ve vyhledávání** tak, aby cílem byla **poptávka, kterou obchod vezme** — ne maximum konverzí za každou cenu.

1. **Struktura účtu** — kampaně a skupiny reklam. Oddělte soukromé piloty a partnery tam, kde to dává smysl.
2. **Měření** — jaké konverze sledujete, příklady UTM (`source`, `medium`, `campaign`, `content`), co je „dobrá poptávka“.
3. **Šum** — co vyloučit (vylučující slova, publika) a co v prvním týdnu posílit.
4. **První měsíc** — jedna priorita a jak poznáte, že to zabírá. Bez vymyšleného ROAS. Stačí logika a kdy byste kampaň vypnuli.

Ostrý účet v Google Ads nestavíte. Nevymýšlejte rozpočty v korunách, aby to „vypadalo firemně“.

## Co odevzdat

Do `output/`:

| Soubor | Obsah |
|--------|--------|
| `account-structure.md` | Strom kampaní a skupin reklam |
| `measurement.md` | Konverze a příklady UTM |
| `30-day-priority.md` | Jedna sázka a kdy to vypnout |

## Co hledáme

Kvalitu poptávky a čisté předání obchodu. Ne větu „snížíme cenu za klik“.
