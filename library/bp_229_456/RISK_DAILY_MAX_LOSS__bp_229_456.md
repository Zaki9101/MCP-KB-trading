---
id: RISK_DAILY_MAX_LOSS__bp_229_456
kind: risk
scope: long-lane-a
tags: [RISK, ANY, daily-stop]
sources: [BLUEPRINT_HANDBOOK p.451, BLUEPRINT_HANDBOOK p.452, BLUEPRINT_HANDBOOK p.453, BLUEPRINT_HANDBOOK p.716]
status: conflict
conflicts: CAM p.100-101 via BLUEPRINT_HANDBOOK p.452: daily loss = daily profit target; OGT p.297: 50% of the last best day for experienced traders; CP p.118: 10% of the account
---
Conditions: Set before the open and enforce at the broker.
Entry: Not applicable.
Stop: Daily max loss at most 50% of your median gross winning day (not the best day). Fixed dollar examples ($100-$300) apply only if lower than your figure. Period stop: 30% of the limit in any window (open, midday) in which you are down.
Target and exits: When the daily stop is hit, stop. No exceptions, no 'one more'.
Time: Before the open.
Refuse if: Trading past the daily stop.
