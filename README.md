# CSS Specificity Bug

This repository demonstrates a common issue encountered when working with CSS: unexpected styling due to specificity conflicts.

The `bug.css` file contains CSS code that leads to unexpected styling due to selector specificity. The `bugSolution.css` file demonstrates several approaches to resolving this issue.

## Problem

The CSS specificity rules determine which style declaration is applied when multiple selectors match an element.  Understanding and managing CSS specificity is crucial to writing predictable and maintainable stylesheets.  This example showcases a common pitfall where a more specific selector overrides a more general one, possibly counter to the developer's intention. 

## Solution

The solution involves carefully considering the order and specificity of selectors and may involve using the `!important` flag (though this is generally discouraged for maintainability) or reorganizing styles to ensure the desired specificity.