---
id: SCAN_LIQUIDITY_ORDER_COUNT
kind: scan
scope: long-lane-a
tags: [SCAN, PREOPEN, liquidity]
sources: [BLUEPRINT_HANDBOOK p.032, BLUEPRINT_HANDBOOK p.099, BLUEPRINT_HANDBOOK p.205]
status: book-stated
conflicts: none
---
Conditions: Clean premarket price action plus real two-sided volume = tradeable. Relative volume matters more than absolute volume. Count the orders printing, not only the share total: 1,000,000 shares in ten 100,000-share orders is not liquid.
Entry: n/a (selection filter; the setup sheet and tape decide).
Stop: n/a.
Target and exits: n/a.
Time: Premarket and the first minutes.
Refuse if: Flat premarket action with a few large block trades, even when gap % and volume totals look fine. High volume made of only a few blocks while the book stays thin.
