---
id: RISK_STOP_BEFORE_ENTRY_RESTING
kind: risk
scope: long-lane-a
tags: [RISK, ANY, stop-type]
sources: [BLUEPRINT_HANDBOOK p.463, BLUEPRINT_HANDBOOK p.482, BLUEPRINT_HANDBOOK p.491, BLUEPRINT_HANDBOOK p.493, BLUEPRINT_HANDBOOK p.506, BLUEPRINT_HANDBOOK p.713]
status: conflict
conflicts: BLUEPRINT_HANDBOOK p.491 (PB p175-176): HFTs may see resting stops, so an alert plus manual exit can be better (unverified 2012 claim)
---
Conditions: Every trade.
Entry: write the stop price and order type before the entry; then size from that distance.
Stop: default is a resting stop order. Hard stop on 100% of size when size is above Tier1, when holding through news risk, if you have ever exceeded a stop, or below the size-up gates. Alert plus manual exit only if you are at the screen and exit the instant it triggers, every time. Moving or removing the stop needs a written, logged override. Broker-side max daily loss and position size always set.
Target and exits: not stated.
Time: any.
Refuse if: no stop number = no trade.
