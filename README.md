# CALCI
##g Simple Python Calculator

### Description

This is a basic Python calculator that takes two numbers and an arithmetic operator (`+`, `-`, `*`, or `/`) from the user. It uses conditional statements to determine which operation to perform and then displays the result. It also checks for division by zero to prevent an error.

### Time Complexity

**O(1) — Constant Time**

The program has a fixed number of operations to perform. It takes two inputs, checks the selected operator through a fixed set of conditions, performs one calculation, and displays the result.

The number of steps does not increase based on the values entered by the user. For example, calculating `5 + 2` and `500000 + 200000` requires essentially the same number of program operations.

Therefore, the time complexity is **O(1)**.

### Space Complexity

**O(1) — Constant Space**

The program stores only a fixed number of variables: the first number, the second number, the operator, and the result.

The amount of memory required does not grow with the input values or the number of calculations.

Therefore, the space complexity is **O(1)**.