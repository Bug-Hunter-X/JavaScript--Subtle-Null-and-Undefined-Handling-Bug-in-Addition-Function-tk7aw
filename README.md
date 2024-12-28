# JavaScript: Subtle Null and Undefined Handling Bug

This repository demonstrates a common, yet subtle, bug in JavaScript related to handling null and undefined values in a function.  The `foo` function aims to add two numbers, but its null checks are incomplete.

## The Bug

The original `bug.js` file contains a function that checks for null values but not undefined values. This causes unexpected results when either input is undefined.

## The Solution

The `bugSolution.js` file provides a corrected version that handles both null and undefined values appropriately using loose comparison.