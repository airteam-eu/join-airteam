# Úkol 3 (volitelný): AI — texty v tónu značky, které umíte spustit znovu

**Čas:** zhruba 45 minut  
Tento úkol **nemusíte** dělat. Když ho odevzdáte, díváme se na vkus a na to, jestli postup umíte použít i na jiný produkt.

## Kontext

AIR TEAM mluví jako **Hrdina / posádka**: věcně, bez korporátní vaty. Zákazník je hrdina příběhu, ne my. Vzor věty: **situace → akce → výsledek**. Úvodní věta není obecná pravda o firmě („spolehlivé řešení na míru“).

Citlivé texty u nás schvaluje **Marketing Manager**. Vy dodáte návrh a označíte, co je rizikové.

Chceme **postup, který půjde spustit znovu**: příští týden jiný produkt, stejný stroj.

## Úkol

Postavte generátor — prompt, Cursor skill, nebo krátký skript. Vstup:

- typ zákazníka (soukromý pilot / partner-MRO)
- fáze (první kontakt / obchod se neuzavřel)
- **jeden** veřejný produkt, služba nebo kategorie z [webů skupiny](../README.md#veřejné-weby-skupiny)

Výstup:

1. **3 varianty** reklam ve vyhledávání (titulky a popisy) **nebo** hlavního textu na Meta — vyberte **jeden** kanál a držte jeho limity.
2. **3 navazující e-maily:** předmět, náhledový text, krátké jádro (situace → akce → výsledek).

U každé varianty napište, **co testujete** (úvod, výzva k akci, důkaz). Jedna věta navíc: co byste ještě poslali Marketing Managerovi ke schválení a co může jít do A/B testu s menším rizikem pro značku.

## Co odevzdat

| Kam | Obsah |
|-----|--------|
| `pipeline/` | Prompt, skill, nebo skript — to, čím to spustíte znovu |
| `output/variants.md` | 6 kousků (3 reklamy + 3 e-maily) + co u každé testujete |
| `output/how-i-reuse.md` | Jak to příští týden spustíte na jiný produkt |

## Co hledáme

Systém a vkus. Ne šest ručně vyleštěných sloganů bez návodu, jak vznikly.
