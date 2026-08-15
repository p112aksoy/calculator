# Calculator (C)

A console-based calculator written in C. Supports basic arithmetic operations along with input validation and an interactive help menu.

## Features

- **Operations**: Addition, subtraction, multiplication, division, and exponentiation (`+`, `-`, `*`, `/`, `^`)
- **Input validation**: Detects invalid operators, division by zero, and incorrect number of inputs
- **Help menu**: Type `HELP` at any time to see usage instructions
- **Exit anytime**: Type `EXIT` to close the program

## How to Use

1. Run the program.
2. Enter a calculation in the format: `number operator number` (e.g. `5 + 3`)
3. Type `HELP` for instructions, or `EXIT` to quit.

## Technologies
- C (standard library: `stdio.h`, `stdlib.h`, `string.h`, `math.h`)

## How to Compile & Run

**Windows (with a C compiler like MinGW or Turbo C):**
**gcc calculator.c -o calculator.exe
calculator.exe**

**Note:** This project uses `conio.h`, which is a Windows-specific library. It may require adjustments (e.g. replacing `getch()`) to run on Linux or macOS.
