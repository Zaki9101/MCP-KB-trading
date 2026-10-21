---
id: RISK_DAILY_MAX_LOSS__bp_457_684
kind: risk
scope: long-lane-a
tags: [RISK, ANY, daily-loss]
sources: [BLUEPRINT_HANDBOOK p.463, BLUEPRINT_HANDBOOK p.476, BLUEPRINT_HANDBOOK p.477, BLUEPRINT_HANDBOOK p.495, BLUEPRINT_HANDBOOK p.716]
status: conflict
conflicts: BLUEPRINT_HANDBOOK p.477 (NB p.89-90 sim): $150 daily max in Month 1; p.463: CAM daily loss = daily profit target, OGT 50% of best day for experienced traders
---
Conditions: Set before the open and enforce at the broker.
Entry: no entry once the limit is hit.
Stop: daily max loss at most 50% of your median gross winning day (not the best day). Period stop: 30% of that limit in any window (open, midday) in which you are down. Small account: 10% of the account (e.g. $100 on $1,000), capped lower by the median-day formula if that is smaller. A single idea risks at most 25% of the daily stop.
Target and exits: hitting the limit closes everything for the day.
Time: whole session.
Refuse if: trading past the daily max loss: never.
