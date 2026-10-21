---
id: RULE_NO_LONG_BELOW_PRIOR_DAY_HIGH
kind: rule
scope: long-lane-a
tags: [SCAN, ANY, prior-day-high]
sources: [BLUEPRINT_HANDBOOK p.280, BLUEPRINT_HANDBOOK p.347]
status: book-stated
conflicts: none
---
Conditions: CEP long filter: the stock must be trading above the previous day's high. The high of day is the most important intraday level.
Entry: Do not take a long in a stock below the previous day's high. After a failed breakout, leave the stock alone until it breaks that high.
Stop: Not applicable.
Target and exits: Prior-day sell-off levels above are resistance where trapped longs sell to get even.
Time: Any.
Refuse if: Stock not trading above the previous day's high.
