# TypeScript Type Error: Argument of type string[] is not assignable to parameter of type string

This repository demonstrates a common TypeScript type error and its solution. The error occurs when a function expecting a string argument is provided with an array of strings.  The solution involves either modifying the function to accept an array or processing the array elements appropriately before passing them to the function.

## Bug Description

The original code attempts to pass a string array to a function that expects a single string. This results in a type error because the function signature doesn't match the argument type.

## Solution

The solution modifies the `greeter` function to accept either a single string or an array of strings. It then handles both scenarios appropriately.