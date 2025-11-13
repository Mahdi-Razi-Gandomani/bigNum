## BigNum

- This project implements a `bigNum` class in C++ to handle integers much larger than those natively supported by standard data types like `int`, `long`, or even `long long`. 

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
