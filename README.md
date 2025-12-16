## VMs Credentials Sheet

https://docs.google.com/spreadsheets/d/1_7eJDFbuqY_WVFAR1wqRJNfjiSehXFm9TYp_HkoAYhc/edit?gid=547734190#gid=547734190

## Important URLs

  1. https://github.com/
  2. https://hub.docker.com/
  3. https://colab.research.google.com/
  4. https://training.datacouch.io/pluralsight/



# Simple Arithmetic Calculator

This project is a simple arithmetic calculator implemented in Python. It provides basic mathematical operations such as addition, subtraction, multiplication, division, and modulus.

## Features

- **Addition**: Adds two numbers.
- **Subtraction**: Subtracts the second number from the first.
- **Multiplication**: Multiplies two numbers.
- **Division**: Divides the first number by the second. Raises an error if division by zero is attempted.
- **Modulus**: Computes the remainder of the division of the first number by the second. Raises an error if modulus by zero is attempted.

## Usage

1. Import the `calculator.py` module into your Python script.
2. Call the desired function with the required arguments.

### Example

```python
from calculator import add, subtract, multiply, divide, modulus

# Perform calculations
print(add(5, 3))        # Output: 8
print(subtract(5, 3))   # Output: 2
print(multiply(5, 3))   # Output: 15
print(divide(5, 3))     # Output: 1.666...
print(modulus(5, 3))    # Output: 2
```

## Requirements

- Python 3.6 or higher

## Testing

Unit tests are provided in the `test_calculator.py` file. To run the tests, use the following command:

```bash
pytest test_calculator.py
```

## License

This project is licensed under the MIT License.
