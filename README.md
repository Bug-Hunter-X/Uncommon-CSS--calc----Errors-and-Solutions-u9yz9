# Uncommon CSS `calc()` Errors and Solutions

This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS and provides solutions for them. The `calc()` function is a powerful tool, but it can be prone to errors if not used carefully.  The examples provided here illustrate potential pitfalls and how to avoid them.  Understanding these nuances can improve your CSS code significantly. 

## Common Errors:

1. **Missing spaces:** Spaces around the `+` and `-` operators are required. 
2. **Unit Mismatch:** Mixing different units in a single calculation (without proper conversion) is not allowed.
3. **Invalid Operators:** Using unsupported operators in the `calc()` function may result in unexpected behavior. 
4. **Parenthesis Errors:** Ensure proper use of parentheses for complex calculations.
5. **Incorrect Unit Combination:** Improper combination of `calc()` with other units can lead to unexpected results.

## Solutions:

Each error is shown with an incorrect example in `bug.css` and the correct solution provided in `bugSolution.css`.