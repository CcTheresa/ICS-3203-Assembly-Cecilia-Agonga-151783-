# Assembly Language Programming Project

## Overview
This repository contains a series of assembly language programs developed as part of an academic assignment. The programs are written for x86 architecture using the NASM assembler. Each task in this project demonstrates a different fundamental concept in assembly programming, including input/output handling, arithmetic operations, and logical operations.

---

## Prerequisites
To run the programs in this repository, ensure you have the following installed on your system:
- **NASM (Netwide Assembler)**: [Download NASM](https://www.nasm.us/)
- A **linker** such as `gcc` or `ld` for creating executable files.
- An x86-based processor or emulator.

---

## Tasks Breakdown

### Task 1: Input and Output Handling
- **Description**: This program accepts input from the user and prints it back to the console. It demonstrates basic assembly-level interaction with standard input/output.
- **Key Concepts**:
  - System calls for reading and writing.
  - Handling strings in assembly.

---

### Task 2: Arithmetic Operations
- **Description**: Implements basic arithmetic operations (addition, subtraction, multiplication, and division). It reads two integers from the user and outputs the results of the operations.
- **Key Concepts**:
  - Arithmetic instructions in assembly (`add`, `sub`, `mul`, `div`).
  - Register manipulation for computations.

---

### Task 3: Logical Operations
- **Description**: Demonstrates the use of logical operations (AND, OR, XOR, and NOT) in assembly language. It takes two integers as input and performs the logical operations on them.
- **Key Concepts**:
  - Bitwise instructions (`and`, `or`, `xor`, `not`).
  - Boolean logic and its implementation in assembly.

---

### Task 4: Conditional Statements
- **Description**: Implements a program that makes decisions based on user input. It uses conditional branching instructions to compare values and execute different instructions based on the result.
- **Key Concepts**:
  - Comparison and conditional jump instructions (`cmp`, `je`, `jne`, `jg`, `jl`).
  - Basic decision-making in assembly.

---

### Task 5: Loops and Iteration
- **Description**: This program demonstrates the use of loops in assembly. It performs repetitive tasks, such as printing a sequence of numbers or summing integers.
- **Key Concepts**:
  - Looping instructions (`loop`, `jmp`).
  - Counters and iterations in assembly.

---

## How to Run the Programs
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/<your-username>/<repository-name>.git
   cd <repository-name>

2.Assemble the program using NASM:
nasm -f elf64 <program-name>.asm -o <program-name>.o

3.Link the object file to create an executable
gcc -no-pie -o <program-name> <program-name>.o

4.Run the executable:
./<program-name>
