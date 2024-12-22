# CSS calc() unexpected behavior with percentages
This repository demonstrates an issue with the CSS `calc()` function when used with percentages and other units.  The expected calculation is not producing the correct result.

## Problem Description
The `calc()` function in CSS is designed to perform calculations on CSS values. However, in certain cases involving percentages and other units, the calculation produces unexpected results.  This repository showcases an example of this behavior and provides a solution.

## Steps to Reproduce
1. Clone this repository.
2. Open `bug.css` and observe the styles applied.
3. Open the HTML file (or any file that uses `bug.css`) in a web browser.
4. Compare the actual rendered dimensions with the expected dimensions based on the calculation in `bug.css`.

## Solution
The solution in `bugSolution.css` demonstrates a way to achieve the expected layout, addressing the issue with the `calc()` function.  The approach avoids relying on `calc()` for this specific use case. Refer to the comments in `bugSolution.css` for detailed explanation.

## Additional Notes
This issue highlights the importance of carefully considering the order of operations and unit compatibility when using the `calc()` function in CSS. For complex calculations, alternative approaches might be more reliable and predictable.