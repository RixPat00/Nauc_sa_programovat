# Style-guide – Akadémia Kód

## Zadanie
Podľa `text.txt` vytvor vlastné `index.html` a `assets/css/style.css`.


Musíš použiť:
- [ ] sémantické HTML (`header`, `nav`, `main`, `section`, `article`, `footer`)
- [ ] CSS premenné v `:root` (farby z tabuľky nižšie)
- [ ] Google Fonts cez `@import` (nadpisy: Space Grotesk, text: DM Sans)
- [ ] **flexbox** (aspoň hlavička a navigácia)
- [ ] **grid** (aspoň karty a pätička)
- [ ] mobile first: základné štýly sú pre mobil, ďalej len `@media (min-width: ...)`
- [ ] BEM názvy tried (napr. `hlavicka__logo`)
- [ ] `:hover` na odkazoch a tlačidlách


## Farby
odnota | Použitie |

oklch(45% 0.2 295)
hsl(260, 15%, 15%)
hsl(0, 0%, 98%)
oklch(90% 0.08 170)
oklch(86% 0.16 95)
hsl(260, 15%, 15%)

## Fonty

- Nadpisy a logo: **Space Grotesk**
- Text: **DM Sans**
- Základná veľkosť textu: `1.1rem`, riadkovanie `1.7`

## Breakpointy
| Zariadenie | Šírka | Karty |
|---|---|---|
| Mobil | do 699px (základ) | 1 stĺpec |
| Tablet | od 700px | 2 stĺpce |
| Desktop | od 1000px | viď layout nižšie |

Desktop layout karty: 3 stĺpce, prvá karta je širšia na tablete.

## Odsadenia
- Bočné odsadenie sekcií: `5%` (na desktope môže byť viac)
- Vertikálne odsadenie sekcií: `3rem`
- Medzery medzi prvkami: `1rem` až `2rem`
