# Array Practice (C++)

A C++ exercise implementing four functions over arrays of strings, with an
assertion-based test driver.

## Functions
| Function | Description |
|----------|-------------|
| `locateMaximum(arr, n)` | Index of the lexicographically greatest string. |
| `countFloatingPointValues(arr, n)` | How many entries look like valid floating-point numbers. |
| `hasNoCapitals(arr, n)` | Whether no entry contains an uppercase letter. |
| `shiftLeft(arr, n, amount, placeholder)` | Shifts entries left by `amount`, filling the tail with `placeholder`; returns the number of placeholders inserted. |

## Build & Run
```bash
g++ -std=c++17 array.cpp -o array
./array
```
