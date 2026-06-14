# CS Degree Archive

A comprehensive collection of coursework and projects from my Computer Science degree, showcasing programming fundamentals and practical implementations.

## 📚 Repository Structure

This archive is organized by programming language:

- **[c/](c/)** - C Programming Language exercises and projects

## 🔤 C Programming (`c/` folder)

### Overview

C is the foundational language taught at the beginning of most Computer Science programs. This folder contains coursework required for learning C at university, along with mini-projects developed throughout the learning journey.

### Coursework Topics Covered

The exercises in this folder cover essential C programming concepts:

1. Introduction to the Language
2. Program Structure & Basic Syntax
3. Data Types & Variables
4. Constants & Storage Classes
5. Operators & Decision Making
6. Loops & Functions
7. Scope Rules & Arrays
8. Pointers & Strings
9. Structures, Unions & Bit Fields
10. TypeDef & Input/Output
11. File I/O & Preprocessors
12. Header Files & Type Casting
13. Error Handling & Recursion
14. Variable Arguments & Memory Management
15. Command Line Arguments

### Exercises

| File | Description |
|------|-------------|
| **Ex1.c** | Volume of Sphere Calculator (fixed radius) - Computes the volume of a sphere with a 10-meter radius using the formula v = 4/3πr³ |
| **Ex2.c** | Volume of Sphere Calculator (user input) - Accepts radius value from user and calculates volume |
| **Ex3.c** | Dollar-and-Cents Calculator - Asks user to enter a dollars-and-cents amount and displays the amount with 5% tax added |
| **Ex4.c** | Polynomial Function Evaluator - Substitutes user input x value into the equation 3x⁵ - 2x⁴ - 5x³ - x² + 7x - 6 |
| **Ex5.c** | US Dollar Bill Denominator - Breaks down a dollar amount (0-20) using the smallest number of $20, $10, $5, and $1 bills |
| **Ex6.c** | Date Formatter - Accepts a date from user and formats it as yyyymmdd |
| **Ex7.c** | Tabbed View Exercise - Demonstrates text formatting with tabs |
| **Ex8.c** | Additional Exercise - Further practice with C concepts |

### Main Program

| File | Description |
|------|-------------|
| **Game.c** | Interactive menu program that runs all exercises above - Provides a unified interface to execute any exercise |

### Learning Resources

This coursework is based on concepts from:
- [TutorialsPoint - C Programming](https://www.tutorialspoint.com/cprogramming/index.htm)

## 🚀 Getting Started

### Prerequisites

- GCC compiler or any C compiler (e.g., `gcc`, `clang`)
- Terminal/Command prompt

### Compiling and Running

To compile a single exercise:

```bash
gcc -o Ex1 c/Ex1.c
./Ex1
```

Or on Windows:

```bash
gcc -o Ex1 c\Ex1.c
Ex1.exe
```

To compile and run the menu-based Game program:

```bash
gcc -o Game c/Game.c
./Game
```

## 📖 File Structure Details

```
cs-degree-archive/
├── README.md (this file)
├── cs-degree-archive.code-workspace
└── c/
    ├── README.md (detailed exercise documentation)
    ├── Ex1.c through Ex8.c (individual exercises)
    └── Game.c (menu-driven program)
```

## 👨‍💻 Author

Mohamed S Harding

## 📝 Notes

- Each exercise includes comments explaining the problem statement and solution
- The exercises progress from basic input/output to more complex algorithmic thinking
- Concepts build upon each other, reinforcing fundamental CS principles
- This archive serves as a reference for foundational programming knowledge

## 🔗 Related

For more information about each exercise, see [c/README.md](c/README.md)
