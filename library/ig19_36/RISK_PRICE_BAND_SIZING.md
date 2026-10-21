---
id: RISK_PRICE_BAND_SIZING
kind: risk
scope: long-lane-a
tags: [RISK, ANY, sizing]
sources: [IG-24 panel 2]
status: sheet-stated
conflicts: none
---
Conditions: Price band sets capital and stop cap.
Entry: $8-$20: $1,500, 20c; $2-$8: $1,000, 10c; $1-$2: $500, 10c.
Stop: Stop cap per band.
Target and exits: Shares = Tier $ / stop; take the smallest. Band $ is a ceiling.
Time: Any.
Refuse if: Widening the stop to fit more shares.
