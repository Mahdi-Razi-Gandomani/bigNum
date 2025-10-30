## BigNum Class for Arbitrary-Precision Arithmetic

- This project implements a `bigNum` class in C++ to handle arbitrary-precision arithmetic, enabling operations on integers much larger than those natively supported by standard data types like `int`, `long`, or even `long long`. 

---

## Overview

The `bigNum` class allows mathematical operations, comparisons, and formatted output for very large integers represented as strings.  
It provides a simple interface for performing arithmetic operations (+, -, *) and comparisons between two big numbers or between a big number and a built-in integer type.

---

## Features

- Handles **integers of arbitrary size**.
- Supports both **positive and negative** numbers.
- Arithmetic operations:
  - Addition (`+`, `+=`)
  - Subtraction (`-`, `-=`)
  - Multiplication (`*`, `*=`)
- Comparison operators:
  - `>`, `<`, `>=`, `<=`, `==`, `!=`
- Works with both `bigNum` and `long` types.
- Overloaded stream operators (`>>`, `<<`) for easy input/output.
- Includes a **digit access operator** (`[]`) for indexing digits. Throws an `out_of_range` exception if the index is invalid.
- Pretty-print feature with **comma delimiters** (`printDelimiter()`).
