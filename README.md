# CSS Specificity Bug: Unexpected Color Inheritance

This repository demonstrates a subtle bug related to CSS specificity and inheritance. The bug involves unexpected color inheritance in nested elements, causing the final rendered color to differ from the expected result.

## Bug Description
The issue occurs when applying multiple CSS rules with varying specificity to nested elements. The expected rule based on specificity might not be applied, resulting in an unexpected color. The code example highlights a scenario where specificity calculation leads to an unexpected color inheritance in nested elements.

## How to Reproduce
1.  Clone this repository.
2. Open the `bug.css` file to see the problematic CSS code.
3. Open `index.html` to see the code and the problem.
4. Observe the rendered color of the text in the paragraph.

## Solution
The solution involves clarifying the CSS rules to ensure the correct level of specificity and priority. This can be done by adjusting selectors or using the `!important` flag (though generally not recommended). The corrected CSS code is available in `bugSolution.css`.

## Note
This is a demonstration of a potentially hard-to-debug CSS issue related to specificity and inheritance. Understanding CSS specificity is crucial for avoiding this kind of problem.