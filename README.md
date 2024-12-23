# Off-by-One Error in C While Loop

This repository demonstrates a common off-by-one error in C using a `while` loop. The provided `bug.c` file contains the erroneous code, while `bugSolution.c` provides the corrected version.

The error occurs because the loop condition `i > 0` results in an early termination when `i` reaches 0.  The correct condition is `i >= 0` to account for all iterations.