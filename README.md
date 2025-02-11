# Unexpected Null Return in Addition Function

This repository demonstrates a common JavaScript bug related to null value handling in functions.

## The Bug

The `foo` function adds two numbers. However, it returns `null` if either of the inputs is `null`. This behavior might not always be expected or desired.  A more robust solution might return 0 or throw an error instead of silently returning null.

## The Solution

The solution file demonstrates improved handling of null values, providing more predictable and reliable behavior.

## How to Run

1. Clone this repository.
2. Open `bug.js` to see the buggy code and `bugSolution.js` to see the improved version.
3. Run both files using a JavaScript interpreter (like Node.js). Observe the differences in output.

