# Calculator Project with CI/CD

![CI/CD Pipeline](https://github.com/anyanikolskaya2111-art/ci-cd-practice/actions/workflows/ci.yml/badge.svg)

## Functions

| Function | Description |
|----------|-------------|
| `add(a, b)` | Returns a + b |
| `subtract(a, b)` | Returns a - b |
| `multiply(a, b)` | Returns a * b |
| `divide(a, b)` | Returns a / b (or None if b=0) |
| `power(a, b)` | Returns a ** b |

## Run Locally

```bash
pip install -r requirements.txt
pytest test_calculator.py -v
