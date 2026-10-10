# sPg RSI Discovery Month 4.10.2 – Event Guide

[Magyar](#magyar) · [English](#english)

## Magyar

Kétnyelvű, egyfájlos Star Citizen segédlet az **RSI Discovery Month** eventhez, **Alpha 4.10.2 LIVE** alapján.

### Fő funkciók
- **31 ismert contract**: Transport, Collection és Defense.
- A **Track pont** és az **Overall pont** külön kezelve.
- aUEC jutalmak és feloldási ponthatárok.
- Elméleti ismétlésszám a 10 000 pontos career trackhez.
- Hauling cargo-, mining- és salvage-anyagigények.
- Solo és csoportos gyors útvonalak.
- Mind a 16 reward tier.
- 5 napos Constellation Mk V Centaurus + Skylark rental contract.
- HU / EN kapcsoló ugyanabban az `index.html` fájlban.
- Mobilbarát, sPg-stílusú sötét UI.
- Nincs külső CSS vagy JavaScript runtime-függőség.

### Event logika
A három fő tracket külön kell teljesíteni:
- **Transport: 10 000**
- **Collection: 10 000**
- **Defense: 10 000**

Az **Overall / Your Total: 30 000** ezekből töltődik.

### Fontos adatbiztonság
A guide nem talál ki hiányzó adatot. A mining leadásokhoz jelenleg nincs megbízhatóan igazolt LIVE minimum Quality küszöb, ezért nincs automatikusan Q600+ ráírva.

Két friss forráseltérés külön jelölve van:
- `Clear Hostiles from Site`: **164 vs 167 pont**.
- `Ling Supply Delivery`: **417 Track / 416 Overall** a Wiki szerint.

Források: [`docs/DATA_SOURCES.md`](docs/DATA_SOURCES.md)

### Használat
Nyisd meg az `index.html` fájlt böngészőben, vagy publikáld GitHub Pages-szel.

---

## English

A bilingual, single-file Star Citizen helper for **RSI Discovery Month**, based on **Alpha 4.10.2 LIVE**.

### Main features
- **31 known contracts** across Transport, Collection and Defense.
- Separate **Track points** and **Overall points**.
- aUEC rewards and unlock thresholds.
- Theoretical repeats required for a 10,000-point career track.
- Hauling cargo, mining and salvage material requirements.
- Fast solo and group routes.
- All 16 reward tiers.
- 5-day Constellation Mk V Centaurus + Skylark rental contract.
- HU / EN switch inside the same `index.html`.
- Responsive sPg-style dark UI.
- No external CSS or JavaScript runtime dependency.

### Event logic
Each career track must be completed separately:
- **Transport: 10,000**
- **Collection: 10,000**
- **Defense: 10,000**

**Overall / Your Total: 30,000** fills from those tracks.

### Data integrity
The guide does not invent missing values. No trustworthy LIVE minimum Quality threshold is currently verified for the mining turn-ins, so Q600+ is not assumed.

Two current source conflicts are explicitly marked:
- `Clear Hostiles from Site`: **164 vs 167 points**.
- `Ling Supply Delivery`: **417 Track / 416 Overall** according to the Wiki.

Sources: [`docs/DATA_SOURCES.md`](docs/DATA_SOURCES.md)

### Usage
Open `index.html` in a browser or publish it with GitHub Pages.

## License
MIT. See [`LICENSE`](LICENSE). Unofficial Hungarian translation: [`LICENSE_HU_UNOFFICIAL.md`](LICENSE_HU_UNOFFICIAL.md).
