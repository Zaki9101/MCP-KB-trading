---
id: R14_INDEX_AND_CONTEXT
tags: [entry]
source: BP p.712 (index not against the trade), BP p.710 (Lane B index move against = no trade; Lane A legs 1-2 standard, 3-4 only with strong L2)
conflict: the index test threshold is not stated; config value (CONFIG_REQUIRED)
---
Rule: the index must not be moving against the trade. Lane A legs 1 and 2 only; legs 3 and 4 only with strong L2 and reduced size; beyond leg 4, no trade.
Refuse if: index is moving against the trade (PASS, name R14, or FLAG if the move is small and the config threshold is not set). Leg 5 or later (PASS, name R14).
