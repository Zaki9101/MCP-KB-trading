---
id: RISK_CENT_CAPS
kind: risk
scope: long-lane-a
tags: [RISK, ANY, stop-cap]
sources: [BLUEPRINT_HANDBOOK p.713, IG-03, IG-01]
status: book-stated
conflicts: source says 'cut shares' for over-cap stops; v1 rule is skip (R03)
---
Conditions: Stop cap is 10c on $1-$8 stocks and 20c on any stock until the size-up gates pass. About 30c only after the gates, at the same dollar risk.
Entry: not stated
Stop: Inside the cap; shares = tier dollars divided by stop distance.
Target and exits: not stated
Time: not stated
Refuse if: Stop beyond the cap: skip. Never tighten a stop to fit size; skip (v1 rule R03) instead.
