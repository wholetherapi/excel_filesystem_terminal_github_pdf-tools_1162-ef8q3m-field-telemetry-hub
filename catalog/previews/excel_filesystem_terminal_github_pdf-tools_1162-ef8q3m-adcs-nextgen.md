# ADCS II reference model

Reference model for **Adaptive Duty-Cycle Sampling II** (CRI-TM-2141,
Revision 1.0), the 2026 successor of the 2020 adaptive duty-cycle study.
The revision replaces the fixed boost fraction with a learned trigger head and
extends the hold-off logic to multi-band sensor stacks.

Implements: CRI-TM-2141 | Adaptive Duty-Cycle Sampling II | v1.0

`adcs2/trigger_head.py` trains the learned gate; `adcs2/schedule.py` applies the
schedule constants of the 2141 revision. The benchmark scripts cover the
successor study only.
