---
id: RISK_PRICE_BAND_SHARE_CEILING
kind: risk
scope: long-lane-a
tags: [RISK, ANY, position-size]
sources: [BLUEPRINT_HANDBOOK p.457, BLUEPRINT_HANDBOOK p.458, BLUEPRINT_HANDBOOK p.463, BLUEPRINT_HANDBOOK p.715]
status: conflict
conflicts: BLUEPRINT_HANDBOOK p.458 (NB p.51): tiers of 500, 800, 1,000 shares under $5 (ceiling only; p.715 allows the ladder only at $25,000+ account and price under $5); p.457 (CEP): $7000/price, $5000/price, $2500/price buttons
---
Conditions: Quick default share count by price band (My Notes): $1,500 / price for $8-$20 stocks; $1,000 / price for $2-$8; $500 / price for $1-$2.
Entry: take the smallest of the risk-based share count, this table, and (while in sim) the monthly caps. Example: $3 stock, 10c stop, table gives 333 shares ($33 risk).
Stop: the stop and its cent cap still govern the real risk.
Target and exits: not stated.
Time: any.
Refuse if: price under $1 (the notes' $0.70-$2 band is not adopted).
