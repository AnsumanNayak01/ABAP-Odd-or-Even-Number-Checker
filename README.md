# ABAP Odd or Even Number Checker (`ZCHECK_ODD_EVEN`)

A clean and optimized SAP ABAP snippet designed to check whether a given integer is **odd** or **even**, complete with input validation.

---

### Overview

This program takes a short integer input, checks if the value is provided, and uses the modulo operator to evaluate parity.

* Integer Input — collects a numeric value using type short integer (`TYPE int2`).
* Empty Check Validation — checks if the input is initial using `IS INITIAL` and displays an informational message.


* Modulo Operation — uses `MOD` alongside `EQ` and `<>` operators to evaluate remainders safely.


* Output Logging — displays the result directly on the screen.



---

### How It Works

* Parameters & Data: `p_num` collects the user integer input (`int2`).


* Validation Logic: Evaluates if `p_num` is left blank, triggering a message popup if no value is provided.


* Parity Logic: Divides the input number by 2, classifying the result as `EVEN` if the remainder is zero, or `ODD` otherwise.



---

### Installation & Execution (SAP GUI)

1. Open transaction **`SE38`** or **`SE80`**.
2. Create an executable report program named `ZCHECK_ODD_EVEN`.
3. Paste the provided code, save (`Ctrl + S`), activate (`Ctrl + F3`), and execute (`F8`).

---

### Attribution & Acknowledgements

* **Purpose:** Created and shared for educational and portfolio demonstration purposes.
