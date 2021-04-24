# Part 3 Questions

1. The application is concatenating the two numbers together instead of adding them, because they are being treated as strings.
2. To fix the bug, I converted `num1` and `num2` inside of `calculateSum` to a number using the `Number()` function. This allows the numbers to be added as numbers, instead of being concatenated as strings, so that `result` contains the correct mathematical result.
