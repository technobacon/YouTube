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

---

## Interpretation vs. fact

This file holds **facts only** — how a mechanic *works*. Claims about what a mechanic is *for*, or why Jagex chose it, are arguments and belong in the script (labelled as interpretation), not here. Unless there's an actual dev quote or newspost stating intent, in which case log the quote with its source.
