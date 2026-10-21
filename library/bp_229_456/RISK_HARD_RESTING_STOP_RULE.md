---
id: RISK_HARD_RESTING_STOP_RULE
kind: risk
scope: long-lane-a
tags: [RISK, ANY, stop-type]
sources: [BLUEPRINT_HANDBOOK p.268, BLUEPRINT_HANDBOOK p.440, BLUEPRINT_HANDBOOK p.713]
status: conflict
conflicts: CEP p.77 and p.103 via BLUEPRINT_HANDBOOK p.440: discretionary hold to -0.07 behind a massive bid; OGT mental tape stop
---
Conditions: Choosing between a resting stop and a mental stop.
Entry: Not applicable.
Stop: Resting stop on 100% of size when above Tier1, when holding through news, if you have ever exceeded a stop, or while below the size-up gates. A tape-based mental stop only on starter size in liquid names, with a hard catastrophic stop behind it. Close-based stops (bar close through VWAP or an EMA) are exit signals, not stops.
Target and exits: Broker-side max daily loss and position size are always set.
Time: Any.
Refuse if: Any position above Tier1 without a resting stop.
