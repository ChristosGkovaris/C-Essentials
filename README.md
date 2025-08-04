# C ESSENTIALS

This project contains **fundamental C programming exercises** that demonstrate **core algorithms, logic building, and console input/output operations**. 

---

## TABLE OF CONTENTS
1. [Overview](#overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Input Data](#input-data)
5. [Algorithms Implemented](#algorithms-implemented)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Output Files](#output-files)
9. [Testing](#testing)
10. [License](#license)
11. [Contact](#contact)

---

## OVERVIEW

This collection of programs demonstrates **essential C programming concepts**, including:

- Basic arithmetic and string operations
- Looping and conditional statements
- Array manipulation and matrix operations
- Simple mathematical algorithms

These exercises are designed to **strengthen logic-building skills** and **familiarity with C syntax**.

---

## FEATURES

- Console-based **user input and output**
- Covers **mathematical operations, array operations, string checks**
- Simple **matrix multiplication**
- Includes **utility algorithms** such as:
  - Palindrome check
  - Prime number detection
  - Factorial and Fibonacci calculations
  - Reversing arrays and summing digits

---

## PROJECT STRUCTURE

```
c-essentials/
│── README.md
│
└── src/
    ├── calculator.c               # Basic calculator with +, -, x, /
    ├── factorial.c                # Computes factorial of a number
    ├── fibonacci_sequence.c       # Generates Fibonacci sequence
    ├── largest_among_three.c      # Finds the largest of three numbers
    ├── matrix_multiplication.c    # Multiplies two matrices
    ├── number_is_prime.c          # Checks if a number is prime
    ├── palidrome_check.c          # Checks if a string is palindrome
    ├── reverce_array.c            # Reverses an integer array
    └── sum_of_num_digits.c        # Sums the digits of a number
```

---

## INPUT DATA

Each program is **interactive** and requests input via **console prompts**, for example:

- **Calculator:** Operation symbol followed by numbers  
- **Matrix Multiplication:** Dimensions and matrix elements  
- **Palindrome Check:** Input string  
- **Factorial, Fibonacci, Prime:** Input integer

---

## ALGORITHMS IMPLEMENTED

1. **Arithmetic & Array Operations**
   - Basic calculator
   - Reverse array elements
   - Sum of digits

2. **Mathematical Algorithms**
   - Factorial calculation
   - Fibonacci sequence generation
   - Prime number checking
   - Largest among three numbers

3. **String Operations**
   - Palindrome checking

4. **Matrix Operations**
   - Matrix multiplication with validation for compatible dimensions

---

## INSTALLATION

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/c-programming-essentials.git
cd c-programming-essentials
```

2. **Install GCC (if not installed):**
```bash
sudo apt install build-essential    # Linux
# or
brew install gcc                    # macOS
```

---

## USAGE

Compile and run any C program using **GCC**:

```bash
gcc src/calculator.c -o calculator
./calculator + 3 4 5
```

Other examples:
```bash
gcc src/factorial.c -o factorial
./factorial

gcc src/matrix_multiplication.c -o matrix_multiplication
./matrix_multiplication
```

---

## OUTPUT FILES

- Programs produce **console output only**  
- Optional: Redirect output to a file if needed:
```bash
./factorial > output.txt
```

---

## TESTING

- Test with **valid and invalid inputs**  
- Verify **matrix multiplication** with small matrices manually  
- Check **palindrome detection** with both palindromes and non-palindromes

---

## LICENSE

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## CONTACT

**Christos Gkovaris**  
University of Ioannina – Computer Science and Engineering  
[GitHub](https://github.com/ChristosGkovaris)
