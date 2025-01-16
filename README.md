# CSS Specificity Bug: Unexpected Color

This repository demonstrates a subtle but important bug related to CSS specificity.  The issue highlights the unexpected behavior that can occur when combining ID and class selectors.

## The Problem

The `bug.css` file contains CSS rules that appear to be straightforward but lead to unexpected results. The element with both an ID and class selector will not render with the expected color due to the specificity rules in CSS.

## The Solution

The `solution.css` file demonstrates how to correctly apply styles in this type of situation, focusing on how to improve selector choice based on the CSS specificity mechanism.