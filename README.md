# CSS `calc()` Gotchas

This repository demonstrates two uncommon issues that can arise when using the CSS `calc()` function.  The first relates to spacing around operators and the second concerns unit compatibility within calculations.

**Problem 1:**  Spaces around operators within `calc()` can cause parsing errors or unexpected results.

**Problem 2:** Combining percentages and fixed units (like pixels) in `calc()` can lead to inconsistent rendering across browsers, especially if the resulting calculation exceeds the container's dimensions.

The `bug.css` file showcases the problematic code, while `bugSolution.css` offers corrected versions.