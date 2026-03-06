# Simple Interest Calculator

## Description
This project is a Simple Interest Calculator. It computes the amount of interest accumulated over a specific period based on a principal amount, an annual interest rate, and the time the money is invested or borrowed for. 

## The Formula
The calculator uses the standard simple interest formula:

`Simple Interest (I) = (P * R * T) / 100`

Where:
* **P** = Principal amount (the initial amount of money)
* **R** = Annual interest rate (in percentage)
* **T** = Time (in years)

## Features
* Calculates the total simple interest.
* Calculates the total accumulated amount (Principal + Interest).
* Clear and straightforward logic.


```python
# Example of the logic used in this project
principal = 1000  # Initial amount
rate = 5          # Annual interest rate in %
time = 2          # Time in years

# Calculate simple interest
interest = (principal * rate * time) / 100
total_amount = principal + interest

print(f"Simple Interest: {interest}")
print(f"Total Amount: {total_amount}")
