# Misnested Pseudo-element Selector in CSS

This repository demonstrates a common yet easily overlooked error in CSS: improperly nesting pseudo-elements within selectors.

The `bug.css` file contains the erroneous CSS. The `bugSolution.css` file provides the corrected code.

**Problem:**
Pseudo-elements like `::before` and `::after` must be associated with a specific element. Placing them without a proper parent selector can lead to unexpected behavior or no effect.

**Solution:**
Ensure that the pseudo-element selector is correctly nested within an element selector that exists in the document's HTML.
