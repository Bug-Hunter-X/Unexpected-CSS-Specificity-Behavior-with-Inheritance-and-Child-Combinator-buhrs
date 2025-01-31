# CSS Specificity Bug
This repository demonstrates an uncommon bug related to CSS specificity, inheritance, and the child combinator (`>`).

## Description
The bug arises from the unexpected interaction between inheritance, specificity, and the use of the `>` combinator.  A seemingly straightforward inheritance case can result in unexpected behavior depending on the specificity of the selector involved. The detailed explanation is available in the bug report.

## Setup
1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Observe the unexpected color of the paragraph element.

## Solution
The solution involves a more careful understanding and use of the CSS specificity rules and the direct child combinator.  The solution is provided in `bugSolution.css`. Refer to the detailed explanation for insights into the fix.
