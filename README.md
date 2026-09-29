# SpendWise - JavaScript Foundation

## Project Description

SpendWise is a simple budget tracking application that helps users keep track of their monthly budget and expenses. The project uses HTML and CSS for the page structure and design, while JavaScript is used to collect information, perform calculations, and display the results.

## JavaScript Concepts Implemented

This project demonstrates several JavaScript concepts learned this week:

* Variables
* Data types
* User input
* Number conversion
* Calculations
* Functions
* Conditional statements
* Console output
* DOM manipulation

## How Variables Are Used

Variables are used to store important budgeting information. The project uses `budget` to store the user's monthly budget, `totalExpenses` to store the total amount spent, and `remainingBalance` to store the amount left after expenses are deducted.

## How User Input Is Collected

The application uses JavaScript's `prompt()` function to collect information from the user. The user enters their monthly budget and total expenses. Since `prompt()` returns the input as text, the `Number()` function is used to convert the values into numbers before calculations are performed.

## How Calculations Are Performed

SpendWise calculates the remaining balance by subtracting total expenses from the monthly budget.

The calculation is:

`Remaining Balance = Budget - Total Expenses`

For example, if the budget is KSh 50,000 and expenses are KSh 30,000, the remaining balance will be KSh 20,000.

## How Functions Organize the Code

Functions help organize the JavaScript code into reusable sections. The `calculateRemainingBalance()` function performs the budget calculation, while the `startBudget()` function collects user input, checks the values, performs the calculation, and displays the results.

Using functions makes the code easier to understand, maintain, and reuse.

## How to Run the Project

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Click the **Enter Budget Information** button.
5. Enter your monthly budget when prompted.
6. Enter your total expenses.
7. View the budget summary on the page.
8. Open the browser Developer Tools and select the **Console** tab to see the labeled JavaScript results.

## Testing

The application was tested by entering different budget and expense amounts. The calculation correctly subtracts expenses from the budget and displays the remaining balance. Invalid text input is also checked and an error message is displayed.

## Project Files

* `index.html` - Contains the structure of the SpendWise webpage.
* `style.css` - Contains the styling and layout.
* `script.js` - Contains the JavaScript functionality.
* `README.md` - Explains the project and how it works.
