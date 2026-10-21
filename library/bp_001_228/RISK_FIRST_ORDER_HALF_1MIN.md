---
id: RISK_FIRST_ORDER_HALF_1MIN
kind: risk
scope: long-lane-a
tags: [RISK, ANY, starter-lot]
sources: [BLUEPRINT_HANDBOOK p.163, BLUEPRINT_HANDBOOK p.173]
status: book-stated
conflicts: source says 'cut shares' for over-cap stops; v1 rule is skip (R03)
---
Conditions: 1-min apex entries (for example the first leg off a Gap and Go) carry the full max-risk exposure at the first fill.
Entry: Start with half size, never full. Expect almost immediate resolution; no resolution = weakness, cut size or exit. Double only if the stop can then move to breakeven; otherwise take the win on the smaller size.
Stop: The larger 5-min first order still fits Tier1 and the cent cap: skip (v1 rule R03), never widen.
Target and exits: Half-at-1R partial still needs a 2.0R first target for the remainder.
Time: Any time.
Refuse if: Full-size first fill on a 1-min apex.
