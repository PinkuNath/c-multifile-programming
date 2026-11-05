# Multi-File C Programming

A menu-driven array operations program implemented in C using multiple source files and a shared header file.

## Overview

This project demonstrates modular programming in C by separating input handling, array operations, and display functionality into different source files.

## Features

- Insert an element at a specified position
- Update an existing element
- Delete an element from a specified position
- Traverse the array in forward order
- Traverse the array in backward order
- Check array boundaries and handle invalid positions

## Project Structure

```text
c-multifile-programming/
├── .gitignore
├── array.h
├── display.c
├── input.c
├── logic.c
├── main.c
└── README.md
```

## File Organization

| File | Responsibility |
|---|---|
| `array.h` | Shared constant and function declarations |
| `main.c` | Main menu and program control |
| `input.c` | Reading user input |
| `logic.c` | Array insertion, updating, deletion, and boundary checks |
| `display.c` | Forward and backward traversal |

## Compilation and Execution

Make sure GCC is installed before compiling.

The following commands work on Windows (Git Bash / MinGW), Linux, and macOS:

**Compile:**

```bash
gcc main.c input.c logic.c display.c -o array_operations
```

**Run:**

```bash
./array_operations
```

On Windows, GCC automatically generates an `.exe` executable.

## Concepts Demonstrated

- Modular programming in C
- Header files and header guards
- Function declarations and definitions
- Separation of concerns
- Compilation and linking of multiple source files
- Array operations

## Technologies Used

- C
- GCC