# Expense-Tracker
The code defines an ExpenseTracker class to manage expenses and categories. It provides a menu-driven interface for adding expenses, categories, and viewing expense summaries.

Here's a step-by-step description of the provided code:

ExpenseTracker Class:
Initializes with empty dictionaries expenses and categories to store expenses and categories, respectively.

add_expense Method:
Adds an expense to the expenses dictionary.
If the category doesn't exist, it creates a new key in the expenses dictionary with an empty list.
Then, it appends a tuple (date, amount) to the list corresponding to the category.

add_category Method:
Adds a new category to the categories dictionary if it doesn't already exist.

view_expenses Method:
Iterates through each category in expenses and calculates the total amount for that category.
Prints the category along with its total amount formatted as currency.

view_categories Method:
Prints all the categories available in the expenses dictionary.

main Function:
Initializes an instance of ExpenseTracker named tracker.
Enters a while loop that displays the Expense Tracker Menu until the user chooses to exit.
Displays a menu with options to add expenses, add categories, view expenses, view categories, or exit.
Depending on the user's choice, it calls the respective methods of the ExpenseTracker class.
If the user chooses to exit, it breaks out of the loop and prints a goodbye message.

User Input Handling:
Handles user input within the main loop to execute different functionalities based on the chosen menu option.
This code provides a simple expense tracking system with options to add expenses, add categories, view expenses by category, view existing categories, and exit the program.

DEMO:

![image](https://github.com/arshasuresh03/Expense-Tracker/assets/160167081/48e448f0-7d2f-495f-ad59-186cacb48cfc)

![image](https://github.com/arshasuresh03/Expense-Tracker/assets/160167081/c6d7554b-7b0d-4a52-b3e1-63f23644ab38)

