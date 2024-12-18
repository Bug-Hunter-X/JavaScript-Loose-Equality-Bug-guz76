# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug related to loose equality (`==`). Loose equality can lead to unexpected type coercion, resulting in incorrect comparisons.  The example shows how to avoid this by using strict equality (`===`).

## Bug
The `bug.js` file contains a function that uses loose equality. This can lead to unexpected behavior when comparing values of different types.

## Solution
The `bugSolution.js` file demonstrates the correct way to compare values using strict equality, avoiding the unexpected type coercion issues.

## How to reproduce
1. Clone this repository.
2. Run the `bug.js` file. Observe the unexpected results due to loose equality.
3. Run the `bugSolution.js` file. Observe the corrected behavior using strict equality.