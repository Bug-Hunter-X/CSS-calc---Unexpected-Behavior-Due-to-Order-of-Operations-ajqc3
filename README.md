# CSS calc() Unexpected Behavior

This repository demonstrates a common, yet subtle, error encountered when using the `calc()` function in CSS. The problem arises from the order of operations and the handling of different unit types (percentages and pixels in this example).  Incorrectly ordering these values will lead to unexpected layout results.

The `bug.css` file showcases the flawed CSS that leads to layout issues.  The `bugSolution.css` file provides the corrected CSS that demonstrates the correct usage of the calc() function.

## How to Reproduce

1. Clone the repository.
2. Open `bug.html` (or create a similar HTML file) in your browser.
3. Observe the unexpected layout caused by the incorrect `calc()` usage in `bug.css`.
4. Replace `bug.css` with `bugSolution.css` and refresh the browser to see the expected layout.