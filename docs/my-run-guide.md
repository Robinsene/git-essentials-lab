# Run guide

## Prerequisites

- JDK 17 or later (`java` and `javac` on your PATH)
- Python 3.9 or later
- Git, to clone this repository

## Run the demo

From the repository root:

```text
python3 run.py demo
```

On Windows, use `py -3 run.py demo` if that is how you run Python 3.

## What the demo does

The runner compiles the Java library application into a temporary directory and runs a short scenario: it builds a small catalog, lets members borrow and return books under the current borrowing limits and loan period, computes overdue fees, and prints a loan receipt.
