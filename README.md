# Infinite Loop Bug in Java

This repository demonstrates a common error in Java involving the use of the `continue` statement within a `while` loop.  The code intends to print numbers 1 through 10, skipping the number 5. However, due to an improper increment condition, an infinite loop results.  The solution provided corrects this by ensuring that the increment happens regardless of the `continue` statement. 

## How to Reproduce

1. Clone this repository.
2. Compile and run `Bug.java`.  Observe the infinite loop.
3. Then, compile and run `BugSolution.java` to see the corrected code.