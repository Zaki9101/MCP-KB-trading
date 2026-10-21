---
id: RISK_STOPS_ON_EVERY_LOT
kind: risk
scope: long-lane-a
tags: [RISK, ANY, every-lot]
sources: [BLUEPRINT_HANDBOOK p.422, BLUEPRINT_HANDBOOK p.436, BLUEPRINT_HANDBOOK p.713]
status: conflict
conflicts: PB p.175 via BLUEPRINT_HANDBOOK p.422: alerts and manual exit because HFTs may see resting stops
---
Conditions: Multi-lot position, size above the starter lot, or news risk live.
Entry: Not applicable.
Stop: Automatic stop on every lot. Manual exit only on starter size while you are watching the screen. Stop-limits can fail to fill in a spike; prefer a stop far enough beyond the level.
Target and exits: The book's case: an unprotected lot covered more than 10c worse than planned when news hit.
Time: Any.
Refuse if: Any lot above starter size without a resting stop.
