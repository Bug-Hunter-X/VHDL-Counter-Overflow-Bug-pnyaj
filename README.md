# VHDL Counter Overflow Bug

This repository demonstrates a common bug in VHDL code: an integer overflow in a counter.  The `buggy_counter.vhdl` file contains the erroneous code. The counter is designed to count from 0 to 15, but the way the upper limit is handled can lead to unexpected behavior, particularly in simulation.

The solution, `fixed_counter.vhdl`, provides a corrected implementation that addresses this potential overflow problem. This ensures that the counter correctly wraps around and avoids unexpected values.

**Key Learning:**
* Proper handling of integer limits in VHDL is crucial to prevent unexpected behavior and ensure the design's reliability.
* Always thoroughly test your VHDL code, including edge cases like maximum and minimum values of counters and signals.