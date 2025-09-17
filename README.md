# Employee Processing Function
# Authur: Kayode Ogunyemi 
# Nexford University (MSc Data & Analytics)
# Module 2 Assignment 
# 17th September, 2025



## Overview
Python and R scripts for handling salary data, and managing employee profiles.

---

## Features
- Import salary data dynamically.
- Store employee details in a Python dictionary.
- Error handling for invalid or missing employee details.
- Export employee details to CSV.
- Save files inside a zipped folder (`Employee Profile`).
- R script to unzip and view employee details.

---

## Project Structure
```
├── Employee_Payment.ipynb       # Jupyter Notebook with all tasks
├── Employee Profile.zip         # Zipped folder with exported employee details
├── R_unzip_script.R             # R script to unzip and display employee data
└── README.md                    # Project documentation
```

---

## How to Run

### 1. Python (Jupyter Notebook)
- Install dependencies:
  ```bash
  pip install pandas
  ```
- Open the Jupyter Notebook:
  ```bash
  jupyter notebook Employee_Payment.ipynb
  ```

### 2. Export Employee Profile
- Run the export cell to generate a CSV file.
- The details will be saved in the `Employee Profile` zipped folder.

### 3. R Script
- Use R to unzip the folder and view employee data:
  ```R
  unzip("Employee Profile.zip", exdir = "Employee_Profile")
  data <- read.csv("Employee_Profile/employee_details.csv")
  print(data)
  ```

---
