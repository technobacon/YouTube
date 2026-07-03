# OSRS Facts Ledger

The channel's accuracy floor. Two rules:

1. **Nothing gets scripted as a stat unless it's in here with a source, or freshly verified.** No numbers from memory.
2. **Every entry carries a source and a date checked.** OSRS patches often — a value true last year can be wrong now. Re-verify anything time-sensitive before it goes in a final script.

Prefer primary sources: the OSRS Wiki (oldschool.runescape.wiki), official Jagex newsposts/patch notes, in-game testing. Note when a "fact" is really a community-derived estimate (e.g. datamined or crowd-sourced drop rates).

## Format

```
| Fact | Value | Source | Date checked | Notes |
```

- **Fact** — the specific claim ("Rune platebody stab defence", "Zulrah unique drop rate", "Moons of Peril released").
- **Value** — the number/date/text.
- **Source** — link.
- **Date checked** — when you last confirmed it (YYYY-MM-DD).
- **Notes** — caveats, whether it's official vs. estimated, version/patch it applies to.

---

## Ledger

| Fact | Value | Source | Date checked | Notes |
|------|-------|--------|--------------|-------|
| XP required for level 99 | 13,034,431 | [OSRS Wiki: Experience](https://oldschool.runescape.wiki/w/Experience) | 2026-07-03 | Canonical, stable since 2001. |
| XP at level 92 | 6,517,253 (≈ half of 99, within ~40 XP) | [OSRS Wiki: Experience](https://oldschool.runescape.wiki/w/Experience) | 2026-07-03 | Curve doubles ~every 7 levels. "92 is half of 99" is accurate. |
| 200M XP cap per skill | 200,000,000 | OSRS Wiki | 2026-07-03 | Canonical. Multiple players have 200M Agility. |
| 2013 revival poll vote count | 449,351 | [Official OSRS tweet](https://x.com/OldSchoolRS/status/963927136586387458), [Wikipedia](https://en.wikipedia.org/wiki/Old_School_RuneScape) | 2026-07-03 | Poll closed 1 Mar 2013; fell short of the 500k free-tier threshold. |
| OSRS launch date | 22 Feb 2013, members-only | Wikipedia / OSRS Wiki | 2026-07-03 | From an Aug 2007 backup. Limited F2P added Feb 2015. |
| All-time concurrent peak | 240,756 on Sun 3 Aug 2025 | [GamesRadar](https://www.gamesradar.com/games/mmo/with-a-new-record-240-000-players-online-old-school-runescape-is-roughly-8x-bigger-than-its-sister-mmo-and-would-be-the-fourth-biggest-game-on-all-of-steam-if-not-for-a-technicality/), [PCGamesN](https://www.pcgamesn.com/old-school-runescape/player-record-august-2025) | 2026-07-03 | No update/event that weekend. ~8x RS3's concurrents per GamesRadar. Re-check before publish — may have been surpassed since. |
| Dec 2024 Leagues peak | 231,719 concurrent | Search-verified (Leagues V: Raging Echoes) | 2026-07-03 | Was the record until Aug 2025. |
| Camus closing lines, O'Brien translation | "The struggle itself towards the heights is enough to fill a man's heart. One must imagine Sisyphus happy." | *The Myth of Sisyphus* (1942; O'Brien trans. 1955), [full text](https://www.sccs.swarthmore.edu/users/00/pwillen1/lit/msysip.htm) | 2026-07-03 | Note "towards," essay's final two sentences. |
| Run energy rework | Betas 27 Jun + 24 Oct 2024; regen formula (Agility/10)+15, was (Agility/6)+8 | [OSRS Wiki update pages](https://oldschool.runescape.wiki/w/Update:Run_Energy_Changes) | 2026-07-03 | Buffed low-level regen; drain slower at all weights. Part of Project Rebalance era. |
| WHO gaming disorder | Added to ICD-11, adopted 2019 | WHO ICD-11 | 2026-07-03 | From knowledge, high confidence (in effect Jan 2022). Verify wording before quoting WHO directly. |
| Sisyphus myth details | Chained Thanatos (first offense); escaped underworld via unperformed funeral rites (second); boulder punishment | Standard Greek mythology (Homer, Odyssey XI) | 2026-07-03 | Prometheus's tormentor is an eagle, not a vulture. |
| Game tick length | 0.6s nominal (100/min); crowded worlds run ~0.616–0.618s (e.g., World 302), emptier ~0.606–0.611s | [OSRS Wiki: Game tick](https://oldschool.runescape.wiki/w/Game_tick) | 2026-07-03 | Actions registered mid-tick begin at next tick start (0–0.6s input latency). Run = 2 tiles/tick, walk = 1. |
| Client-side UI cycle | 20ms (right-click menus, tab switching) | OSRS Wiki: Game tick | 2026-07-03 | Separate from the 600ms server tick — faster loops exist in the codebase. |
| Prayer drain mechanics | Each active prayer adds drain effect to a counter per tick; a point is lost when counter exceeds resistance = 2 × prayer bonus + 60 | [OSRS Wiki: Prayer](https://oldschool.runescape.wiki/w/Prayer_flicking) | 2026-07-03 | Key: no drain is charged on the tick a prayer is activated — this is what makes flicking possible. 1-tick flicking = off/on every tick, zero drain. |
| Skilling timer manipulation | Herb + swamp tar sets a 3-tick delay; knife + teak/mahogany logs 3t; celastrus bark 4t | [OSRS Wiki: Tick manipulation](https://oldschool.runescape.wiki/w/Tick_manipulation) | 2026-07-03 | The "skilling timer" counts down to the next action roll. |
| 3-tick fishing | Barbarian/fly fishing rolls every 5 ticks by default; 3-ticking ≈ 67% faster XP | OSRS Wiki: Tick manipulation | 2026-07-03 | |
| 3t4g granite | Adamant pick mines granite every 4 ticks; 3-ticked = fastest Mining XP in game | OSRS Wiki: Tick manipulation | 2026-07-03 | |
| 1-tick karambwans | Over 1,000,000 Cooking XP/hr | OSRS Wiki: Tick manipulation | 2026-07-03 | |
| 2-tick woodcutting | Default WC delay 4 ticks; auto-retaliate vs NPC with rapid weapon → rolls every 2 ticks | OSRS Wiki: Tick manipulation | 2026-07-03 | |
| **GAP:** origin of the 600ms value | No dev statement found explaining the original choice or confirming it can't change | searched 2026-07-03 | 2026-07-03 | Script must frame origin as general early-2000s server architecture, no invented dev quotes. |
| RS3 tick system | RS3 runs on the same 600ms game tick; EoC (Nov 2012) rebuilt combat on top of it without changing the tick | Owner-confirmed 2026-07-03; common knowledge | 2026-07-03 | EoC launch date (Nov 2012) from memory — verify before putting on screen. |
| Quest count / quest points | 181 quests, 339 QP (24 F2P / 157 members) | [OSRS Wiki: Quests](https://oldschool.runescape.wiki/w/Quests) | 2026-07-03 | As of 30 Jun 2026. First quest: Cook's Assistant; latest: The Blood Moon Rises. Max-QP hurdles: 75 Magic, 75 Firemaking, 74 Slayer. |
| Recipe for Disaster | Released 15 Mar 2006; 10 parts (intro + 8 subquests + finale); full completion requires 175 QP; final reward = Barrows gloves via Culinaromancer's chest | [OSRS Wiki: RFD](https://oldschool.runescape.wiki/w/Recipe_for_Disaster) | 2026-07-03 | Also 70 Cooking + other skills. Sequel to Cook's Assistant, the game's first quest. |
| Fairy ring unlock | Fairytale I complete + Fairytale II started (up to Fairy Godfather's permission; FT2 completion NOT required); prereq chain: Restless Ghost, Priest in Peril, Nature Spirit, Lost City | [OSRS Wiki: Fairy ring](https://oldschool.runescape.wiki/w/Fairy_ring) | 2026-07-03 | 55 working ring codes of 64 possible. |
| Quest Helper adoption | Among the most popular Plugin Hub plugins; exact install count NOT verified | searched 2026-07-03 | 2026-07-03 | Stats site (runelite.phyce.dev) is JS-rendered, unreadable via fetch. Get the number before it goes in a script. |
| Quest unlock examples (canonical, spot-check at script stage) | Ancient Magicks ← Desert Treasure I; Piety ← King's Ransom + Knight Waves; dragon scimitar ← Monkey Madness I; Prifddinas ← Song of the Elves (2019); Morytania ← Priest in Peril; Cook's Assistant = 300 Cooking XP | memory, high confidence | 2026-07-03 | All standard knowledge; verify each on wiki before final script. |
| Aronson & Mills 1959 | Severity-of-initiation experiment: subjects who underwent an embarrassing initiation rated the group more highly (effort justification) | memory, high confidence | 2026-07-03 | Classic social psych; verify citation wording before quoting on screen. |
| GE tax rate history | Introduced 9 Dec 2021 at 1%; raised to 2% on 29 May 2025; **still 2% as of Jul 2026 (re-verified)**; capped at 5M coins per item; items under 50 coins effectively untaxed; staples exempt (bread, lobster, mind runes, bronze arrows, basic tools) | [OSRS Wiki: Grand Exchange tax](https://oldschool.runescape.wiki/w/Grand_Exchange_tax) | 2026-07-03 | Seller pays. The 2% increase shipped **unpolled** (Yama CAs & More update). Item sink values: 399 tbows ≈ 587.3B, 5.4k arcane ≈ 666.4B, 5.4k spectral ≈ 140.6B. |
| Venezuela specifics (NPR Planet Money) | Est. 1.8M Venezuelans have played for money; green dragons; ~$8/day typical ($7–10 good nights); Venezuelan coalition (purple/pink hats) beat Reign of Terror for Revenant Caves control ~Jan 2020 after a week-long war; Jagex then nerfed the caves without confirming motive; 2019 national blackout visibly dented player counts | [NPR transcript](https://www.npr.org/transcripts/1018915121) | 2026-07-03 | The "half the player base vanished during the blackout" claim appears in coverage — do NOT use a number without re-reading the transcript directly. |
| Real-world monetary history (for analogies) | Bank of England founded 1694 to fund war against France; UK left the gold standard in 1931; D3 real-money auction house closed March 2014 | general history / memory, high confidence | 2026-07-03 | Verify D3 RMAH date before on-screen use. |
| Item sink totals | ~5.6 trillion coins of items deleted since launch (through 29 May 2025), incl. 399 twisted bows, 5,400 spectral shields, 253,000 occult necklaces | OSRS Wiki: Grand Exchange tax | 2026-07-03 | Tax revenue buys designated items (raid uniques, GWD, Nightmare, high Slayer drops) and deletes them. Update totals at recording time. |
| GE launch in OSRS | 26 Feb 2015; polled, passed at 76.3% (threshold 75%) | [OSRS Wiki: Grand Exchange](https://oldschool.runescape.wiki/w/Grand_Exchange) | 2026-07-03 | 8 slots members / 3 F2P. Jagex reserves intervention rights on manipulation. |
| Buy limits | Per-item purchase caps every 4 hours; connected limits across variants (e.g., prayer potion doses share one limit) | OSRS Wiki: Grand Exchange | 2026-07-03 | |
| Bonds | Introduced OSRS 30 Mar 2015; 1 bond = 14 days membership; only item legally purchasable with real money; GE price ~11.6M coins | [OSRS Wiki: Old school bonds](https://oldschool.runescape.wiki/w/Old_school_bonds) | 2026-07-03 | Price moves constantly — re-check at recording. |
| Death's Coffer | Sacrifice tradeables worth >10,000 coins for value +5% credited toward death fees | [OSRS Wiki: Sink (economy)](https://oldschool.runescape.wiki/w/Sink_(economy)) | 2026-07-03 | |
| Gold sinks catalogue | Shop purchases, banned-account wealth deletion, POH construction, Barrows repairs, crystal/powered-staff recharges, sawmill planks | OSRS Wiki: Sink (economy) | 2026-07-03 | |
| Jagex economy planning blog | "Old School Economy — Future Plans" official newspost exists (proposed the 2% tax framing) | [wiki mirror](https://oldschool.runescape.wiki/w/Update:Old_School_Economy_-_Future_Plans) | 2026-07-03 | Evidence Jagex explicitly reasons in monetary-policy terms. |
| Venezuela gold farming | Bolivar hyperinflation (2014–2020 GDP crash) drove large-scale OSRS gold farming; OSRS gp held value better than the bolivar; covered by NPR Planet Money ("How Hyperinflation in Venezuela Led to Clan Warfare in OSRS"); Jagex later nerfed the farmed content (Revenant caves) | [NPR](https://www.npr.org/transcripts/1018915121), Kotaku, MassivelyOP | 2026-07-03 | Re-read NPR transcript before scripting specific claims (dates, clan war details). |

---

## Interpretation vs. fact

This file holds **facts only** — how a mechanic *works*. Claims about what a mechanic is *for*, or why Jagex chose it, are arguments and belong in the script (labelled as interpretation), not here. Unless there's an actual dev quote or newspost stating intent, in which case log the quote with its source.
