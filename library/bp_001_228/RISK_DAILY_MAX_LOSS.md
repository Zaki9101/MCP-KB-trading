---
id: RISK_DAILY_MAX_LOSS
kind: risk
scope: long-lane-a
tags: [RISK, ANY, daily-loss]
sources: [BLUEPRINT_HANDBOOK p.008, BLUEPRINT_HANDBOOK p.009, BLUEPRINT_HANDBOOK p.195]
status: conflict
conflicts: BLUEPRINT_HANDBOOK p.195 (NB): daily max loss $200 (and $150 in a training plan). Ch.19 p.716: at most 50% of the median gross winning day.
---
Conditions: Daily max loss = at most 50% of your median gross winning day, set and enforced at the broker before the open, with a 30% period stop.
Entry: n/a.
Stop: n/a.
Target and exits: Hitting the daily max loss closes everything and ends the day.
Time: Set before the open.
Refuse if: Trading past the daily stop.
