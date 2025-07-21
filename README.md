# Selenium Data-Driven Login Automation (Python)

This project uses Selenium Webdriver with Python to perform a
**data-driven login test** on
[saucedemo.com] (https://www.saucedemo.com/).
Test data which includes usernames and passwords is stored in a CSV file. This CSV file is automatically looped
through to similar multiple login attempts
---

## Tools & Technologies
-Python 3.13
-Selenium Webdriver
-Firefox Browser
-CSV Module
-Time Module
-Pycharm
---

## Project Description
The script:
-Reads test credentials data from a 'testdata.csv' file
-Launches Firefox using Selenium WebDriver
-Navigates to 'http://www.saucedemo.com/'
-Enters each username and password into the login form
-Submits the form for each pair of credentials
-Repeats process for all rows in CSV file
---

## Test Case Overview
**Test Case:** Attempt login using multiple username/password combinations
**Test Data Source:** 'testdata.csv'

**Example CSV Structure:**

'''csv
username,password
standard_user,secret_sauce
locked_out_user,secret_sauce
problem_user,secret_sauce

How to run the test
1. Clone this repository (https://github.com/MrMGaines/AutomationDemo.git)
2. Navigate into the folder: cd DataDrivenTestingUsingCSVFilePortfolio.py
3. Install Selenium
4. Ensure Firefox is installed and in your system path
5. Run the script: DataDrivenTestingUsingCSVfilePortfolio.py

