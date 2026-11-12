# Vibration-triggered burst sampling

Community implementation of **Vibration-Triggered Burst Sampling**
(CRI-TM-2042, Revision 1.1), the precursor study that buffers a short burst when
an accelerometer threshold is crossed and then returns to sleep. It does not
use a duty-cycle schedule.

Implements: CRI-TM-2042 | Vibration-Triggered Burst Sampling | v1.1

`burst/trigger.py` contains the threshold logic and `burst/buffer.py` the burst
ring buffer.
