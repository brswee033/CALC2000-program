# CALC2000 – CIS352 Chapter 1 Assignment

## 📘 Overview
This project is a modified version of the **CALC2000** COBOL program from Chapter 1.  
The program calculates the future value of an investment using a fixed interest rate and number of years.  

Instead of accepting user input at runtime, this version uses predefined input values and runs the calculation multiple times while increasing the investment amount.

---

## 🧮 What the Program Does
- Uses a fixed investment amount, interest rate, and number of years
- Calculates the future value of an investment
- Runs the calculation three times
- Doubles the investment amount before each new calculation
- Displays formatted output for easy reading

---

## ⚙️ Default Input Values
The program uses the following predefined values:

- Initial Investment Amount: 1000  
- Number of Years: 10  
- Yearly Interest Rate: 5.5%

---

## 🖥️ Program Output
The program displays:
- Program header information
- Investment amount
- Number of years
- Interest rate
- Calculated future value


---

## 🆕 New Concepts Used
- Removing `ACCEPT` statements and using initialized input values
- Numeric edited data items for formatted output
- `COMPUTE` statements for calculations
- Structured paragraph calls using `PERFORM`
- Separation of calculation logic and display logic

