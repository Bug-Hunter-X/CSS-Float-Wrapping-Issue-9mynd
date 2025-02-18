# CSS Float Wrapping Bug

This repository demonstrates a common issue with floating elements in CSS. When divs are floated without a defined width on their parent container, they might not wrap correctly across multiple lines in some browsers. This leads to unexpected layout issues.

## Bug

The `bug.css` file contains CSS code that causes this problem. The divs inside a container without a specified width will float but not wrap.  This is particularly problematic when the content within the divs extends beyond the width of the viewport.

## Solution

The `solution.css` file provides a solution to this problem.  The parent container now has a defined width or clearfix is used. This ensures proper wrapping behavior across different browsers.