# Tailwind CSS Gradient Bug Report

This repository demonstrates some uncommon issues that can occur when using gradients in Tailwind CSS.  These issues aren't necessarily syntax errors that prevent compilation, but lead to unexpected visual results or no gradient being applied.

**Issues Covered:**

* **Missing `to` value in gradient definition:**  Forgetting the `to` direction can prevent the gradient from rendering correctly.
* **Invalid color values:** Using a color that Tailwind doesn't understand or is misspelled will cause problems.
* **Unsupported gradient types:** Using gradient directions that aren't supported by your Tailwind configuration will have no visible effect.

**Solutions:**

Ensure you use valid Tailwind CSS color values, always specify the `to` direction for gradients, and verify the gradient type is supported within your configuration.

This repository includes example HTML files (`bug.html` and `bugSolution.html`) showcasing the bug and its solution. The `bug.html` demonstrates the issue and the `bugSolution.html` demonstrates the solution.