# ADCS community port

Community reproduction of the Calder Ridge Instruments memo
**CRI-TM-2087 - Adaptive Duty-Cycle Sampling for Low-Power Vibration Logging** (Revision 1.0, 2020-11-30).

Implements: CRI-TM-2087 | Adaptive Duty-Cycle Sampling for Low-Power Vibration Logging | v1.0

What is implemented:

- envelope trigger with a 0.6 g threshold on the 0-400 Hz band
- baseline duty fraction of 0.08 and a boosted fraction of 0.35 while an event is active
- 90 second hold-off after the envelope falls back under the threshold
- duty-cycle accounting and the waveform counter used by the field dashboards

`adcs/trigger.py` holds the state machine; `adcs/schedule.py` holds the duty
schedule. `tests/` reproduces the worked example from the memo.

This is an independent reproduction. The memo authors did not release reference code.
