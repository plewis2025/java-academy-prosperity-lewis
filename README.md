# JAVA-ACADEMY--PROSPERITY-LEWIS
Starbucks Finance Calculators
Just like choosing between a grande caramel macchiato today or saving for a Starbucks gift card tomorrow, these calculators help you decide whether to spend, save, or invest.

Calculator 2 – Compound Interest (CD Future Value)
 Example Run
Enter deposit amount (principal): 1000
Enter annual interest rate (in %): 1.75
Enter number of years: 5

Future Value: $1091.44
Total Interest Earned: $91.44

Calculator 3 – Present Value of an Ordinary Annuity
 Example Run
Enter monthly payout: 3000
Enter annual interest rate (in %): 2.5
Enter number of years: 20

Present Value of the annuity: $566141.46

 Error Handling Example

If a user accidentally types “latte” instead of a number, our program responds kindly instead of crashing:

Enter deposit amount (principal): latte
 Error: Please enter a valid number (no text like 'latte')!

 Interesting Code Snippet
double PV = PMT * (1 - Math.pow(1 + i, -n)) / i;


 Why interesting?

This single elegant line does the entire annuity math, no loops needed.

It shows the power of Java’s Math library — we compress what would be hundreds of manual steps into one neat calculation.

 How to Run

Open the project in IntelliJ IDEA.

Compile the program with the green  button.

Enter the values when prompted in the console.

Enjoy your “financial brew”! ☕💰
