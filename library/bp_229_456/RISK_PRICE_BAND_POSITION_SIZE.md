---
id: RISK_PRICE_BAND_POSITION_SIZE
kind: risk
scope: long-lane-a
tags: [RISK, ANY, price-band]
sources: [BLUEPRINT_HANDBOOK p.456, BLUEPRINT_HANDBOOK p.715]
status: conflict
conflicts: NB p.11 via BLUEPRINT_HANDBOOK p.456: the $500 band printed as $0.70-$2, below the $1 floor (not adopted); source says 'cut shares' for over-cap stops; v1 rule is skip (R03)
---
Conditions: Quick default share count by share price.
Entry: $1,500 for $8-$20 stocks; $1,000 for $2-$8; $500 for $1-$2; under $1 = no trade. Shares = band dollars / price. The table sets capital deployed, not risk.
Stop: Shares x stop distance must still fit your tier and the cent cap; skip (v1 rule R03) if they disagree, never widen the stop to fit the table.
Target and exits: Not applicable.
Time: Any.
Refuse if: Stock under $1; using the table's dollar figure to justify a wider stop.
