# Unnecessary Vendor Prefix in CSS Transform

This repository demonstrates a common CSS bug involving unnecessary vendor prefixes and provides a solution.  The bug involves using a vendor-specific prefix for the `transform` property, resulting in inconsistent rendering across different browsers. Modern browsers generally support the standard `transform` property without vendor prefixes.

## Bug

The `bug.css` file contains CSS code with an outdated `-webkit-` prefix for the `transform` property. This prefix is not required by modern browsers and might lead to unexpected visual results or inconsistencies in rendering.

## Solution

The `bugSolution.css` file shows the corrected CSS, removing the unnecessary vendor prefix.  This ensures better cross-browser compatibility and cleaner code.