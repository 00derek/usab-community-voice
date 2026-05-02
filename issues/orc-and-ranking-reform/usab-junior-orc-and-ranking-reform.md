---
title: USAB Junior ORC Format and Ranking Reform
date: 2026-04-30
status: draft
audience: USAB junior governance, regional directors, host clubs, coaches and parents
related_issues:
  - ../issue-junior-ranking-points-and-seeding.md
  - ../issue-orc-format-match-load-and-tournament-length.md
---

# USAB Junior ORC Format and Ranking Reform

## Executive Summary

USAB's junior tournament system today exhibits two coupled problems:

1. **Format crisis at ORC**: A round-of-128 single-elimination main draw compressed into 3 days produces 7–9 matches per day for multi-event players in the most popular events (BS U13/U15/U17 and XD U13/U15). This is an attrition test, not a competition, and injuries follow.
2. **Ranking incentives that fuel the crowding**: ORC's 50%-of-JN points value, paired with OLC and CRC at 15%, creates a "must attend ORC" pressure that swells fields beyond what the format can absorb. The best-4 counting model and limited handling of edge cases (playing-up, BWF-experienced players) compound the issue.

This document proposes a coupled set of changes that address both problems with minimal disruption to established structures:

- **Cap the events at R64 with a parallel B-flight** running in the same weekend, no 4th day required.
- **Drop the CRC tier** (redundant with OLC in practice), bump OLC from 15% to 20% of JN, leave ORC at 50%.
- **Introduce B-flight points at 30% of A-flight** for capped events.
- **Keep best-4 sum** as the counting model. No changes to how points are aggregated.
- **Phase the rollout** through a regional pilot.

Edge-case seeding inputs (BWF tour ranking points, playing-up cross-age-group rankings) are recognized as real concerns but are deliberately deferred to a separate workstream — they require their own design discussion and are not addressed in this proposal. See §10 Open Questions.

The format change is operationally close to neutral on venue load: total match count is essentially identical to today's R128 (128 each, including 3rd/4th playoffs), simultaneous court demand is essentially identical, and per-day match counts at the venue are essentially the same. The player-welfare improvement comes from one fewer round per player (6 vs 7), which eliminates the compressed 3-rounds-in-one-day scenario that today's format forces on deep-run multi-event players.

The proposal is structured to be acceptable as a Phase 1 change. A Phase 2 footnote describes a longer-term direction (quality-of-field multiplier) that would address geography effects and edge cases more elegantly but requires ranking-infrastructure investment.

---

## 1. Problem Statement

### 1.1 Format crisis (ORC)

The current ORC main draw begins at R128 (single elimination) over a 3-day long weekend. With ~700 entries spread across age groups and disciplines, several events — specifically Boys' Singles U13/U15/U17 and Mixed Doubles U13/U15 — frequently exceed 64 entries, triggering R128 brackets.

A R128 single-elim has 7 rounds. Compressed into 3 days, that means players who advance deep cannot avoid 2-3 singles matches on a single day. Multi-event players (singles + doubles + mixed) routinely face **7–9 matches in a single day** during the busy middle days of the weekend.

This produces:
- Extended delays as match dependencies pile up
- Injury risk (particularly for U13/U15 athletes whose load tolerance is lower)
- Withdrawals and walkovers as attrition compounds
- A poor competitive experience that undermines the developmental value of the event

### 1.2 Ranking incentives drive the crowding

Current ranking weights:

| Tier                               | % of JN points | Notes                                      |
| ---------------------------------- | -------------: | ------------------------------------------ |
| JN (Junior National)               |           100% | Once per year, national field              |
| ORC (Open Regional Championship)   |            50% | Once per region per year, draws nationally |
| OLC (Open Lower-tier Championship) |            15% | Open in name, mostly local in practice     |
| CRC (Closed Regional Championship) |            15% | Closed to one region                       |

The 50%-vs-15% gap creates strong pressure for any ranking-conscious player to attend ORC events, regardless of geographic distance, readiness, or match fitness. ORC fields swell to ~700 entries — close to JN itself — and the format cannot absorb that volume.

### 1.3 Counting model and edge cases

The best-4 counting model produces three secondary issues:

1. **Single-peak opportunism**: A player with one strong JN result + three strong ORCs can lock in best-4 early in the season and stop competing without ranking penalty.
2. **No reward for sustained participation**: Playing a 5th or 6th event adds nothing to the ranking unless it improves on the existing best-4.
3. **Edge cases unhandled**: Players competing up an age group hold understated rankings in that division. Players with significant BWF international experience but limited domestic participation enter major events without seeding protection.

### 1.4 The two problems are one problem

The format crisis cannot be solved structurally without addressing the ranking incentives that drive it, and the ranking incentives cannot be addressed in isolation without considering what the format can actually absorb. This proposal treats them as a single design.

---

## 2. Design Goals

In priority order:

1. **Player welfare**: No multi-event player should face a 7–9 match day. Per-day match load must be sustainable.
2. **Inclusion**: All registered players should get to play meaningful, ranking-relevant matches at the events they sign up for.
3. **Operational feasibility**: Host clubs, officials, and volunteers must be able to deliver the new format without doubling court-hours, doubling officiating-hours, or extending to 4 days.
4. **Ranking accuracy**: Rankings should reflect actual competitive strength as closely as the system can produce, with edge cases handled.
5. **Political feasibility**: The change set should be small enough to actually adopt. Big-bang restructuring is out of scope.

### Non-goals

- A full ranking-system rewrite. (Quality-of-field multipliers are noted as Phase 2.)
- Re-balancing the 6-region structure. (Out of scope; might be revisited later.)
- Eliminating the JN/ORC tier hierarchy. (The hierarchy is sound; only the OLC/CRC layer needs simplification.)
- Standardizing the calendar across regions. (Each region retains scheduling autonomy.)

---

## 3. Proposed Design

### 3.1 Format: A-flight / B-flight cap for crunch events

**Crunch events** (events that historically exceed 64 entries):

- Boys' Singles U13
- Boys' Singles U15
- Boys' Singles U17
- Mixed Doubles U13
- Mixed Doubles U15

Crunch designation should be applied to any event projected over 64 entries at registration close, based on prior-year data. The list above is the expected set; the rule is the criterion.

**For crunch events at ORC:**

- **A-flight**: Top 64 by national ranking, entered automatically. Single-elim R64. Full officiating standard.
- **B-flight**: All remaining registrants (capped at 64 — hard cap of 128 total registrants per event). Single-elim R64 with byes if under 64. Reduced officiating standard (roving umpire / self-reporting; full officiating reserved for B-flight QF onward).
- Both flights run Saturday–Monday at the same venue. **No Friday extension.**

For non-crunch events: format is unchanged.

### 3.2 Tier weights

| Tier         | Old % of JN |                 New % of JN | Change                           |
| ------------ | ----------: | --------------------------: | -------------------------------- |
| JN           |        100% |                        100% | unchanged                        |
| ORC A-flight |         50% |                     **50%** | unchanged                        |
| ORC B-flight |         n/a | **15%** (= 30% of A-flight) | new                              |
| OLC          |         15% |                     **20%** | bumped                           |
| CRC          |         15% |                 **dropped** | removed from ranking calculation |

**Rationale:**

- ORC A-flight stays at 50%. The "must attend ORC" pressure is addressed structurally by capping the field and offering B-flight, not by lowering the headline value. Top-ranked players still earn the elite-event premium they should.
- B-flight is set at 30% of A-flight. This places the B-flight winner approximately equal to an A-flight R16 finisher, and approximately 20% above an A-flight R32 finisher. The relationship "winning a bracket beats losing a first match" holds; "tier matters" also holds.
- OLC bumped to 20%. With CRC removed, OLC absorbs the regional development role. The bump satisfies the constraint **2 × OLC ≤ 1 × ORC** with comfortable margin (2 OLC golds = 80% of 1 ORC gold). Players who can't realistically make A-flight are now points-rewarded for staying local instead of grinding to ORC.
- CRC dropped. In practice, OLC fields are also mostly local; the OLC/CRC distinction has not produced meaningfully different competitive experiences. Hosts who currently run CRC may convert to OLC or continue running events as non-ranking developmental tournaments.

**Constraint check** (using U15 BS values, JN 1st = 5,832, ORC 1st = 2,916):

| Comparison                   |   Pts |   Pts | Verdict                                                               |
| ---------------------------- | ----: | ----: | --------------------------------------------------------------------- |
| 2 × OLC gold vs 1 × ORC gold | 2,332 | 2,916 | 2 OLC = 80% of 1 ORC ✓ (bound respected)                              |
| 3 × OLC gold vs 1 × ORC gold | 3,498 | 2,916 | 3 OLC > 1 ORC by 20% ✓ (best-4 should reward extra activity modestly) |
| OLC 1st vs B 1st             | 1,166 |   875 | OLC > B by 33% ✓ (winning a full event > winning second bracket)      |
| OLC 1st vs A R16             | 1,166 | 1,166 | exactly equal ✓ (winning OLC ≈ making A R16)                          |
| B 1st vs A R32               |   875 |   729 | B > A R32 by 20% ✓ (winning bracket > losing first)                   |
| A R16 vs B 1st               | 1,166 |   875 | A R16 > B by 33% ✓ (tier matters)                                     |

### 3.3 Counting model: best-4 sum (unchanged)

Retain the best-4 sum as the ranking score. No change to how points are aggregated.

This proposal does not introduce a participation bonus or other counting-model changes. The "best-4 overweights peaks" concern raised in the original ranking issue is partially addressed by the tier-weight changes (compressing the OLC gap reduces the marginal benefit of a single high-tier result) and the B-flight introduction (a player who is locked-in on best-4 still has incentive to compete because B-flight at later events offers meaningful points). Further counting-model adjustments are deferred — they can be revisited if the tier and format changes alone don't address the concern.

### 3.4 B-flight specification

| Element              | Specification                                                                                    |
| -------------------- | ------------------------------------------------------------------------------------------------ |
| Bracket size         | R64 single-elim (with byes if under 64 registrants in B-flight)                                  |
| Schedule             | Sat–Mon, parallel with A-flight                                                                  |
| Seeding              | By national ranking among B-flight registrants                                                   |
| Officiating standard | Roving umpire (1 per 4 courts) + self-reporting in early rounds; full officiating from QF onward |
| Match format         | Same as A-flight (best of 3 games to 21 rally points)                                            |
| Points               | 30% of A-flight at every position (see point tables, §4)                                         |
| Awards               | Medals/trophies awarded same as A-flight, labeled "B-flight"                                     |
| Eligibility          | Players who fail to make A-flight by national ranking, capped at 64                              |
| Bracket published    | Friday evening (after registration close)                                                        |

### 3.5 Edge cases (BWF and playing-up): deferred

The original ranking issue raised two real edge cases that this proposal does **not** attempt to solve:

- Players with meaningful BWF tour ranking points but limited domestic junior participation
- Players competing up an age group, whose ranking in the older division understates their actual level

These cases were considered. A wildcard / committee-discretion mechanism was proposed and rejected during design discussion: it would add governance complexity, demand a fair public criteria framework, and risk politicization without clearly outperforming a more principled approach.

The recommended path forward is to address these as a separate workstream — a future proposal could:

- Define how BWF tour ranking points should be incorporated as a seeding input for affected players
- Define how cross-age-group ranking should be combined with same-age ranking for playing-up players
- Possibly use a quality-of-field multiplier (see Phase 2 footnote, §12) which addresses both cases as a side-effect

For now, A-flight entry is purely top 64 by national ranking. Edge-case players enter B-flight if their domestic ranking is outside the top 64. This is a known limitation of the Phase 1 proposal.

This deferral is named explicitly in §10 Open Questions and the proposal acknowledges it as a real gap, not a solved problem.

### 3.6 What is *not* changing

- 3-day weekend format (Sat–Mon) is preserved. No 4th day.
- 6-region structure preserved.
- JN format and weighting unchanged.
- Best-of-3 to 21 match format unchanged.
- Calendar autonomy by region preserved.
- Non-crunch events run with current format (no cap, no B-flight).

---

## 4. Reference Point Tables

All three crunch-age tables shown. Numbers are exact arithmetic; final adoption may round to clean values.

### 4.1 U13 Singles / Doubles

| Finish |                     JN | ORC A-flight | ORC B-flight (30% of A) | OLC (20%) |
| ------ | ---------------------: | -----------: | ----------------------: | --------: |
| 1st    |                  3,149 |        1,575 |                     473 |       630 |
| 2nd    |                  2,834 |        1,417 |                     425 |       567 |
| 3rd    |                  2,677 |        1,338 |                     401 |       535 |
| 4th    |                  2,519 |        1,260 |                     378 |       504 |
| 5–8    | 2,362 / 2,047 / 1,732¹ |          984 |                     295 |       393 |
| 9–16   |         1,417 / 1,102² |          630 |                     189 |       252 |
| 17–32  |             945 / 630³ |          394 |                     118 |       158 |
| 33–64  |             472 / 354⁴ |          157 |                      47 |        63 |

### 4.2 U15 Singles / Doubles

| Finish |                     JN | ORC A-flight | ORC B-flight (30% of A) | OLC (20%) |
| ------ | ---------------------: | -----------: | ----------------------: | --------: |
| 1st    |                  5,832 |        2,916 |                     875 |     1,166 |
| 2nd    |                  5,249 |        2,624 |                     787 |     1,050 |
| 3rd    |                  4,957 |        2,479 |                     744 |       991 |
| 4th    |                  4,666 |        2,333 |                     700 |       933 |
| 5–8    | 4,374 / 3,791 / 3,208¹ |        1,823 |                     547 |       729 |
| 9–16   |         2,624 / 2,041² |        1,166 |                     350 |       467 |
| 17–32  |         1,750 / 1,166³ |          729 |                     219 |       292 |
| 33–64  |             875 / 656⁴ |          292 |                      88 |       117 |

### 4.3 U17 Singles / Doubles

| Finish |                     JN | ORC A-flight | ORC B-flight (30% of A) | OLC (20%) |
| ------ | ---------------------: | -----------: | ----------------------: | --------: |
| 1st    |                 10,800 |        5,400 |                   1,620 |     2,160 |
| 2nd    |                  9,720 |        4,860 |                   1,458 |     1,944 |
| 3rd    |                  9,180 |        4,590 |                   1,377 |     1,836 |
| 4th    |                  8,640 |        4,320 |                   1,296 |     1,728 |
| 5–8    | 8,100 / 7,020 / 5,940¹ |        3,375 |                   1,013 |     1,350 |
| 9–16   |         4,860 / 3,780² |        2,160 |                     648 |       864 |
| 17–32  |         3,240 / 2,160³ |        1,350 |                     405 |       540 |
| 33–64  |         1,620 / 1,080⁴ |          540 |                     162 |       216 |

¹ JN reports finer banding at top: 5 / 6 / 7–8. ORC and OLC use the 5–8 banded grouping.
² JN: 9–12 / 13–16. Tier tables: 9–16 banded.
³ JN: 17–24 / 25–32. Tier tables: 17–32 banded.
⁴ JN: 33–48 / 49–64. Tier tables: 33–64 banded.

For U11 and U19 events, current point structures remain unchanged (U11 events do not exceed 64 entries; U19 events are subject to the same crunch criterion if they ever cross the threshold).

---

## 5. Worked Example: BS U15 at South ORC, 100 registrations

### 5.1 Entry mechanics

| Group              |  Count | Entry path                     |
| ------------------ | -----: | ------------------------------ |
| A-flight entry     |     64 | Top 64 by national U15 ranking |
| B-flight           |     36 | All remaining registrants      |
| **B-flight total** | **36** | Bracket: R64 with 28 byes      |

### 5.2 Schedule

| Day      | A-flight (64 players)        | B-flight (36 players)              |
| -------- | ---------------------------- | ---------------------------------- |
| Friday   | (no event activity at venue) | (no event activity at venue)       |
| Saturday | R64 → R32 (2 rounds)         | R64 (mostly byes) → R32 (2 rounds) |
| Sunday   | R16 → QF (2 rounds)          | R16 → QF (2 rounds)                |
| Monday   | SF → F (2 rounds)            | SF → F (2 rounds)                  |

### 5.3 Per-player match load

| Player profile                                           |               Match count over 3 days |
| -------------------------------------------------------- | ------------------------------------: |
| A-flight winner (singles only)                           |                             6 (2/day) |
| A-flight winner across BS + BD + XD (deep run all three) |  up to 18 over 3 days, ~6/day at peak |
| B-flight winner (singles only)                           | 5–6 (R64 byes for top B-flight seeds) |
| Either flight, first-round loss                          |                                     1 |

**Comparison to today's R128 format:**

| Discipline scenario    |             Today (R128, 7 rounds) |         Proposed (R64, 6 rounds) |                           Δ |
| ---------------------- | ---------------------------------: | -------------------------------: | --------------------------: |
| Deep-run, singles only |          7 over 3 days, peak 3/day |        6 over 3 days, peak 2/day |       −1 match, peak day −1 |
| Deep-run, BS + BD + XD | up to 21 over 3 days, peak 7–9/day | up to 18 over 3 days, peak 6/day | −3 total, peak day −1 to −3 |

The improvement is concentrated on the **brutal day** — typically Sunday or Monday today, when 3 rounds compress into a single day for deep-run players. With 6 rounds in 3 days, scheduling can hold per-discipline match count to 2/day, eliminating the worst compressions.

### 5.4 Points outcome examples

| Finish | A-flight pts (U15) | B-flight pts (U15) |
| ------ | -----------------: | -----------------: |
| 1st    |              2,916 |                875 |
| 2nd    |              2,624 |                787 |
| 3rd    |              2,479 |                744 |
| 4th    |              2,333 |                700 |
| 5–8    |              1,823 |                547 |
| 9–16   |              1,166 |                350 |
| 17–32  |                729 |                219 |
| 33–64  |                292 |                 88 |

---

## 6. Player Journey Scenarios (BS U15)

### 6.1 Player ranked #25 nationally

| Choice                 | Outcome               |
| ---------------------- | --------------------- |
| Register for South ORC | Direct A-flight entry |
| Realistic finish       | A R16 → R8            |
| Realistic points       | 1,166–1,823           |

No change from today's experience for this player except that the format is less brutal day-to-day.

### 6.2 Player ranked #80 nationally

| Choice                           | Travel cost |      Best-case pts | Likely-case pts |
| -------------------------------- | ----------- | -----------------: | --------------: |
| Travel to ORC, lands in B-flight | High        |     875 (B winner) |          70–280 |
| Stay local for OLC               | Low         | 1,166 (OLC winner) |         117–467 |

**OLC is now the rational choice** for this player: higher ceiling AND higher floor, lower travel cost. The "everyone must attend ORC" pressure is structurally relieved.

### 6.3 Player ranked #150 nationally with BWF junior experience

Today: low domestic ranking → poor seed at any ORC they enter. Disadvantaged despite demonstrated competitive strength.

Under this proposal: **not directly addressed.** With A-flight entry strictly by domestic top-64, this player likely lands in B-flight at any ORC they attend. The proposal acknowledges this as a real gap (see §3.5 and §11) and recommends addressing BWF tour ranking points as a seeding input via a separate workstream.

### 6.4 Player competing up (U15-eligible playing in U17)

Today: their U17 ranking is artificially low because they have few U17 results. Seeded poorly in U17 events.

Under this proposal: **not directly addressed.** Same as the BWF case — their U17 domestic ranking is what determines A-flight entry. The proposal recommends a separate workstream to define how cross-age-group ranking should be combined for playing-up players.

### 6.5 Best-4 sum, full season examples

| Profile                        | Best-4 sum (U15) |
| ------------------------------ | ---------------: |
| 1 ORC gold + 3 OLC golds       |            6,414 |
| 4 ORC R16 finishes             |            4,664 |
| 4 OLC golds                    |            4,664 |
| 2 OLC golds + 2 B-flight golds |            4,082 |
| 1 ORC gold (only event)        |            2,916 |

Best-4 sum is unchanged from current methodology. The OLC bump and B-flight introduction are what shift relative outcomes between profiles.

---

## 7. Operational Impact

### 7.1 Match count comparison

| Format                            | Total matches | Rounds for winner |
| --------------------------------- | ------------: | ----------------: |
| Current R128 single bracket       |           128 |                 7 |
| Proposed R64 A + R64 B (parallel) |           128 |            6 each |

Total matches are essentially identical (128 each, including 3rd/4th place playoffs). The R128 reaches that total in 7 rounds; the parallel R64+R64 reaches the same total in 6 rounds because the final round runs in both brackets concurrently.

### 7.2 Per-round simultaneous match count

| Round | R128 single | R64 A + R64 B parallel |
| ----- | ----------: | ---------------------: |
| 1     |          64 |           32 + 32 = 64 |
| 2     |          32 |           16 + 16 = 32 |
| 3     |          16 |             8 + 8 = 16 |
| 4     |           8 |              4 + 4 = 8 |
| 5     |           4 |              2 + 2 = 4 |
| 6     |           2 |              2 + 2 = 4 |
| 7     |           2 |                      — |

Simultaneous match counts are identical for rounds 1–6. Peak court demand and peak officiating demand are unchanged.

### 7.3 Per-day distribution

Both formats need to fit their rounds into 3 days. Plausible scheduling:

| Day      |            R128 single (7 rounds) |      R64 + R64 parallel (6 rounds each) |
| -------- | --------------------------------: | --------------------------------------: |
| Saturday |           96 matches (R128 + R64) | 96 matches (R64+R32 in A, R64+R32 in B) |
| Sunday   |       28 matches (R32 + R16 + QF) |   24 matches (R16+QF in A, R16+QF in B) |
| Monday   | 4 matches ( SF + Final & 3rd/4th) |      8 matches (SF + F in both A and B) |

**Per-day match counts are essentially the same.** The total court-hours and officiating-hours required at the venue do not increase under the proposed format.

Where the player-welfare improvement actually comes from:

- **Per-player rounds drops from 7 to 6.** Deep-run players play one fewer match overall.
- **Monday compression eases.** Today, deep-run players play QF + SF + F on Monday (3 matches per discipline). Under the proposed format, Monday is just SF + F (2 matches per discipline). For multi-event players, that translates to 2-3 fewer matches on the worst day.
- **No round is forced into a single-day triple.** With 6 rounds in 3 days, scheduling can hold per-discipline match count to 2/day. With 7 rounds in 3 days, at least one day must hold 3 rounds — that compression cannot be avoided.

So the proposal is operationally **roughly neutral on venue load** and **meaningfully better on per-player day load**.

### 7.4 What hosts must actually plan for

- **Two finals on Monday** instead of one. Two presentation ceremonies. Two sets of medals.
- **Bracket scheduling complexity**: two brackets to publish, two sets of pairings to manage.
- **Awards inventory**: medals/trophies for B-flight (similar units to A-flight).
- **Reduced officiating in B-flight**: roving umpires need to be briefed on coverage protocol. Self-reporting forms or scoring apps for early rounds.

The operational ask is meaningfully smaller than "extend to 4 days" or "double court count." It is concrete and bounded.

### 7.5 Friday is *not* required

The proposal explicitly does not require Friday court time at the venue. All play (A and B brackets) runs Saturday–Monday. Bracket publication happens Friday evening once registration closes — no on-court Friday activity.

This was a deliberate design decision after considering and rejecting Friday-morning qualifier mechanics. The qualifier idea would have effectively created a 4-day tournament, conflicting with the original constraints around school/work absence and host operating costs.

---

## 8. Phased Rollout

### Phase 1 (proposed for next applicable season)

- **Pilot in one region with one or two crunch events** (suggested: BS U15 in the region with the highest historical ORC entry counts).
- Apply tier reweighting (OLC to 20%, CRC dropped) for that region's ORC.
- Apply A/B-flight format to piloted events.
- Document operational outcomes (match counts, host feedback, player feedback).

### Phase 2 (following season, conditional on Phase 1 outcomes)

- Expand A/B-flight format to all 5 crunch events nationally.
- Apply tier reweighting nationally.
- Optionally introduce **quality-of-field multiplier** (per-event field-strength adjustment). This addresses geography effects and edge cases more elegantly but requires ranking-infrastructure investment. Scoping work begins in Phase 2 if it is prioritized.
- Begin separate workstream on edge-case seeding inputs (BWF tour ranking, playing-up cross-age-group ranking).

### Phase 3+ (longer term, out of scope for this proposal)

- Region rebalancing if data supports it
- Calendar coordination across regions
- Composite seeding model incorporating BWF and adult rankings

---

## 9. Risks and Mitigations

| Risk                                                                    | Likelihood | Impact | Mitigation                                                                                                                                     |
| ----------------------------------------------------------------------- | ---------- | ------ | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Hosts push back on running two parallel brackets                        | Medium     | Medium | Pilot first; document that simultaneous court demand is ~unchanged; offer reduced officiating standard for B-flight                            |
| Officials push back on Monday workload (two finals)                     | Low–Medium | Low    | One additional final per crunch event is bounded; final officiating is rotated                                                                 |
| Players ranked 65+ at a crunch event feel relegated to "second class"   | Medium     | Medium | Award-equivalence and meaningful B-flight points; clear communication that B-flight is real competition                                        |
| BWF / playing-up players land in B-flight despite demonstrated strength | Medium     | Medium | Acknowledged limitation of Phase 1; addressed via separate edge-case workstream (see §3.5)                                                     |
| Dropping CRC orphans some host clubs that ran them                      | Low        | Low    | Hosts can convert to OLC or continue as non-ranking developmental events                                                                       |
| OLC bump to 20% is too generous and inflates rankings                   | Low        | Low    | The 2-OLC-gold-equals-80%-of-1-ORC-gold check holds; 3 OLC golds beat 1 ORC gold by only 20%, which is the intended best-4 reward for activity |
| Pilot region's experience doesn't generalize                            | Medium     | Medium | Phase 1 explicitly observational; Phase 2 calibration based on data                                                                            |

---

## 10. Open Questions

These are not blockers for adoption but should be answered as part of implementation:

1. **Who has authority to approve tier reweighting and format changes?** USAB high-performance committee, board, or regional directors? The proposal needs a clear approval path.
2. **What is the timing of the Phase 1 pilot relative to the existing season calendar?** Implementation requires regions to opt in and host clubs to plan.
3. **How will B-flight points be communicated to coaches and parents during the pilot season?** The new structure needs a public-facing explainer, not just an internal rule change.
4. **How should BWF tour ranking points be incorporated as a seeding input?** This is a real edge-case gap that the current proposal does not address. Requires a separate design discussion: what BWF-tier threshold qualifies, how to weight against domestic ranking, what to do for players in disciplines BWF doesn't track at junior level.
5. **How should playing-up cross-age-group ranking be combined with same-age ranking?** Same edge-case workstream as item 4. Requires defining how a U15-eligible player's U15 ranking should inform their U17 seeding.
6. **Should the crunch criterion be event-by-event annually**, or a fixed list of events? An annual recalibration based on prior-year data is more flexible but harder to communicate.
7. **What happens to OLC points already earned in the current season** if Phase 1 includes a tier reweight mid-season? Likely answer: re-compute at season end using new weights. Needs explicit policy.
8. **Does the proposal require any change to the registration/seeding software** USAB uses? Vendor capabilities should be confirmed.

9. **Should USAB drop or reduce its 30% revenue cut on OLC events to amplify the redistribution effect?** The OLC tier-weight bump in this proposal (15% → 20% of JN) is intended to redirect ranking-conscious participation away from saturated ORCs and toward locally-run OLCs. That redistribution only fully works if the supply of OLC events grows to match the new demand, which depends on host economics. If USAB's standard 30% cut on tournament revenue is reduced or removed for OLC specifically, hosts capture more of the upside from larger fields, OLC becomes more attractive to run, and the player-side and host-side incentives point the same direction. Without this lever, the reform improves OLC's attractiveness to *players* but leaves host economics unchanged, and the supply of OLC events may not expand to absorb the redirected demand. This question sits inside the broader financial-sustainability concern raised in [`../issue-financial-sustainability-membership-hosting-officiating.md`](../issue-financial-sustainability-membership-hosting-officiating.md) and may be best addressed jointly with that workstream. Linked issues: [`../issue-orc-format-match-load-and-tournament-length.md`](../issue-orc-format-match-load-and-tournament-length.md), [`../issue-junior-ranking-points-and-seeding.md`](../issue-junior-ranking-points-and-seeding.md).

---

## 11. Stakeholder Impact Summary

| Stakeholder                          | Impact                                                                                                                                                                                   | Net assessment                                          |
| ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| Top-ranked players (top 64)          | A-flight experience similar to today, with shorter event (6 rounds vs 7) and better daily distribution. ORC retains its 50% prestige weight.                                             | Positive                                                |
| Mid-ranked players (#65–128)         | Now have B-flight pathway with meaningful points (15% of JN). Lower travel pressure to ORC since OLC is more attractive.                                                                 | Positive                                                |
| Lower-ranked / new players           | Same OLC opportunities, now valued at 20%. Path through B-flight if they choose to travel to ORC.                                                                                        | Slightly positive                                       |
| Playing-up / BWF-experienced players | Not directly addressed in this proposal. Will land in B-flight unless their domestic ranking is top 64. Acknowledged as a real gap; deferred to a separate edge-case seeding workstream. | Neutral (no improvement, no regression)                 |
| Host clubs                           | Two brackets to manage at crunch events instead of one R128. Total matches and court-hours essentially unchanged. Operational complexity slightly higher.                                | Neutral to slightly negative; manageable                |
| Officials and volunteers             | Total officiating-hours essentially unchanged. Two finals on Monday for crunch events. Reduced officiating standard for B-flight early rounds eases load.                                | Neutral                                                 |
| Coaches                              | Need to communicate B-flight value to families. Playing-up logic is more straightforward.                                                                                                | Slightly positive                                       |
| Regions running CRC events           | Choice to convert to OLC or run as non-ranking developmental events.                                                                                                                     | Neutral; preserves choice                               |
| USAB governance                      | Phase 1 pilot is a bounded change; data-driven scaling.                                                                                                                                  | Positive (low-risk pathway to a meaningful improvement) |

---

## 12. Phase 2 Footnote: Quality-of-Field Multiplier

A more elegant longer-term mechanism: each event's points are scaled by the actual strength of the field that attended.

**Mechanism**: Each event's awarded points = base tier points × field-strength factor, where field-strength factor is computed from the ranking points of the top-N entrants relative to a reference baseline.

**What this would solve**:

- Geography effects: a strong-attendance ORC pays more than a weak-attendance one, regardless of region
- Edge cases: a playing-up player or BWF-experienced player who beats strong opponents earns proportionally more, addressed automatically rather than via separate workstream
- JN/ORC density differential: encoded automatically rather than via static tier multiplier

**Why this is Phase 2, not Phase 1**:

- Requires ranking-infrastructure investment (compute pipeline, possibly software vendor changes)
- Communication burden: families and coaches need to understand a new dynamic mechanism
- Chicken-and-egg problem at season start (initial weights based on prior-season data)
- Phase 1 changes alone meaningfully address the immediate format crisis; the additional accuracy benefits of quality-of-field can wait

This footnote exists to signal that the spec authors see the full longer-term direction, and Phase 1 is a deliberate pragmatic step rather than a final answer.

---

## 13. Mapping to Existing Community Voice Issues

This proposal addresses the design space raised in two existing issue documents:

- [`../issue-junior-ranking-points-and-seeding.md`](../issue-junior-ranking-points-and-seeding.md)
  - Item 1 (best-4 overweight peaks): partially addressed by tier-weight compression (smaller marginal benefit from any single high-tier result) and B-flight (continued incentive to compete after best-4 is locked). Counting model itself is unchanged.
  - Item 2 (large tier differentials): addressed by OLC bump (15→20%) and B-flight introduction
  - Item 3 (seeding edge cases — BWF, playing-up): **deferred to separate workstream.** Acknowledged as a real gap; not solved by this proposal.

- [`../issue-orc-format-match-load-and-tournament-length.md`](../issue-orc-format-match-load-and-tournament-length.md)
  - The 7–9 matches/day problem: addressed by R64 cap + B-flight, no 4th day required
  - The capping fairness concern: addressed by B-flight + OLC reweight (everyone registered still plays in some bracket)
  - The 4-day cost concern: explicitly avoided by design

Both issue documents may be updated to reference this proposal as the recommended response. A condensed version of this design (1–2 pages) could be added to the issue files as a community proposal for review.
