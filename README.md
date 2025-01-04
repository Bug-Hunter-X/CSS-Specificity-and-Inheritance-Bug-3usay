# CSS Specificity and Inheritance Bug

This repository demonstrates a subtle bug related to CSS specificity and inheritance. The bug arises from unexpected behavior when combining nested selectors and inheritance.

## Bug Description

The issue occurs when specific styles are applied to nested elements, and the final rendered color might not match expectations due to the order of rules in the CSS and the complexities of how specificity and inheritance interact.  This inconsistency can manifest across different browsers.

## How to Reproduce

1.  Clone this repository.
2.  Open `index.html` in your browser.
3.  Observe the rendered colors of the paragraph elements.  The result might be unexpected based on an assumed understanding of CSS specificity.

## Solution

The solution is provided in `bugSolution.css`, which addresses specificity and inheritance issues through more precise style application and more robust cascading.