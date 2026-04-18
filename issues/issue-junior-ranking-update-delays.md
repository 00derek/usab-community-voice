## Issue
Junior rankings are not updated on the promised monthly cadence, causing ongoing frustration among families who rely on them for tournament seeding, JSE/JN selection eligibility, and college recruitment visibility. The gap between USAB's stated commitment and actual delivery points to an unresolved process or resourcing problem — and the lack of automation makes it fragile and volunteer-dependent.

**Tags**: `transparency` `rankings` `junior` `operations` `automation` `community`

## Context
Rankings are not an abstract metric for junior players and their families — they directly affect:
- **Seeding and draw placement** at sanctioned tournaments
- **Selection eligibility** for JSE and Junior Nationals
- **College recruitment** visibility, where coaches actively monitor national junior rankings

USAB has committed to monthly ranking updates, but recurring delays mean families are often making tournament entry and travel decisions against stale data. When updates are weeks or months late, players may be seeded incorrectly, miss selection thresholds they had in fact crossed, or present outdated rankings to college programs.

The pattern of repeated delays despite a stated commitment suggests the problem is structural, not incidental. A monthly cadence that depends entirely on manual effort and a single point of ownership will fail whenever that person is unavailable, overloaded, or changes roles. Without automation or a documented fallback process, the same delays will recur indefinitely.

The junior community has raised this concern repeatedly. Continued non-delivery without a visible corrective plan damages trust in USAB's operational reliability and signals that junior program infrastructure is under-resourced.

## Potential Options

> The options below are illustrative examples only and are not necessarily the best or final solutions. Better options may come from the community, clubs, or USAB directly.

- **Option A — Audit and document the current process end-to-end**: Before proposing solutions, map the full ranking update pipeline — how tournament results are collected, validated, calculated, and published — and identify exactly where delays originate. This is a prerequisite for any durable fix.

- **Option B — Automate tournament result ingestion**: If results from sanctioned tournaments (e.g., via TournamentSoftware or BadmintonUS) can be pulled programmatically, automate the data collection step so rankings can be calculated without waiting for manual data entry. Removes the most common bottleneck.

- **Option C — Assign dedicated ownership with a published update calendar**: Designate a specific role (staff or volunteer lead) responsible for ranking updates, publish a calendar of update dates for the year, and create a visible accountability mechanism — e.g., a status page showing last updated date and next scheduled date. Families should never have to guess when rankings were last refreshed.


- **Option D — Implement a fully automated pipeline with guaranteed SLA**: Create an automated process with a guaranteed maximum turnaround time after a tournament concludes. If the underlying event-result systems support it, automated ingestion and publication should be a realistic medium-term goal.

## Open Questions

- ✓ **Addressed (Apr 18):** *What is the current end-to-end process?* — Manual, multi-handoff: Justin Rogers + Ty + Mary. Starts last week of month. Documented informally but not publicly.
- ✓ **Addressed (Apr 18):** *Who owns the ranking update process?* — Justin Rogers (process owner), working with Ty and Mary.
- ✓ **Addressed (Apr 18):** *Is there a known automation timeline?* — Two vendors under evaluation; 4–6 months expected; goal of post-tournament automation by summer 2026.
- ✓ **Addressed (Apr 18):** *Are there known technical barriers?* — Playup rule handling and duplicate user IDs (one player had 3 accounts) are the main complications.
- Where do delays most commonly occur — data collection, calculation, approval, or publication?
- How are tournament results from sanctioned events submitted and ingested — standard format or varies?
- Has USAB internally documented an SLA or accountability mechanism for the monthly commitment?
- How many formal complaints or community inquiries about ranking delays has USAB received?


## Status

**Current status**: `open`
**Last updated**: 2026-04-18
**Community feedback**: [Submit feedback](https://docs.google.com/forms/d/e/1FAIpQLScrp_rzg7bhIJdpnF74Te7dnxWacTYk8plZI045A96DvILNgQ/viewform)

## USAB Response

### Apr 18, 2026 — Community Feedback Meeting

Justin Rogers described the current process as manual and multi-handoff, inherited from Trenton's departure. The team now starts the monthly run during the last week of each month to hit a first-of-month target. One delay occurred in February 2026 when a tournament overlapped the month boundary. John stated a goal of full automation by summer 2026, with two vendors under evaluation; expected implementation timeline is 4–6 months. Community members (including two independent developers) have already built ranking scrapers from public TournamentSoftware data and offered technical consultation.

- Rankings are updated monthly; process starts last week of each month to hit first-of-month target
- February 2026 was delayed due to a tournament overlapping the month start; most recent months on schedule
- Two vendors being evaluated; one vendor quoted ~6 months, John expects to finalize choice after upcoming Europe trip
- Target: automated ranking update after every tournament, not just monthly
- Known critical requirements for vendor: playup rule handling, deduplication of players with multiple accounts
- Community engineers have built working ranking scrapers from public data and are available for technical consultation (not as primary vendors)

## Action Items

→ [View in action items tracker](../action-items.md)
