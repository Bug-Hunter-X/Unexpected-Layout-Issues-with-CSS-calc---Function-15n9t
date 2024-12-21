# CSS calc() Unexpected Behavior

This repository demonstrates a common error encountered when using the `calc()` function in CSS, specifically involving the interaction of percentages and fixed units.  The `bug.css` file showcases the problematic code, while `bugSolution.css` provides a corrected approach.

The issue stems from relying on container dimensions that might not be fully determined when `calc()` is evaluated.  The solution involves ensuring that the container's dimensions are properly established before the `calc()` calculation is used.