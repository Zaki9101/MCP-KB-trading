---
id: RISK_TIER_LADDER_SHARES
kind: risk
scope: long-lane-a
tags: [RISK, ANY, tiers]
sources: [BLUEPRINT_HANDBOOK p.238, BLUEPRINT_HANDBOOK p.455, BLUEPRINT_HANDBOOK p.456, BLUEPRINT_HANDBOOK p.715]
status: book-stated
conflicts: none
---
Conditions: Sizing any trade or add. Tier = percent of the daily stop.
Entry: Tier1 5%, Tier2 10%, Tier3 15%, Tier4 20% of the daily stop (Tier5 25% is implied, not stated). The ladder sizes confirmed adds inside one trade; it is not one tier per attempt, and risk never rises after a stop-out.
Stop: Shares = tier dollar risk / stop distance.
Target and exits: Not applicable.
Time: Any.
Refuse if: Raising the tier on a second attempt.
