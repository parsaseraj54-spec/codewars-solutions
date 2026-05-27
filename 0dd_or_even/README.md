# Odd or Even Checker 🔢

A simple Python function that checks whether the sum of a list of numbers is odd or even.

---

## Features

- ➕ Calculates the sum of a list
- 🔢 Checks if the sum is odd or even
- ⚡ Returns a simple result as a string

---

## How It Works

The function:

1. Takes a list of numbers as input
2. Calculates the total sum using `sum()`
3. Checks if the sum is divisible by 2
4. Returns `"even"` or `"odd"`

---

## Example

```python
odd_or_even([1, 2, 3, 4])
```

Output:

```text
even
```

---

## Code Overview

```python
def odd_or_even(arr):
    total = sum(arr)
    
    if total % 2 == 0:
        return "even"
    else:
        return "odd"
```

---

## Concepts Practiced

- Functions
- Lists
- Built-in functions (`sum`)
- Conditional statements
- Modulo operator (`%`)
- Return values

---

## Possible Improvements

- Handle empty lists
- Return `"invalid input"` for non-numeric values
- Extend to return both sum and parity
- Convert into a CLI tool

---

## Author

Made with Python by **Parsa**