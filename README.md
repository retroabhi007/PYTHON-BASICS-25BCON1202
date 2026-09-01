# PYTHON-BASICS-25BCON1202
BASIC PYTHON PROGRAM
```markdown
# Factorial Calculator

A lightweight, efficient Python script to compute the factorial of non-negative integers using an iterative approach.

---

## Features

* **Simple & Fast:** Computes factorials iteratively with minimal overhead.
* **No External Dependencies:** Runs natively using standard Python built-ins.
* **Beginner-Friendly:** Clear and readable syntax suitable for learning basic algorithms and loops.

---

## Requirements

* **Python:** Version 3.6 or higher

---

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/factorial-calculator.git](https://github.com/your-username/factorial-calculator.git)

```

2. Navigate to the project directory:
```bash
cd factorial-calculator

```



---

## Usage

Run the script directly via your terminal:

```bash
python factorial.py

```

---

## Example

The script computes the factorial for a specified integer $n$:

```python
n = 5
fact = 1

for i in range(1, n + 1):
    fact *= i

print(f"Factorial of {n} = {fact}")

```

**Output:**

```text
Factorial of 5 = 120

```

---

## License

This project is licensed under the [MIT License](https://www.google.com/search?q=LICENSE).

```

Would you like to extend `factorial.py` to accept dynamic user inputs from the command line (via `sys.argv` or `argparse`)?

```
