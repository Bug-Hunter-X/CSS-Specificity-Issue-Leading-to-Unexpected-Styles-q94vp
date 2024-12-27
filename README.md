# CSS Specificity Bug

This repository demonstrates a common, yet often subtle, bug in CSS related to specificity.  The bug arises from the interaction of multiple CSS selectors with varying levels of specificity, resulting in unexpected styling outcomes.

## Bug Description

The CSS code in `bug.css` demonstrates a scenario where the specificity of CSS selectors leads to a result different from what one might intuitively expect.  The inner `div`'s color is not what is initially expected based on a cascading rule.