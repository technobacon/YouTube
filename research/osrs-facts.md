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

---

## Interpretation vs. fact

This file holds **facts only** — how a mechanic *works*. Claims about what a mechanic is *for*, or why Jagex chose it, are arguments and belong in the script (labelled as interpretation), not here. Unless there's an actual dev quote or newspost stating intent, in which case log the quote with its source.
