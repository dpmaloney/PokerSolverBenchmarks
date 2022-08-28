# PokerSolverBenchmarks

The following solves were done on an i7-10700k with 32gb of 3200mhz ram.

BigBench.txt to .5% of the pot.

My Solver may not build the tree in the exact same way as pio because pio rounds some betsizes, I'll see if I can fix this. The lower values for my solver use donk sizings on the river and turn, but I need to check correctness.

| jesolver 1084 (Default Settings) | Piosolver 2.0.7.13 | My Solver |
| :----: | :----: | :----: |
| 563.836 sec | 2000+ sec (timed out) | 1336 sec or 368 sec |
| 14,679 mb of ram | 12,003 mb of ram | 15,690 mb of ram or 7,840 mb of ram |

Notes: Piosolver only uses 50% of the CPU for the whole benchmark, odd. 
