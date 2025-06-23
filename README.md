# 🔢 Big Integer Library in C++

A comprehensive **arbitrary-precision integer arithmetic** library written in modern **C++**, designed to handle integers of virtually unlimited size. Built from scratch without external dependencies, this project is ideal for exploring advanced **Data Structures & Algorithms**, number theory, and cryptography use cases.

---

## 📚 Description

Standard integer types in C++ (`int`, `long long`, etc.) have fixed maximum sizes. This library introduces a **custom BigInt class** that can represent and manipulate integers of **any size**, limited only by system memory. It mimics native integer behavior through **extensive operator overloading** and supports a rich set of mathematical operations including multiplication, division, exponentiation, square roots, factorials, and more.

---

## ✨ Key Features

### 🧮 Arithmetic Operations
- `+`, `-`, `*`, `/`, `%`: Full support for arbitrary-precision arithmetic
- `^`: Fast exponentiation (Exponentiation by Squaring)
- `sqrt()`: Integer square root using binary search

### ➕ Increment / Decrement
- `++a`, `a++`, `--a`, `a--`: Pre and post increment/decrement

### 📏 Comparison Operators
- `==`, `!=`, `<`, `>`, `<=`, `>=`: Digit-wise comparison

### 📥 Input / Output
- `>>`: Read BigInt from `cin` or input stream
- `<<`: Write BigInt to `cout` or output stream

### 📐 Helper & Utility Functions
- `Length(BigInt)`: Returns the number of digits
- `Null(BigInt)`: Checks if the number is zero
- `divide_by_2(BigInt&)`: Efficient binary division (used in exponentiation)

### 🔢 Combinatorial & Number Theory Functions
- `NthFibonacci(int n)`: Compute the n-th Fibonacci number
- `NthCatalan(int n)`: Compute the n-th Catalan number
- `Factorial(int n)`: Compute n!

---

## ✅ Complete Functionality Checklist

| Functionality                | Description                                             |
|-----------------------------|---------------------------------------------------------|
| `BigInt(string)`            | Constructor from string                                 |
| `BigInt(unsigned long long)`| Constructor from number                                 |
| `BigInt(const char*)`       | Constructor from C-string                               |
| `BigInt(BigInt&)`           | Copy constructor                                        |
| `operator=`                 | Assignment                                              |
| `operator[]`                | Access individual digit (0-indexed from least significant)|
| `operator+`, `operator+=`   | Addition                                                |
| `operator-`, `operator-=`   | Subtraction                                             |
| `operator*`, `operator*=`   | Multiplication                                          |
| `operator/`, `operator/=`   | Division                                                |
| `operator%`, `operator%=`   | Modulo                                                  |
| `operator^`, `operator^=`   | Power                                                   |
| `++`, `--`                  | Pre/Post increment/decrement                            |
| `operator==`, `!=`, `<`, `>`, `<=`, `>=` | All comparison operators                   |
| `operator<<`, `operator>>`  | Input and output stream operators                       |
| `Length(BigInt)`            | Returns number of digits                                |
| `Null(BigInt)`              | Check if BigInt is zero                                 |
| `divide_by_2(BigInt&)`      | Divide BigInt by 2 (internal use)                       |
| `sqrt(BigInt&)`             | Integer square root                                     |
| `NthFibonacci(int)`         | Compute the n-th Fibonacci number                       |
| `NthCatalan(int)`           | Compute the n-th Catalan number                         |
| `Factorial(int)`            | Compute factorial of n                                  |

---
