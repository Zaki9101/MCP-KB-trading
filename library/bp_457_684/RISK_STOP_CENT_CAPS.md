---
id: RISK_STOP_CENT_CAPS
kind: risk
scope: long-lane-a
tags: [RISK, ANY, stop]
sources: [BLUEPRINT_HANDBOOK p.463, BLUEPRINT_HANDBOOK p.575, BLUEPRINT_HANDBOOK p.580, BLUEPRINT_HANDBOOK p.608, BLUEPRINT_HANDBOOK p.713]
status: conflict
conflicts: BLUEPRINT_HANDBOOK p.463: OGT about 30c "large loss", PB 20c real stop, TR 25-35c padded stops for 1,000-share lots (not adopted before the gates); p.575 Brooks Emini stop about two points; source says 'cut shares' for over-cap stops; v1 rule is skip (R03)
---
Conditions: Every stock trade; take the stop from the structure that proves the idea wrong.
Entry: shares = dollar risk / stop distance; a wider stop means fewer shares.
Stop: $1-$8 stocks 10c hard cap; any stock 20c until the size-up gates; about 30c after the gates at the same dollar risk. Pad 1-3c beyond the structural level (5-10c beyond a whole or half number or an obvious range edge), always inside the cap and counted in the share size. A pattern or Brooks distance never widens a stop.
Target and exits: not stated.
Time: any.
Refuse if: the structure stop or padding passes the cap: skip. Never tighten into the noise to fit; skip (v1 rule R03) instead.
