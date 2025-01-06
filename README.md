Highridge Construction Company Payment Slips Program
=====================================================
This Python program and R application will allow Highridge Construction Company to pay its workers on a weekly basis. As a hired software engineer, the tasks are to create a worker list dynamically, assign employee levels based on conditions, add error handling in, convert the program into R, and package it for submission.
Installing and Running the Program
1. Prerequisites
You need to have Python 3.x and R installed.
In Python, no external packages are needed since only default modules are used.
2. Running the Application
Python: The script of payment_slips.py should be run in order to carry out the generation of the payment slips.
R: You can do the same operations in R by running the payment_slips.R file.

Steps to Complete the Assignment
Step 1: Python Program Development
I drafted a Python program for implementing the specified tasks, from creating a worker list to assigning levels based on salary and gender conditions.
Step 2: Dynamic Generation of the List of Workers
Based on the use of Python dictionaries and loop,  I generated a list of at least 400 workers . Each worker had attributes, namely:
name: a unique identifier such as "Worker_1"
gender: randomly assigned as "M" or "F
salary: Random integer between $7,500 and $30,000
Step 3: Creating Pay Slips Using a For Loop
A for loop will run across the workers list to generate the slip of each worker that includes:
name
gender
salary
employee level (this was assigned based on specific conditions)
Step 4: Apply Conditional Statements
The code uses conditional statements to implement the following logic on employees in order to assign employee levels:
In case the worker's salary falls in between $10,000 and $20,000, the Employee level is marked as "A1."
If the worker's salary falls between $7,500 and $30,000, and the worker is female, then Employee level is "A5-F."
All other workers are given the Employee level "Standard."
Step 5: Add Exception Handling
Exception handling is put in place to handle such potential errors as:
Invalid data types for either salary or gender.
Missing data for any one of the worker's attributes.
Each exception that is caught and reported will enable the program to continue processing other employees.
Step 6: Convert the Code to R
The same logic developed in the Python program was converted to R. The same sequence of steps was followed and conditions according to the problem statement. The R code - payment_slips.R consists of the following:
Creation of a data frame for the workers.
Conditional statements based on if and else if Statements.
Error handling to manage any potential errors during the iteration using tryCatch.
This program assigns random values for each worker, so the results will be different every time this program is run.
The code is modular, easy to modify. For example, one can easily change the number of workers or conditions by simply editing the code.

  
total.csv.zip_data = pd.read_csv('total.csv.zip')
