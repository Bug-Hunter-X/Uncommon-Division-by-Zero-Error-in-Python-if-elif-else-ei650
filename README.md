# Uncommon Division by Zero Error in Python if-elif-else
This repository demonstrates a subtle error related to division by zero in Python, specifically when using if-elif-else control flow statements.  The code appears to handle zero division cases, but fails due to the order of evaluation. 
The `bug.py` file contains the erroneous code, and `bugSolution.py` provides the corrected version.

The key takeaway is to be mindful of the execution order when handling multiple conditional checks involving potential division by zero, especially in nested or complex statements.