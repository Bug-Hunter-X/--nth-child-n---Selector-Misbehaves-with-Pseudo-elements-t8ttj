# :nth-child(n) Selector Issue with Pseudo-elements

This repository demonstrates a subtle bug related to the CSS `:nth-child(n)` selector when used in conjunction with pseudo-elements (`::before` and `::after`).  The selector doesn't behave as expected, leading to incorrect element selection.

The `bug.css` file showcases the problematic code. The `bugSolution.css` file provides a corrected approach.

This issue is important because it can cause unexpected styling and layout problems, particularly when dealing with complex structures.