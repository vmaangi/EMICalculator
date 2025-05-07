# EMICalculator
Calculator.java


---

# 📊 EMI Calculator – Java Program

This is a simple Java console application that calculates the **Equated Monthly Installment (EMI)** for a loan, based on the loan amount, annual interest rate, and tenure in years.

## 📌 Features

* Accepts user input for:

  * Loan amount (Principal)
  * Annual interest rate (in %)
  * Loan tenure (in years)
* Calculates:

  * Monthly interest rate
  * Total number of monthly payments
  * EMI using the standard formula
* Displays the calculated monthly EMI

## 📐 Formula Used

The EMI is calculated using the formula:

```
EMI = [P × r × (1 + r)^n] / [(1 + r)^n – 1]
```

Where:

* **P** = Principal loan amount
* **r** = Monthly interest rate (Annual interest rate / 12 / 100)
* **n** = Loan tenure in months (Years × 12)

## 💻 How to Run

1. Clone or download the repository.
2. Navigate to the project directory.
3. Compile and run the program using any Java IDE or terminal:

```bash
javac EMICalculator.java
java day4.EMICalculator
```

4. Follow the prompts to input loan details.

## 🧾 Sample Output

```
Please enter loan amount in USD
10000
Enter annual interest rate (in %)
7.5
Enter loan tenure in years
2
Your monthly EMI is: 450.44
```

## 🛠 Requirements

* Java Development Kit (JDK) 8 or later
* Basic knowledge of running Java programs

## 📁 File Structure

```
day4/
└── EMICalculator.java
```

## 🧠 Author

Developed as a practice exercise for understanding basic Java input/output, mathematical computations, and user interaction.

---


