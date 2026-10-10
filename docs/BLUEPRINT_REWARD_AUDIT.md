# RSI Discovery Month 4.10.2 LIVE – Blueprint / component audit

## Magyar

**Nem sikerült igazolni, hogy bármelyik RSI Discovery jutalomsáv
gyártási blueprintet adna.** Nem helyes tehát automatikusan BP-ként
megjeleníteni őket. A CIG a jutalmakat komponensként és egyéb tárgyként
hirdeti; MrKraken 4.10.2 LIVE `contracts.ini` fájljának megvizsgált
`iasi_` sorain nincs `[BP]` jelölés.

**A pontos komponensnevek:**

| Track | Pont | Komponens |
|---|---:|---|
| Transport | 2 000 | BriskAir IC-20 Cooler – S2 Grade B |
| Transport | 6 500 | BriskAir IC-30 Cooler – S3 Grade B |
| Collection | 2 000 | Delphi RS-20 Radar – S2 Grade B |
| Collection | 6 500 | Delphi RS-30 Radar – S3 Grade B |
| Defense | 2 000 | Sovereign IP-20 Power Plant – S2 Grade B |
| Defense | 6 500 | Sovereign IP-30 Power Plant – S3 Grade B |
| Overall | 4 500 | BriskAir IC-10 Cooler, Delphi RS-10 Radar, Sovereign IP-10 Power Plant – S1 Grade B |
| Overall | 30 000 | Helios Power Plant – S1, S2, S3 Grade A |

Ez a lista a 2026.10.09-i LIVE adatkinyerésből származó
konkrét neveket használja; a jutalom formáját (fizikai inventory
objektum / webhangar / BP) a játékbeli jóváírás bizonyítaná véglegesen.

A **Wikelo Gemini LMG / Grey Combat Armour** receptjei ugyanabban a
4.10.2-es patchben jelentek meg, de NEM az RSI Discovery reward track részei.

## English

**No RSI Discovery reward tier has been verified to award a
crafting blueprint.** The official event calls them components
and equipment, and the inspected `iasi_` contract text in
StarStrings 4.10.2 LIVE contains no `[BP]` marker.

The exact component names and tiers are listed above.
The distinction between a component item and a blueprint is important;
the presence of a crafting recipe elsewhere in the game does not prove
it is awarded in this event.

Wikelo Gemini LMG and Grey Combat Armour recipes are
separate 4.10.2 content, not RSI Discovery reward track prizes.

## Evidence

- https://github.com/MrKraken/StarStrings
- https://github.com/KrovaxCode/SCMDB_DATA
- https://www.reddit.com/r/LowSodiumStarCitizen/comments/1x1qgfs/live_410212881860_findings/
- https://robertsspaceindustries.com/comm-link/transmission/21334-Alpha-4102-RSI-Discovery-Month
