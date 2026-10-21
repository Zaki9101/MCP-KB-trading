---
id: RISK_STOP_BEFORE_ENTRY_CAPS
kind: risk
scope: long-lane-a
tags: [RISK, ANY, stop]
sources: [BLUEPRINT_HANDBOOK p.008, BLUEPRINT_HANDBOOK p.009, BLUEPRINT_HANDBOOK p.081, BLUEPRINT_HANDBOOK p.179, BLUEPRINT_HANDBOOK p.221, BLUEPRINT_HANDBOOK p.228]
status: conflict
conflicts: BLUEPRINT_HANDBOOK p.221 and p.211 (TR): base and open-break stops of 25c (30c rare), Ex17 stop 29.69 on a 30.00 trigger; p.179 (PB) LNKD risk about 50c. Ch.19 p.713 caps govern.; source says 'cut shares' for over-cap stops; v1 rule is skip (R03)
---
Conditions: No stop number = no trade. Write the stop price and type before entry, at the level that proves the idea wrong (structure).
Entry: Size from the stop: shares = tier dollar risk / stop distance.
Stop: Caps: 10c on $1-$8 stocks; 20c on any stock until the size-up gates are passed. Inside the cap, cut shares until the dollar risk fits. Beyond the cap, skip (v1 rule R03); never widen. Never tighten into the noise; reduce shares instead.
Target and exits: n/a.
Time: Before every entry.
Refuse if: Structure stop beyond the cap. Copying historical example stop widths from the source notes.
