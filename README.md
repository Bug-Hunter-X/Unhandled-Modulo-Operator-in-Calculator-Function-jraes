# Unhandled Modulo Operator in Calculator Function

This repository demonstrates a common JavaScript bug related to unhandled operators in a switch statement. The `calculate` function handles addition, subtraction, multiplication, and division, but it throws an error if any other operator is used, including the modulo operator (`%`).

The `bug.js` file contains the buggy code.  The `bugSolution.js` file shows the corrected code.

## Bug

The original code throws an error if a user attempts to perform a modulo operation. This is because the switch statement doesn't have a `case` for the `%` operator. 

## Solution

The solution adds a case for the modulo operator to the switch statement, handling modulo operations correctly.  If an invalid operator is used, a more descriptive error message is provided.