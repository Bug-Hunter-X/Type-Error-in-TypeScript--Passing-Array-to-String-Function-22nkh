# Type Error in TypeScript: Passing Array to String Function

This repository demonstrates a common type error in TypeScript that occurs when an array is passed to a function expecting a string. The error occurs because the types do not match, and the compiler will flag this as an issue.  The solution involves type checking and handling the array correctly.

## Bug
The bug lies in the `greeter` function, which expects a single string as input. However, the program passes an array of strings to the function, resulting in a type error.

## Solution
The solution involves either modifying the `greeter` function to accept an array of strings or iterating over the array and calling the `greeter` function for each element.

The solution file (`bugSolution.ts`) presents a corrected version.