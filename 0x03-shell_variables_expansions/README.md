# Shell Scripting Project – Environment and I/O Operations

This repository contains a collection of Bash scripts designed to manipulate environment variables, handle basic I/O operations, and demonstrate shell scripting logic under strict constraints.

## 📜 General Requirements

- All scripts are written using `vi`, `vim`, or `emacs`.
- Scripts are tested on **Ubuntu 20.04 LTS**.
- Each script:
  - Has exactly **two lines**.
  - Starts with `#!/bin/bash`.
  - Ends with a newline.
  - Is executable.
- **Disallowed**: `&&`, `||`, `;`, `bc`, `awk`, `sed`.

---

## 📂 Script Descriptions

| Script Name              | Description |
|--------------------------|-------------|
| `2-create_global_variable` | Creates a global (exported) variable `BEST` with value `"School"`. |
| `3-create_local_variable`  | Creates a local variable `BEST` with value `"School"`. |
| `4-global_variables`       | Prints all environment variables. |
| `5-local_variables`        | Displays all shell variables, environment variables, and functions. |
| `8-true_knowledge`         | Adds `128` to the value of `$TRUEKNOWLEDGE` and prints the result. |
| `9-divide_and_rule`        | Divides `$POWER` by `$DIVIDE` and prints the result. |
| `10-love_exponent_breath`  | Raises `$BREATH` to the power of `$LOVE` and prints the result. |
| `11-binary_to_decimal`     | Converts a binary number (`$BINARY`) to decimal and prints the result. |
| `12-combinations`          | Prints all combinations of two lowercase letters, excluding `oo`. |
| `13-print_float`           | Prints the value of `$NUM` with two decimal places. |
| `100-decimal_to_hexadecimal` | Converts a decimal number (`$DECIMAL`) to hexadecimal. |
| `101-rot13`                | Applies ROT13 encryption to input text. |
| `102-odd`                  | Prints every other line from input, starting with the first. |
| `103-water_and_stir`       | Adds two numbers from custom bases (`WATER`, `STIR`) and outputs the result in base `bestchol`. |
| `2-path`                   | Appends `/action` to the end of the `PATH`. |
| `3-paths`                  | Counts the number of non-empty directories in the `PATH`. |

---

## 🧪 Usage

Before running the scripts:
```bash
chmod +x script_name
