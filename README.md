# Menu-Driven Calculator (PS No. 25)

A console calculator written in **Python 3** that repeatedly shows a menu of arithmetic operations, takes two numbers, displays the result (rounded to 2 decimal places) and handles errors such as division by zero until the user chooses to exit.

## Student Details
| | |
|---|---|
| **Name** | Saikat Jana |
| **ERP Number** | 00353 |
| **Course** | BCA (Artificial Intelligence and Machine Learning) |
| **Section** | 1-B |
| **University** | Rungta International Skills University |

## Problem Statement
Create a console calculator that repeatedly shows a menu of arithmetic operations, takes two numbers, displays the result and handles errors such as division by zero until the user chooses to exit.
Menu: 1 Add, 2 Subtract, 3 Multiply, 4 Divide, 5 Power, 6 Modulus, 7 Exit. Results are rounded to 2 decimal places.

**Concepts used:** Functions, Loops, Operators, Exceptions

## Features
- Loop-driven menu with an Exit option
- One function for each operation (add, subtract, multiply, divide, power, modulus)
- try-except handling for division by zero and non-numeric input
- Menu-choice validation (1 to 7)
- Every result rounded to 2 decimal places

## How to Run
```bash
python code.py
```

## Sample Run
```
===== CALCULATOR MENU =====
1. Add
2. Subtract
3. Multiply
4. Divide
5. Power
6. Modulus
7. Exit
Enter your choice (1-7): 1
Enter first number: 12
Enter second number: 8
12 + 8 = 20.00
```

## Test Cases
| # | Input | Expected Output |
|---|-------|-----------------|
| 1 | Add: 12 and 8 | `12 + 8 = 20.00` |
| 2 | Divide: 0 and 5 | `0 / 5 = 0.00` |
| 3 | (a) Divide: 10 and 0 / (b) Multiply: abc and 4 / (c) Choice 9 | (a) `Error: Division by zero is not allowed.` (b) `Invalid number. Enter numeric values only.` (c) `Invalid choice. Select 1 to 7.` |
| 4 | (a) Power: 2 and 10 / (b) Modulus: 17 and 5 / (c) Subtract: 5 and 9.5 / (d) Exit | (a) `2 ^ 10 = 1024.00` (b) `17 % 5 = 2.00` (c) `5 - 9.5 = -4.50` (d) `Thank you for using the calculator. Exiting...` |

All 4 test cases pass. Screenshots are in `testcases.pdf`.

## Files
| File | Description |
|------|-------------|
| `code.py` | Main program |
| `readme.md` | This file |
| `testcases.pdf` | Test cases with execution screenshots |
| `test_data.txt` | Test inputs and outputs in text form |
| `project_details.png` | Project details image from the Project Allocation PDF |
| `Project_Report_Menu_Driven_Calculator.pdf` | Full project report |
