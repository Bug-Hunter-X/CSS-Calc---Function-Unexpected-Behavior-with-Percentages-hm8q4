# CSS Calc() Function Unexpected Behavior with Percentages
This repository demonstrates an uncommon CSS error related to the `calc()` function and percentage calculations.  The issue arises from attempting to directly add percentages within the `calc()` function without understanding the context of the parent element's dimensions.

## Bug
The provided `bug.css` file contains CSS code that demonstrates the error. When you try to add two percentages directly within the `calc()` function, the outcome might not be as expected. This is because percentages are calculated relative to the containing element's dimensions, and adding them directly might not be valid. 

## Solution
The solution in `bugSolution.css` demonstrates how to resolve this issue by correctly using the `calc()` function with percentages, ensuring accurate calculations.

Feel free to contribute and improve the examples!