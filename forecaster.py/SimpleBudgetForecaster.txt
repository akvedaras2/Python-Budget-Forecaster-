#Okay test test test test 
# My Python Budget Forecaster

#1. Starting funds in account 
Balance = 5000

#2. Monthly Income 
Salary = 1750
Other_Income = 200
Total_Income = Salary + Other_Income

#3. Monthly Expenidtures 
Utilites = 200
Groceries = 300
Rent = 700 
Lifestyle = 50
Total_expenditure = Utilites + Groceries + Rent + Lifestyle

#4. Savings each month 
Monthly_savings = Total_Income - Total_expenditure

#5. Print 
print("Budget Forecast")
print("Starting Balance: £", Balance)
print("Total Monthly Income: £", Total_Income)
print("Total Monthly Expenses: £", Total_expenditure)
print("Money saved each month: £", Monthly_savings)

print("Forecast for the next 9 months:")
Months_forecasted = 9 

for month in range(1, Months_forecasted + 1):
    Balance = Balance + Monthly_savings
    print("Month", month, "- Projected Balance: £", Balance)



