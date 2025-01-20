# BigNum Class for Arbitrary-Precision Arithmetic

This project implements a `bigNum` class in C++ to handle arbitrary-precision arithmetic. The class supports operations like addition, subtraction, multiplication, and comparisons between large numbers, as well as between a `bigNum` and a `long` integer.

---

## Features

- **Arbitrary-Precision Arithmetic**:
  - Supports addition (`+`), subtraction (`-`), and multiplication (`*`) for large numbers.
  - Handles operations between two `bigNum` objects and between a `bigNum` and a `long` integer.

- **Comparison Operators**:
  - Supports comparison operators (`>`, `<`, `>=`, `<=`, `==`, `!=`) for `bigNum` objects and between a `bigNum` and a `long` integer.

- **Compound Assignment Operators**:
  - Supports compound assignment operators (`+=`, `*=`) for `bigNum` objects.

- **Indexing**:
  - Allows accessing individual digits of a `bigNum` using the `[]` operator.
  - Throws an `out_of_range` exception if the index is invalid.

- **Input/Output**:
  - Supports reading and printing `bigNum` objects with delimiters for better readability.
