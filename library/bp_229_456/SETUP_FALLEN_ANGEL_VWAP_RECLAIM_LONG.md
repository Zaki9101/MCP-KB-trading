---
id: SETUP_FALLEN_ANGEL_VWAP_RECLAIM_LONG
kind: setup
scope: long-lane-a
tags: [VWAP, OPEN, low-float]
sources: [BLUEPRINT_HANDBOOK p.256, BLUEPRINT_HANDBOOK p.395, BLUEPRINT_HANDBOOK p.396, BLUEPRINT_HANDBOOK p.397, BLUEPRINT_HANDBOOK p.398, BLUEPRINT_HANDBOOK p.424]
status: conflict
conflicts: NB p.130 via BLUEPRINT_HANDBOOK p.396 and p.398: '1-min OR 5-min high' triggers; verdict NB-A4-06 requires both. Stop choice C-T6-N06 (p.424); source says 'cut shares' for over-cap stops; v1 rule is skip (R03)
---
Conditions: Low-float stock (usually under 20M shares) gaps up big premarket on strong news with premarket volume of at least 1M; pops to a new high, sells off to a support (e.g. premarket low), consolidates, then reclaims VWAP on volume clearly above prior candles.
Entry: New 1-min AND new 5-min high after the reclaim. A 1-min-only break is a Tier1 starter at most.
Stop: Tighter structural level of the consolidation low or the premarket low, inside the Ch. 19 cap; skip (v1 rule R03), never widen.
Target and exits: Staged: VWAP, then HOD, then premarket high. The first target must measure 2.0R (CAPR's HOD was 1.6R: half size or use the next target).
Time: Best 9:30-10:30 per the notes; Ch. 19 entries from 9:35 (CAPR entry was 9:45).
Refuse if: Reclaim volume not clearly bigger than the preceding candles; medium-float stock.
