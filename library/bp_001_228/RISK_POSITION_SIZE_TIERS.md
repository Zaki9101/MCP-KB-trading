---
id: RISK_POSITION_SIZE_TIERS
kind: risk
scope: long-lane-a
tags: [RISK, ANY, sizing]
sources: [BLUEPRINT_HANDBOOK p.008, BLUEPRINT_HANDBOOK p.009, BLUEPRINT_HANDBOOK p.179, BLUEPRINT_HANDBOOK p.180]
status: conflict
conflicts: BLUEPRINT_HANDBOOK p.163 (CAM): max loss per idea about 25% of the daily profit target. Ch.19 p.716: at most 25% of the daily stop.
---
Conditions: Shares = tier dollar risk / stop distance. First lot = Tier1 = 5% of the daily stop (GMan ladder: Tier2 10%, Tier3 15%, Tier4 20%; daily stop $5,000 gives Tier1 $250). All lots of one idea: hard ceiling 25% of the daily stop. Default position dollars by price band: $1,500 for $8-$20, $1,000 for $2-$8, $500 for $1-$2; the stop and its cap still govern risk.
Entry: Add only to a position already working, with the stop at breakeven or behind the new swing; add smaller when far from support.
Stop: Every lot carries a stop.
Target and exits: n/a.
Time: Any time.
Refuse if: All-in trades. Second try larger than half the first lot.
