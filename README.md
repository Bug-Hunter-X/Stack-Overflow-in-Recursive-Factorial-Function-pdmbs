# Hack Bug: Stack Overflow in Recursive Factorial

This repository demonstrates a common error in Hack: a stack overflow caused by excessive recursion in a factorial function.  The `bug.hh` file contains the erroneous code, which recursively calculates the factorial. For large inputs, this will exceed the maximum recursion depth and crash the program.

The solution, `bugSolution.hh`, provides an iterative approach that avoids the stack overflow issue. This demonstrates the importance of carefully considering recursion depth and using iterative solutions for computationally intensive tasks.

## How to Reproduce

1. Clone the repository.
2. Compile and run `bug.hh` with a large input (e.g., `echo foo(10000)`) to observe the stack overflow.
3. Compile and run `bugSolution.hh` to see the corrected iterative solution.

## Lessons Learned

* Be mindful of recursion depth limitations.
* Iterative solutions often provide superior performance and stability for computationally intensive tasks compared to their recursive counterparts.