# Data Sources / Adatforrások

Checked / Ellenőrizve: **2026-10-10**

## Official / Hivatalos
- Star Citizen Alpha 4.10.2 LIVE Release Notes  
  https://robertsspaceindustries.com/en/comm-link/Patch-Notes/21351-Star-Citizen-Alpha-4102
- FAQ: RSI Discovery Month  
  https://robertsspaceindustries.com/comm-link/transmission/21350-FAQ-RSI-Discovery-Month
- Alpha 4.10.2: RSI Discovery Month – Missions, Rewards, & Icons  
  https://robertsspaceindustries.com/comm-link/transmission/21334-Alpha-4102-RSI-Discovery-Month

## Game-data / community references
- Star Citizen Wiki – RSI Discovery Month  
  https://starcitizen.tools/RSI_Discovery_Month
- VerseHub – RSI Discovery Month  
  https://versehub.space/events/discovery-month

## Known conflicts / Ismert eltérések
1. **Clear Hostiles from Site** — Star Citizen Wiki: 164; VerseHub: 167. A számoló 164-et használ és kijelzi az eltérést.
2. **Ling Supply Delivery** — 417 Track, Star Citizen Wiki szerint 416 Overall/Event.
3. **Mining Quality** — nincs jelenleg igazolt minimum Quality az Iron/Beryl/Quantainium leadásokhoz; a guide nem talál ki értéket.
4. **Scavenger Hunt** — VerseHub player-reportként listázza; korábbi PTU finding disabled státuszt jelzett. Nem része a gyors útvonalnak.

## Reward versus blueprint clarification / Jutalom kontra blueprint

**Magyar:** A CIG 2026.10.09-i RSI Discovery Month FAQ-ja a megszerezhető jutalmakat festések, flight blade-ek, komponensek, páncélok, fegyverek és eszközök formájában sorolja fel; **blueprint nincs megjelölve a jutalomsávokon**. A Constellation Mk V Centaurus + Skylark külön **5 napos bérlés**.

**English:** CIG's 2026-10-09 RSI Discovery Month FAQ lists ship paints, flight blades, components, armor, weapons and tools. **The reward tracks do not identify crafting blueprints**. The Constellation Mk V Centaurus + Skylark is a separate **5-day rental**.

Official FAQ: https://robertsspaceindustries.com/comm-link/transmission/21350-FAQ-RSI-Discovery-Month
Event page: https://robertsspaceindustries.com/comm-link/transmission/21334-Alpha-4102-RSI-Discovery-Month


## Krovax SCMDB_DATA cross-check / Krovax SCMDB_DATA keresztellenőrzés

- Repository: https://github.com/KrovaxCode/SCMDB_DATA
- Snapshot manifest: https://github.com/KrovaxCode/SCMDB_DATA/blob/main/data/latest.json
- Mining data: https://github.com/KrovaxCode/SCMDB_DATA/blob/main/data/mining_data-4.10.2-live.12881860.json
- Build: `4.10.2-live.12881860`; source snapshot `generated_at`: `2026-10-09T14:34:48Z`.
- Observed mining `rarity`: `Iron (Ore) = common`; `Beryl (Raw) = rare`; `Quantainium (Raw) = legendary`.
- `qualityBands` describe game mining data, **not RSI Discovery contract acceptance thresholds**. Minimum `Procure Refined` mission Quality remains **UNVERIFIED**.
- General `crafting_blueprints` data does **not** prove that RSI Discovery reward tracks grant crafting blueprints. The official reward list remains authoritative.
- `mission-history` is keyed mission history / version metadata and must not be treated as proof of complete event point/payout tables.
- Public mirror has **no explicit GitHub license** at inspection time. This project references and briefly summarizes factual observations; it does **not** bundle or redistribute SCMDB's datasets.

**Magyar:** A ritkasági besorolás és a Quality-sáv nem egy event küldetés minimumminősége. Nem találunk ki mission thresholdot.

**English:** Mining rarity and quality bands are not event mission minimum-quality requirements. Do not infer an unverified mission threshold.


## 4.10.2 reward component audit / Jutalomkomponens-ellenőrzés

- MrKraken / StarStrings (`master`, sc-alpha-4.10.2_live_12881860):
  https://github.com/MrKraken/StarStrings
  `src/For_Tool_Creators/contracts.ini` — `[BP]` denotes potential
  contract blueprint rewards; inspected `iasi_` entries did not carry
  the marker.
- 2026-10-09 LIVE reward datamine:
  https://www.reddit.com/r/LowSodiumStarCitizen/comments/1x1qgfs/live_410212881860_findings/
  — exact component names.
- CIG event information:
  https://robertsspaceindustries.com/comm-link/transmission/21334-Alpha-4102-RSI-Discovery-Month
  — lists components as rewards, not explicitly BP items.
- In-game reward inventory/account grant still needs separate confirmation.


## 1.0.4 – SCMDB blueprint-source mission panel

- [Krovax / SCMDB_DATA 4.10.2 LIVE blueprint JSON](https://github.com/KrovaxCode/SCMDB_DATA/blob/main/data/crafting_blueprints-4.10.2-live.12881860.json)
- [SCMDB](https://scmdb.net/) blueprint pool interface (screenshot source supplied by user).
- [Star Citizen Wiki – GUARD blueprint](https://api.star-citizen.wiki/blueprints/89800887-d53c-4519-a5c2-45e551b889b4)
- [Star Citizen Wiki – Lotus blueprint](https://api.star-citizen.wiki/blueprints/lotus)
- [Star Citizen Wiki – TigerLilly blueprint](https://api.star-citizen.wiki/blueprints/tigerlilly)

All six displayed missions correspond to Headhunters blueprint-source missions;
**they are not RSI Discovery Month contracts**. Source pages may span build versions.
No 4.10.2 LIVE BP pool-ID was inferred from the screenshot. This is a
static, separately labeled reference, not a live pool-query replication.


## 1.0.5 – SCMDB 4.10.2 BP recipe and acquisition source

Exact 22 screenshot blueprints and recipe slot quantities derived from `crafting_blueprints-4.10.2-live.12881860.json`. Acquisition pool membership from `merged-4.10.2-live.12881860.json`, using `blueprintPools` and `contracts[].blueprintRewards`. Not part of the RSI Discovery track. Full table: [`SCMDB_4_10_2_BLUEPRINTS.md`](SCMDB_4_10_2_BLUEPRINTS.md).


