---
id: RISK_CUT_SHARES_NOT_STOP
kind: risk
scope: long-lane-a
tags: [RISK, ANY, sizing]
sources: [BLUEPRINT_HANDBOOK p.427, BLUEPRINT_HANDBOOK p.438, BLUEPRINT_HANDBOOK p.456, BLUEPRINT_HANDBOOK p.713]
status: book-stated
conflicts: none
---
Conditions: The distance from trigger to the failure level is larger than your dollar risk allows.
Entry: Not applicable.
Stop: Never bring the stop closer. Shares = tier dollar risk / stop distance: with $250 risk, a 25c stop = 1,000 shares and a 50c stop = 500. The same setup in a $20 and a $200 stock risks the same dollars.
Target and exits: Not applicable.
Time: Any.
Refuse if: Stop still beyond the cent cap after cutting shares (skip).
