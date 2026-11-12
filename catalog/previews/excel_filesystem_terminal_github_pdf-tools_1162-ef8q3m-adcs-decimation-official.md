# ADCS-D official code

Official implementation released by the Calder Ridge Instruments authors for
**Adaptive Duty-Cycle Sampling with Decimation** (CRI-TM-2093, Revision 2.0),
the decimation-aware variant used in the 2022 acoustic pilot.

Implements: CRI-TM-2093 | Adaptive Duty-Cycle Sampling with Decimation | v2.0

`adcs_d/decimator.py` implements the polyphase decimation stage;
`adcs_d/schedule.py` implements the 2093 duty schedule.
