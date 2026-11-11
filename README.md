# Inverted Pattern Generator (`mx8.py`)

A simple Python script built to practice **nested `for` loops** and pattern printing.

## How it Works
The program generates an inverted triangle pattern combining asterisks (`*`) and descending row numbers:
* **Outer Loop:** Counts backward from `5` down to `1` to control the total number of rows.
* **Inner Loop:** Prints `*` followed by the current row number on the same line using `end=' '`.
* **Line Break:** Moves to a new line after each row finishes printing.

## Concepts Learned
* Using `range()` with a negative step (`5, 0, -1`) to count backward.
* Controlling inline output formatting with the `end` parameter in `print()`.
* Nesting loops to build grid and pyramid patterns.
  
