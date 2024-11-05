## Task 1
All tasks completed successfully. Observing the waveform in GTKwave gave expected outcome.
Time axis means nothing in GTKwave, as Verilator operates cycle-by-cycle. Each tick is 1ps.

Test yourself challenges also completed. Waveform now shows counter pausing on the 9th clock cycle, then resuming on the 12th.
Asynchronous reset added by adding reset positive edge to flip flop sensitivity list. This allows the flip flop to be reset independent of clock cycle.

---

## Task 2
All tasks completed. 

Test yourself challenge done by setting en to the value of vbdFlag(). Reset is kept 0 throughout. 