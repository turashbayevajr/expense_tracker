# Expense Tracker

This is a simple web-based Expense Tracker application that allows users to input, track, and calculate their expenses. The application is built using HTML, Bootstrap for styling, and vanilla JavaScript for functionality. Expenses can be recorded in either USD or KZT (Kazakhstan Tenge), and the total can be calculated and displayed in either currency.

## Features

- **Expense Form**: Add expenses with date, amount, currency (USD or KZT), category, and an optional comment.
- **Local Storage**: Expenses are saved to the browser's `localStorage`, so they persist even after the page is refreshed.
- **Currency Conversion**: Enter the current exchange rate from USD to KZT to calculate the total expenses in your chosen currency.
- **Responsive Design**: The page layout is responsive and works well on both desktop and mobile devices.

## Installation

No installation is required. Simply download or clone the repository and open `index.html` in your web browser.

## Usage

1. **Add an Expense**:
   - Enter the date of the expense.
   - Input the amount spent.
   - Select the currency (USD or KZT).
   - Choose a category (Food, Transport, Entertainment).
   - Optionally, add a comment about the expense.
   - Click the "Add Expense" button to save the expense.

2. **View Expenses**:
   - The added expenses will appear in a list below the form.

3. **Calculate Total Expenses**:
   - Click the "Calculate" button to enter the current exchange rate (1 USD to KZT).
   - Choose the currency (USD or KZT) to display the total expenses.
   - The total amount will be displayed below the expense list.

## Example

### Add Expense

- **Date**: 2024-09-10
- **Amount**: 100
- **Currency**: USD
- **Category**: Food
- **Comment**: Groceries

### Calculate Total

- **Exchange Rate**: 1 USD = 480 KZT
- **Display in KZT**: Total: ₸48,000

## Dependencies

- **Bootstrap 5.3**: For styling and responsive design.
- **JavaScript**: Vanilla JavaScript for handling form submissions, localStorage, and calculations.


