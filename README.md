# Uncommon HTML Bug: Unexpected Deletion of Script Element using outerHTML
This repository demonstrates an uncommon bug related to the use of the `outerHTML` property in HTML.  The bug involves unexpected deletion of a script element when modifying an element's `outerHTML` property.  This is particularly problematic when the script element is dynamically manipulating the element being altered.

The `bug.html` file reproduces the issue. The `solution.html` file shows a way to avoid this issue.