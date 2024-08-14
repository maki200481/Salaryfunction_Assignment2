Overview
This repository contains scripts for analyzing employee salary data using Python and R. The Python script processes and exports data, while the R script reads the exported data for further analysis.

Setup
Prerequisites
Python 3.x
R
Libraries
Python: pandas
R: No additional libraries required beyond the default installation.
Installation
Install required Python libraries using pip:

bash
Copy code
pip install pandas
Files
SalaryAnalysis.ipynb: Jupyter Notebook for data processing in Python.
DataAnalysis.R: R script for reading the data.
Usage
Run SalaryAnalysis.ipynb in Jupyter Notebook to process and export the salary data.
Execute DataAnalysis.R in RStudio or a similar R environment to read and display the exported data.
Example Commands
Python:

python
Copy code
# Calculate and print total payroll
print(f"Total Payroll: {calculate_total_payroll(employee_dict):.2f}")
R:

R
Copy code
# Display the employee data
print(read.csv("unzipped_files/CHRISTOPHER CHONG.csv"))
