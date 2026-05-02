## Issue
The current junior ranking and seeding system may not consistently reflect player quality entering major events. A best-4 counting model, large point differentials between event tiers, and limited handling of certain seeding edge cases can all affect who is rewarded, who is seeded, and how accurately rankings reflect competitive strength.

**Tags**: `ranking` `selection` `junior` `high-performance` `governance`

## Context
Rankings serve more than one function in the junior system. They influence seeding, shape access to major events, and help communicate who is performing well over the course of a season. Because they carry that much weight, the design of the points system matters.

The current concern has several parts:

**1. Best-4 counting may overweight peak results**
Counting only the best 4 results may allow a player with one or two strong results at high-value events to outrank a player with more consistent performance across a broader season. It also reduces incentive to continue competing once a player's top results are already locked in.

**2. Large tier differentials may amplify geography and access effects**
If JN and ORC events carry substantially more value than OLC or CRC events, players who can attend those higher-value events more often may accumulate points faster than equally skilled players in regions with fewer such opportunities. That can make rankings partly a reflection of access as well as performance.

**3. Current seeding inputs may miss important edge cases**
Two examples arise repeatedly in discussion:
- Players competing up in an older age group may have rankings in that division that understate their actual level
- Players with meaningful BWF international experience but limited domestic junior participation may enter with little or no domestic ranking protection despite being strong competitors

These issues do not necessarily mean the system is fundamentally unsound. They do suggest it should be reviewed to determine whether it is still aligned with the competitive and developmental goals of the junior pathway.

## Potential Options

> The options below are illustrative examples only and are not necessarily the best or final solutions. Better options may come from the community, clubs, or USAB directly.

- **Option A — Rebalance ranking point differentials across event tiers**: Reduce the gap between JN, ORC, and OLC/CRC point awards so rankings better reflect sustained performance across the season and are less dependent on access to a small number of high-value events.

- **Option B — Increase the number of counting events**: Raise the cap from best 4 to best 6 or best 8 events. This would reward season-long consistency and preserve incentive for continued participation, though it should be reviewed alongside event-tier weighting so it does not simply magnify existing access differences.

- **Option C — Refine seeding criteria for age-group crossover players**: Adjust seeding inputs so players competing up an age group are evaluated with more context than their ranking in that division alone.

- **Option D — Incorporate BWF ranking points into seeding or selection inputs**: Use BWF points as a supplementary input, tiebreaker, or partial composite factor for players with international competition records. This would require a clear methodology for players without BWF data.

- **Option E — Develop a composite ranking or selection score**: Rather than relying on a single metric, define a weighted model that combines domestic ranking points, event performance, and possibly international data. This is more complex to administer, but may better reflect overall player strength.

## Open Questions

- What are the current point values across JN, ORC, OLC, and CRC, and when were those differentials last reviewed?
- How many sanctioned events do competitive junior players typically complete in a season, and how much would rankings change under a best-6 or best-8 model?
- How often do age-group crossover players or internationally active players enter major junior events with seedings that the community views as misleading?
- If BWF points are incorporated, how should USAB handle players with no international record so the system remains fair?
- Are rankings intended primarily to reward seasonal participation, estimate player strength, determine event access, or do all three? If all three, should a single points system be carrying all of those functions?
- Which body within USAB has authority to revise ranking and seeding methodology, and what evidence would it need to justify a change?

## Community Proposal — May 1, 2026

A community-drafted design proposal addresses this issue jointly with the related ORC format issue (`issue-orc-format-match-load-and-tournament-length.md`). Key recommendations on the ranking side:

- **Bump OLC weighting** from 15% to 20% of JN. Compresses the tier gap that drives must-attend pressure on ORC. Respects the constraint that 2 OLC golds should not outweigh 1 ORC gold (at 20%, 2 OLC = 80% of 1 ORC).
- **Drop CRC tier** from ranking calculation. In practice OLC and CRC have similar local-mostly fields; the distinction has not produced meaningfully different competitive outcomes. Hosts can convert CRC events to OLC or run them as non-ranking developmental events.
- **Keep ORC at 50% of JN**. The "must attend" pressure is addressed via format change (capping + B-flight at the related ORC format issue), not by lowering the headline weight.
- **Counting model unchanged.** Best-4 sum is retained as-is. The proposal does not introduce a participation bonus or any other change to how points are aggregated. A counting-model adjustment was considered and deferred — it can be revisited as a follow-on if the structural changes prove insufficient.
- **Edge cases (BWF, playing-up) deferred to a separate workstream.** A-flight entry under the companion format proposal is purely top 64 by national ranking. The proposal authors considered a wildcard / committee-discretion mechanism for handling players whose level exceeds their domestic ranking and decided against it: it would add governance complexity (public criteria framework, appeals path, ongoing committee workload, politicization risk) without clearly outperforming a more principled approach. These cases are recognized as real and are scoped to a future proposal — see Open Questions.

How each item from the original Context section is addressed:

| Concern | Proposal addresses by |
|---|---|
| 1. Best-4 overweights peaks | **Partially addressed.** Tier-weight compression (OLC 15→20%) reduces the marginal value of any single high-tier result; B-flight introduction gives players who are locked-in on best-4 a reason to keep competing because B-flight at later events offers meaningful points. The counting model itself is unchanged. |
| 2. Tier differentials amplify access effects | OLC bump (15→20%) compresses the gap; B-flight introduction (covered in companion issue) gives traveled players a second-bracket alternative at the same weight as OLC. |
| 3. Edge cases unhandled (BWF, playing-up) | **Not addressed; deferred to a separate workstream.** Acknowledged as a real gap in the Phase 1 proposal. A future proposal needs to define how BWF tour ranking points should be incorporated as a seeding input and how cross-age-group ranking should combine with same-age ranking for playing-up players. Until that work happens, edge-case players whose domestic ranking is outside the top 64 will land in B-flight at crunch events. |

Full design including point tables, worked examples, and rollout plan is at [`orc-and-ranking-reform/usab-junior-orc-and-ranking-reform.md`](./orc-and-ranking-reform/usab-junior-orc-and-ranking-reform.md).

## Status

**Current status**: `community-proposal-drafted`
**Last updated**: 2026-05-01
**Community feedback**: [Submit feedback](https://docs.google.com/forms/d/e/1FAIpQLScrp_rzg7bhIJdpnF74Te7dnxWacTYk8plZI045A96DvILNgQ/viewform)

## USAB Response

### Apr 18, 2026 — Community Feedback Meeting

The ranking seeding discussion surfaced two specific concerns. First, the current system does not incorporate world junior or adult rankings for seeding at selection events — players who compete internationally but have limited domestic participation hold no seeding protection despite demonstrated competitive level. Second, Cora confirmed the playup rule (where a player has points in two age groups) is a known source of referee-level confusion about which ranking to apply. Both issues are acknowledged requirements for any new automation vendor. The seeding input question has been routed to the HPC via the selection format discussion.

- World junior and adult rankings should be considered as seeding inputs for JSE — raised as community ask, not yet formally adopted
- Playup rule handling: players with points in two age groups create ambiguity about which ranking applies for seeding; known issue for referees
- Automation vendor requirement: must handle playup rule and duplicate user IDs
- Seeding methodology review will follow from HPC selection format discussion

## Action Items

→ [View in action items tracker](../action-items.md)
