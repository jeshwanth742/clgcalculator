##  **University Grade Point Average Calculator**

This Python script calculates Semester Grade Point Average (SGPA) and Cumulative Grade Point Average (CGPA) for a list of courses.

**Features:**

* Calculates SGPA and CGPA based on course credits and grade points.
* Provides percentage equivalents for SGPA and CGPA (assuming a 10 point grading scale).
* Well-documented and easy to understand code.

**Requirements:**

* Python 3.x

**Usage:**

1. Clone or download this repository.
2. Modify the `courses` list in the script (`calculate_gpa.py`) to include your course information:
    - Each course should be a dictionary with "credit" (integer) and "grade_point" (float) keys.
3. Run the script using `python calculate_gpa.py`.

**Example Usage:**

```
SGPA: 3.67 (91.75%)
CGPA: 3.67 (91.75%)
```

**How it Works:**

The script defines three functions:

1. `calculate_total_gp_and_credit`: Calculates the total grade points and total credits from a list of courses.
2. `calculate_sgpa`: Calculates SGPA and its percentage equivalent based on total grade points and total credits.
3. `calculate_cgpa`: Calculates CGPA and its percentage equivalent based on total grade points and total credits (similar to `calculate_sgpa`).

**Contribution:**

Feel free to modify the script to fit your specific needs. Pull requests are welcome!
