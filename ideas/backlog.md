# Idea Backlog

Every video starts here as a thesis, not a topic. A good entry is something a knowledgeable player might argue with or hasn't consciously noticed. "Let's look at X" is not a thesis.

**Status key:** `spark` (raw) → `angle` (thesis locked) → `outlined` → `drafting` → `final` → `published` → `scrapped`

### Entry format

```
## <Working title>
- **Thesis:** <one arguable sentence>
- **The itch:** <what's strange/unfair/unnoticed that makes a viewer lean in>
- **Possible hook:** <the first 15s>
- **Strongest counterargument:** <the steelman you'll have to beat>
- **Evidence needed:** <numbers/encounters/patch history to verify>
- **Status:** spark
- **Facts confidence:** <low/med/high — do we know the numbers?>
```

---

## CANDIDATES — pitched 2026-07-03, awaiting pick

## 1. Old School RuneScape Is Held Together by Lag
- **Thesis:** The 600ms tick — a 2001 server constraint the game never shed — accidentally built OSRS's entire skill ceiling, and smoothing it out would delete two decades of technique.
- **The itch:** Players curse the tick daily (pathing, dead clicks, stalls) while every skill-expression mechanic they're proud of — flicking, tick manipulation, tick-eating — only exists because of it.
- **Possible hook:** A world-record speedrun clip where the player's hands are doing something invisible to the camera, then: every trick in that clip is an exploit of lag.
- **Strongest counterargument:** The jank is a real tax — new players bounce off dead clicks and pathing misery; Jagex itself has flirted with engine work. Romanticizing limitation is survivorship bias.
- **Evidence needed:** verified 2026-07-03 → `research/osrs-facts.md`. Gap: no dev statement on the 600ms origin (script hedges accordingly).
- **Status:** drafted → `scripts/drafts/held-together-by-lag.md`
- **Facts confidence:** high

## 2. The Attention Tax (OSRS's Invisible Stat)
- **Thesis:** Every reward rate in OSRS is priced in attention — the game has a second, unlisted balancing axis running from full-afk to tick-perfect, and once you see it, a dozen "weird" design choices snap into focus.
- **The itch:** Why does prayer flicking exist? Why is the best XP always the most miserable? Why can you legitimately play this game while working? Same answer, every time.
- **Possible hook:** Two players get the same 99. One watched Netflix for 300 hours; one performed 300 hours of tick-perfect inputs in half the time. The game priced both fairly, and no other game can.
- **Strongest counterargument:** "Attention pricing" at the top end is an RSI machine, and RuneLite (markers, metronomes, helpers) has quietly deflated the price of attention without rewards adjusting — the axis is eroding.
- **Evidence needed:** anchors verified 2026-07-03 → `research/osrs-facts.md` (AFK timer to 25 min, Jagex "low intensity skillers" blog language, tick-manip rates, prayer drain). Rung XP pairs to verify at script stage.
- **Status:** outlined (v2 — ascent structure, honest-attention-market angle) → `scripts/drafts/attention-tax.md`
- **Facts confidence:** high

## 3. OSRS Is a Democracy, and It Shouldn't Work
- **Thesis:** OSRS is the only MMO governed by player supermajority, and the punishing threshold — built to slow Jagex down — is the single constitutional decision that kept the game alive while every other MMO drifted away from its players.
- **The itch:** Game designers universally say players don't know what they want. OSRS handed players a veto in 2013 and outgrew everything in its genre.
- **Possible hook:** The graveyard: Artisan, dead at the polls. Warding, dead at the polls. Skills a design team spent months on, executed by the electorate — and the game is healthier for the bodies.
- **Strongest counterargument:** It's a managed democracy — Jagex writes the ballot, "integrity changes" bypass the vote entirely, and a supermajority is a status-quo veto where 30% of voters rule. The system's real function is theater that manufactures consent.
- **Evidence needed:** threshold history (75% at launch; lowered to 70% — confirm date), Artisan/Warding poll results and dates, Sailing's passing vote, examples of unpolled integrity changes.
- **Status:** angle
- **Facts confidence:** med

## 4. Jagex Is Running a Central Bank
- **Thesis:** The Grand Exchange is a managed economy wearing a convenience feature's clothes — buy limits, a transaction tax, item sinks, and gold sinks are monetary policy, and Jagex's least glamorous design work is the reason OSRS avoided the hyperinflation that ate every other MMO economy.
- **The itch:** Your bank tab has held its value for a decade. That's bizarre. Ask a WoW player what their gold buys now versus 2019.
- **Possible hook:** Open on the GE ticker like a Bloomberg terminal. Somewhere in Cambridge, someone's job is deciding how much money should exist in a medieval fantasy world.
- **Strongest counterargument:** The real economy is the shadow one — bots and RWT set prices more than Jagex does, and the "central bank" is a night watchman who can't stop the counterfeiters.
- **Evidence needed:** verified 2026-07-03 → `research/osrs-facts.md` (tax 1%→2% history, 5.6T item sink w/ 399 tbows, GE polled in at 76.3%, bonds Mar 2015, Venezuela/NPR). Re-check time-sensitive numbers at recording.
- **Status:** drafted → `scripts/drafts/jagex-central-bank.md`
- **Facts confidence:** high (tax re-verified 2% as of Jul 2026; sink/bond snapshots to refresh at recording)

## 5. OSRS Quests Are Designed to Waste Your Time
- **Thesis:** OSRS quests are the best in the genre because they're allowed to inconvenience you — they gate rather than reward, refuse to mark objectives, and the permission slips they hand out (mechanics, areas, gear) are what keep the world's geography meaningful.
- **The itch:** By every modern metric — XP/hour, repeatability, voice acting, waypoints — these quests are terribly designed. They're also the thing everyone tells you the game does best. Both observations are correct.
- **Possible hook:** A modern MMO quest: follow the dotted line, kill ten boars, ding. An OSRS quest: a talking chicken, a puzzle that stumps you for an hour, and at the end — permission to use fairy rings for the rest of your life.
- **Strongest counterargument:** Quest Helper. The majority now follows a dotted line anyway, so the sacred design is already dead and nostalgia is doing the rest. (Response has to take plugin adoption seriously.)
- **Evidence needed:** core facts verified 2026-07-03 → `research/osrs-facts.md` (181 quests/339 QP, RFD 175 QP + 10 parts, fairy ring chain). Gap: Quest Helper install count.
- **Status:** drafted → `scripts/drafts/quests-waste-your-time.md`
- **Facts confidence:** high (QH adoption number pending)

---

## SEED IDEAS
*Unvalidated sparks — theses to pressure-test, not settled takes. Verify all mechanics before drafting.*

## In Defense of Going Dry
- **Thesis:** OSRS's refusal to add meaningful bad-luck protection is correct — the moment drops are guaranteed, they become wages, and the entire emotional economy of the drop log collapses.
- **The itch:** The community begs for pity timers; Jagex keeps mostly refusing; the game keeps growing.
- **Strongest counterargument:** Going 3x dry on a 1/512 isn't identity, it's disrespect for the player's time — and newer designs (points systems, tradeable uniques) show Jagex already quietly agrees.
- **Status:** spark
- **Facts confidence:** low

## Jagex No Longer Decides How Hard Its Game Is
- **Thesis:** RuneLite moved difficulty tuning out of Jagex's hands — bosses are designed at one difficulty and played at another, and every encounter since ToA has been balanced *around* the plugin layer.
- **The itch:** True tile markers, timers, and helpers changed what "hard" means, and nobody voted on it.
- **Strongest counterargument:** Plugins are just information parity with the wiki; skill expression survived (Inferno is still the Inferno).
- **Status:** spark
- **Facts confidence:** low

## Slayer solves the problem of "what do I even do today"
- **Thesis:** Slayer's genius isn't the rewards, it's that it outsources the player's daily decision-making and routes them through content they'd otherwise skip.
- **The itch:** Most players say they hate their task list yet log in for it anyway. Why does an assignment feel better than free choice?
- **Possible hook:** Open on the paralysis of a maxed account with nothing to do, versus a fresh Slayer task.
- **Strongest counterargument:** It's a Skinner-box chore loop dressed up as content; "engagement" isn't the same as good design.
- **Evidence needed:** how tasks gate content access, XP rates, the role of block/skip mechanics.
- **Status:** spark
- **Facts confidence:** low

---

## SCRAPPED

## Sisyphus Would Have Loved Old School RuneScape
- Fully drafted 2026-07-03, scrapped by owner same day. Script preserved in git history (`scripts/drafts/sisyphus-osrs.md`, removed at commit after 068cc7d). Verified facts from it remain valid in `research/osrs-facts.md`. Philosophy-first framing; the channel's lane is mechanics-first.

## Prayer is a second health bar the game never tells you about
- Absorbed into candidate #2, "The Attention Tax" — the prayer material becomes its strongest body section.

---

## ALREADY COVERED — don't repeat, but mine for callbacks
*See `channel-context.md` for the full catalogue. These topics are spent as standalone videos; reference them, don't redo them.*
- Inventory / 28 slots / storage — video #1.
- Moons of Peril: defence calculation (#5), flat armor (#6), supply/dungeon ecosystem (#7). The whole Moons well is dug. A *fourth* Moons angle would likely underperform (see the trilogy decay note in `channel-context.md`).
- OSRS vs. WoW Classic design (#2).
- Hueycoatl boss critique (#4).

## STRATEGY NOTE FOR NEW IDEAS
Your best video was a self-contained, contrarian claim about a thing players thought they understood ("DPS is a lie"). Bias new sparks toward that shape: pick a widely-held OSRS belief and overturn it, and make it standalone — not "part N of a series."
