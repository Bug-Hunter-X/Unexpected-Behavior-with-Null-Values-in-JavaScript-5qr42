# JavaScript Null Handling Bug

This repository demonstrates a common bug in JavaScript related to handling null values when performing arithmetic operations.

## Problem
The `foo` function is designed to add two numbers. However, it produces unexpected results when either `a` or `b` is null.  JavaScript's loose comparison (`==`) can cause unexpected type coercion, potentially leading to incorrect calculations or errors.

## Solution
The issue is resolved by using strict equality (`===`) to check for null values explicitly. The corrected function now handles null inputs gracefully, returning 0 as intended.

## How to Run
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` to see the buggy and corrected code respectively. 
3. Run each file using a JavaScript environment (Node.js, browser console, etc.).