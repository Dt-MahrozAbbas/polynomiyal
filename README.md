

# Polynomial Operations in Python

This repository contains a Python script for working with polynomials. The script allows users to create polynomials, set coefficients, evaluate polynomial expressions, and display polynomials in a readable format.

## Features

- **Create Polynomials:** Define polynomials of any degree.
- **Set Coefficients:** Assign coefficients to specific powers of the polynomial's variable.
- **Evaluate Polynomials:** Compute the value of a polynomial for a given input.
- **Display Polynomials:** Print the polynomial in a mathematical format.

## File Overview

### `polynomial1.py`

This file defines the following functionality:

1. **`createPolynomial(degree)`**
   - Creates a polynomial object with a specified degree.
   - Initializes coefficients to 0 and sets the variable as 'x'.

2. **`setCoefficient(polynomial, power, coefficient)`**
   - Sets the coefficient for a specific power of the polynomial.

3. **`printPolynomail(polynomial)`**
   - Prints the polynomial in a human-readable format, such as:
     ```
     -2x^3 + 5x^2 - 1
     ```

4. **`value(polynomial, x)`**
   - Evaluates the polynomial for a given value of `x`.

5. **`main()`**
   - Demonstrates how to create and manipulate a polynomial.
   - Example: Creating a polynomial `-2x^3 + 5x^2 - 1` and evaluating it for `x = 1`, `x = 2`, and `x = -5`.

## Example Usage

Here's how the script works:

```python
e = createPolynomial(3)
setCoefficient(e, 3, -2)
setCoefficient(e, 2, 5)
setCoefficient(e, 0, -1)
printPolynomail(e)
print(value(e, 1))  # Outputs the polynomial value at x = 1
print(value(e, 2))  # Outputs the polynomial value at x = 2
print(value(e, -5)) # Outputs the polynomial value at x = -5
```

Expected output:
```
-2x^3 + 5x^2 - 1 
2
-9
-616
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/polynomial-operations.git
   cd polynomial-operations
   ```

2. Run the script:
   ```bash
   python polynomial1.py
   ```

## Requirements

- Python 3.x