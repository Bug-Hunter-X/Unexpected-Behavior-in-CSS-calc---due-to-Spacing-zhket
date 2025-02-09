# Unexpected Behavior in CSS calc() due to Spacing

This repository demonstrates an uncommon error in CSS that arises from using spaces around operators within the `calc()` function.  Incorrect spacing can lead to unexpected results or parsing errors. The solution highlights the importance of correct syntax within the `calc()` function.

## Bug
The provided `bug.css` file contains a CSS rule that uses spaces around the minus operator in the `calc()` function. This incorrect spacing leads to the `width` not calculating as expected.

## Solution
The `bugSolution.css` file corrects the error by removing the unnecessary spaces around the minus operator in the `calc()` function. This ensures correct calculation and expected results.