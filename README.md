# Tailwind CSS Responsive Design Conflict

This repository demonstrates a common issue encountered when using Tailwind CSS for responsive design. The problem arises from the order of responsive classes and Tailwind's specificity rules, leading to unexpected visual results at different breakpoints.

## Problem
The `responsive-bug.html` file showcases the bug.  Notice how the padding isn't properly adjusted at larger screen sizes due to the ordering of Tailwind classes.  This is caused by the unintended precedence given to certain responsive classes.