# 4.10.2 LIVE SCMDB Blueprint-katalógus / Blueprint Catalogue

**HU:** Az RSI Discovery event 31 contractja és a 16 event reward tier **nem változott**. Ez a 22 BP egy **külön katalógus**, a felhasználó által mutatott screenshotok pontos komponenseivel és receptjeivel. **Nem RSI Discovery rewardok.**

**EN:** The 31 RSI Discovery contracts and 16 event reward tiers are **unchanged**. This separate 22-BP catalogue matches the screenshot components and their recipes. **These are not RSI Discovery event rewards.**

Adatverzió / Data version: `4.10.2-live.12881860`.

**Források / Sources:**

- [Crafting blueprints 4.10.2 LIVE](https://github.com/KrovaxCode/SCMDB_DATA/blob/main/data/crafting_blueprints-4.10.2-live.12881860.json) — `blueprints` / `tiers` / `slots` / `options`, quantities and minQuality
- [Merged 4.10.2 LIVE](https://github.com/KrovaxCode/SCMDB_DATA/blob/main/data/merged-4.10.2-live.12881860.json) — `blueprintPools` and `contracts[].blueprintRewards`, faction and availableSystems
- [StarStrings 4.10.2](https://github.com/MrKraken/StarStrings) — contracts naming and `[BP]` conventions
- Screenshots supplied by the user (Power Plant Grade B, Power Plant Grade A, Cooler Grade B, Radar Grade B)

## Fontos korlátozások / Important limitations

1. `minQuality = 1` in these craft recipe slots is not a Q600+ gate. It does not mean quality cannot affect item performance.
2. Pool membership **does not guarantee a specific BP drop**. Some contract titles appear in multiple systems and difficulty/rank variants; their pools differ.
3. The source confirms these records **exist in the 4.10.2 LIVE build** and can be associated with contract BP pools; it does not alone prove they were first introduced in 4.10.2 rather than an earlier build.
4. Grade labels are taken from the supplied screenshots; recipe quantities and time come from SCMDB's 4.10.2-LIVE data.
5. `BroadSpec` S2 and S3 are **separate records**; a name-only deduplication would be incorrect.
6. Event reward components `BriskAir`, `Delphi`, `Sovereign`, `Helios` are **not identical** to the 22 BP component products. Another craft recipe in the same game build does not imply an event blueprint reward.

## Azonosított receptadatok / Identified recipes

| Component | Group | Grade | Size | System/source | Craft time | Materials for 1 item |
|---|---|---|---:|---:|---:|---|
| IonBurst | power | Civilian B | S1 | Pyro / Foxwell Enforcement | 12:30 | Torite 0.35 SCU, Silicon 0.14 SCU, Laranite 0.24 SCU |
| MagnaBloom | power | Civilian B | S1 | Pyro / Foxwell Enforcement | 12:30 | Torite 0.35 SCU, Silicon 0.14 SCU, Laranite 0.24 SCU |
| IonSurge | power | Civilian B | S2 | Pyro / Foxwell Enforcement | 18:30 | Torite 1.22 SCU, Silicon 0.5 SCU, Laranite 0.85 SCU |
| Radiance | power | Civilian B | S2 | Pyro / Foxwell Enforcement | 18:30 | Torite 1.22 SCU, Silicon 0.5 SCU, Laranite 0.85 SCU |
| IonSurge Pro | power | Civilian B | S3 | Pyro / Foxwell Enforcement | 27:30 | Torite 4.3 SCU, Silicon 1.7 SCU, Laranite 3 SCU |
| Celestial | power | Civilian B | S3 | Pyro / Foxwell Enforcement | 27:30 | Torite 4.3 SCU, Silicon 1.7 SCU, Laranite 3 SCU |
| WhiteRose | power | Civilian A | S1 | Pyro / Headhunters | 13:00 | Borase 0.35 SCU, Laranite 0.14 SCU, Bexalite 0.24 SCU |
| Lotus | power | Civilian A | S2 | Pyro / Headhunters | 19:00 | Borase 1.22 SCU, Laranite 0.5 SCU, Bexalite 0.85 SCU |
| TigerLilly | power | Civilian A | S3 | Pyro / Headhunters | 28:00 | Borase 4.3 SCU, Laranite 1.7 SCU, Bexalite 3 SCU |
| Cryo-Star | cooler | Civilian B | S1 | Nyx / Headhunters | 8:30 | Torite 0.16 SCU, Pressurized Ice 0.16 SCU, Iron 0.1 SCU |
| FlashFreeze | cooler | Civilian B | S1 | Nyx / Headhunters | 8:30 | Torite 0.16 SCU, Pressurized Ice 0.16 SCU, Iron 0.1 SCU |
| Endo | cooler | Civilian B | S1 | Nyx / Headhunters | 8:30 | Torite 0.16 SCU, Pressurized Ice 0.16 SCU, Iron 0.1 SCU |
| Cryo-Star EX | cooler | Civilian B | S2 | Nyx / Headhunters | 10:30 | Torite 0.5 SCU, Pressurized Ice 0.5 SCU, Iron 0.3 SCU |
| FullFrost | cooler | Civilian B | S2 | Nyx / Headhunters | 10:30 | Torite 0.5 SCU, Pressurized Ice 0.5 SCU, Iron 0.3 SCU |
| Taiga | cooler | Civilian B | S2 | Nyx / Headhunters | 10:30 | Torite 0.5 SCU, Pressurized Ice 0.5 SCU, Iron 0.3 SCU |
| Cryo-Star XL | cooler | Civilian B | S3 | Nyx / Headhunters | 13:30 | Torite 1.64 SCU, Pressurized Ice 1.64 SCU, Iron 1 SCU |
| FrostBite | cooler | Civilian B | S3 | Nyx / Headhunters | 13:30 | Torite 1.64 SCU, Pressurized Ice 1.64 SCU, Iron 1 SCU |
| Tige | radar | Military B | S1 | Stanton / Headhunters / Foxwell Enforcement | 10:30 | Borase 0.28 SCU, Bexalite 0.1 SCU, Lindinium 0.1 SCU |
| BroadSpec | radar | Industrial B | S2 | Stanton / Pyro / Nyx / Shubin Interstellar | 11:30 | Agricium 1.2 SCU, Laranite 0.3 SCU, Gold 0.3 SCU |
| Vigilance | radar | Military B | S2 | Stanton / Headhunters | 12:30 | Borase 1.2 SCU, Bexalite 0.3 SCU, Lindinium 0.3 SCU |
| BroadSpec | radar | Industrial B | S3 | Stanton / Pyro / Nyx / Shubin Interstellar | 14:30 | Agricium 2 SCU, Laranite 0.8 SCU, Gold 0.8 SCU |
| Devoue | radar | Military B | S3 | Stanton / Headhunters | 15:30 | Borase 2 SCU, Bexalite 0.8 SCU, Lindinium 0.8 SCU |
