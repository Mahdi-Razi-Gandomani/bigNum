# BigNum Class for Arbitrary-Precision Arithmetic

This project implements a `bigNum` class in C++ to handle arbitrary-precision arithmetic. The class supports operations like addition, subtraction, multiplication, and comparisons between large numbers, as well as between a `bigNum` and a `long` integer, enabling operations on integers much larger than those natively supported by standard data types like `int`, `long`, or even `long long`.

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

---


### Example Output

```
a = 25,232,345
b = 285,293,475,283,945,729,834,502,394,823,452,345,923
a + b = 285293475283945729834502394823477578268
a - b = -285293475283945729834502394823427113578
a * b = 7196896015364027587683468768122188700937551956355

long c = 21342
a + c = 25253687
a - c = 25211003
a * c = 538277871090

25232345 < 285293475283945729834502394823452345923
25232345 <= 285293475283945729834502394823452345923
25232345 != 285293475283945729834502394823452345923

a += b -> a =  285293475283945729834502394823477578268
b *= 2 -> b = 570586950567891459669004789646904691846
```
