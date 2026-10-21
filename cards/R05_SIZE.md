---
id: R05_SIZE
tags: [always, entry]
source: BP p.685 (lot max 300, first lot 50-100); IG-03; user decisions (100 start, 300 max, $1,000 value cap)
conflict: BP p.457-458 position-size tables differ; the user's decision governs
---
Rule: start at 100 shares per entry. Ceiling 300 shares. Position value at most $1,000 (shares x entry price). Size is also limited by the risk budget (R06): shares no more than the risk budget divided by stop distance. Below the minimum share count in config, skip.
Refuse if: shares above 300; position value above $1,000 (PASS, name R05); risk budget gives fewer shares than the minimum (PASS, name R05).
Note: at $1,000 value, 300 shares fits only below about $3.33 a share.
