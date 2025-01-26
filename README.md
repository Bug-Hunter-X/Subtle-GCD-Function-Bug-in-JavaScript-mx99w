# Subtle GCD Function Bug
This repository demonstrates a subtle bug in a JavaScript function designed to calculate the greatest common divisor (GCD) of two numbers using the Euclidean algorithm. The function works correctly for most inputs but fails in specific scenarios involving zero.

## Bug Description
The `myFunction` uses recursion and the Euclidean algorithm. However, the handling of zero inputs is flawed, leading to incorrect GCD calculations under certain conditions.

## How to Reproduce
1. Clone this repository.
2. Open `bug.js`.
3. Run the code. Observe that the GCD calculation is not correct when one or both of the inputs are zero.

## Solution
The solution is provided in `bugSolution.js`. It addresses the edge cases involving zero inputs, ensuring correct GCD calculation for all inputs.