# M461AB Input Module · Unsorted

Ward-Beck Systems M461AB. Wiki page: [M461AB on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M461AB.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 1 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 4 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 1 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 2 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 0 |

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M461AB - RTO-144 Connections.pdf`

## RTO-144 pinout

RTO-144 edge connector. Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | Mic In | in | A1 + | high |
| 9 | Direct OUT | out | A4 + | high |
| 10 | Line | io | A2 + | high |
| 11 | Fader Return | in | B4 + | high |
| 12 | CHON OUT - OUT | out | B3 + | high |
| 13 | Insert Return | in | B2 + | high |
| 14 | Insert Send | out | B1 + | high |
| 16 | Right OUT | out | A3 + | high |
| A | Mic In | in | A1 - | high |
| K | Direct OUT | out | A4 - | high |
| L | Line | io | A2 - | high |
| M | Fader Return | in | B4 - | high |
| N | CHON OUT - OUT | out | B3 - | high |
| P | Insert Return | in | B2 - | high |
| R | Insert Send | out | B1 - | high |
| T | Right OUT | out | A3 - | high |

**Straps:** CH ON LAMP: JMP.Z.W · 24V Ground: JMP.X.18 · 24V to 25V: JMP.Y.21 · CH ON GND : JMP.3 · Insert  SEND: JMP.14.13 · Insert  Return: JMP.R.P · Fader Send: JMP.12.11 · Fader Return: JMP.N.M

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M461AB.kicad_sym](KICAD/M461AB.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
