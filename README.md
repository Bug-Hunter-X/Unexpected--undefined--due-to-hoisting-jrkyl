# JavaScript Hoisting Bug

This repository demonstrates a common JavaScript bug related to variable hoisting.  The code in `bug.js` illustrates how the behavior of `var` declarations can be counterintuitive to developers not fully understanding hoisting.  The solution in `bugSolution.js` shows how to avoid the issue.

**Key Concept:** Hoisting in JavaScript moves declarations (but not initializations) to the top of their scope.  In this specific case, the declaration of 'a' is hoisted, but it's still undefined until the line `var a = 10;` is executed. 

This example is intended for educational purposes to highlight potential pitfalls of using `var` and demonstrate best practices.