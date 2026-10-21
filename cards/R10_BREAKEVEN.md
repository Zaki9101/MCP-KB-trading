---
id: R10_BREAKEVEN
tags: [always, manage]
source: BP p.713 (breakeven trigger), BP p.445 (no move on a few cents of noise), BP p.463 (hard stop stays live on all shares)
conflict: BP p.388 and p.410 use "breakeven once up by the amount risked"; Ch.19 governs in v1
---
Rule: move the stop to breakeven only after the first partial is sold or the first target is reached, not on a few cents of noise. Then raise the stop by hand to the newest structure, and never onto a level without real support. The hard stop stays live on all remaining shares.
Refuse if: no partial and no first target reached (PASS-style answer: HOLD, name R10). Breakeven move asked on a level without support (HOLD, name R10).
Answer MOVE_STOP_BE only when the partial or first target condition is met.
