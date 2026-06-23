# Python Budget Forecaster 

This is a simple script I wrote to help predict a bank balance over a few months. It takes basic income and expenses, figures out the monthly savings, and runs a loop to show what the bank account will look like in the future.

I built this as a beginner project to practice using Python variables, basic math operations, and `for` loops.

# How to use it
Right now, the numbers are written directly into the code. 

1. Open `forecaster.py` in any text editor.
2. Change the variables at the top (like `Balance`, `salary`, `rent`, etc.) to match your own numbers.
3. Open your terminal or command prompt and run: `python forecaster.py`

The script will print out a summary of your monthly cash flow and a month-by-month prediction of your savings. You can also change the `Months_forecasted` variable to predict as far into the future as you want.

# Limitations 
This is my first iteration of this project, so it intentionally uses basic scripting.
* It predicts that each monthly expenditure would remain the same throught all of the forecasted months. Therefore I do plan on having 'Dynamic Vaiables' in a future project 
* Addiotnally it's not very efficient since the user would have to manually change the values of their income, expenditures etc. 