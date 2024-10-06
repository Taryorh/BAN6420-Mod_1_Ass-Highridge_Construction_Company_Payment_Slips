# BAN6420-Mod_1_Ass-Highridge_Construction_Company_Payment_Slips

# Highridge Employee Payment Slip Generator

## Overview
This project consists of Python and R scripts that generate a list of 400 employees and create payment slips for each employee based on their attributes (name, gender, salary, and department). Employee levels are determined based on conditional logic applied to the salary and gender.

## Python Code
The Python code is split into two files:

1. **`highridge_class.py`**: Contains the `HighridgeProcessor` class that generates employees and payment slips.
2. **Main Script called paymentslip_generator**: Instantiates the `HighridgeProcessor` and generates the payment slips.

### How to Run the Python Script:
1. Ensure you have Python 3.x installed.
2. Install the required libraries using `pip install logging`.
3. Create a `logs` folder in the same directory as the Python files.
4. Make sure there is a `paymentslip.log` file inside the `logs` folder (or create one if it doesn’t exist).
5. Run the main Python script.

```bash
python main_script.py
