# Simple-Higher-Order-Function-Example
This Python script demonstrates the concept of higher-order functions, where functions can accept other functions as arguments or return functions as results.

Example 1:

- Two helper functions, loud and quiet, are defined to convert text to uppercase and lowercase, respectively. The hello function takes another function func as an argument, applies it to the string "Hello!", and prints the result.

Example 2:

- The divisor function defines an inner function dividend, which divides its argument by the outer function's parameter x. The outer function divisor returns the inner function dividend. Later, divisor is called with an argument of 2, and the returned function is assigned to divide. When divide is called with an argument of 10, it divides 10 by 2, resulting in 5.
