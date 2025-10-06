# Python Simple Banking Program

This is a straightforward console-based banking program written in Python, designed for beginners to understand basic programming concepts such as input handling, conditional statements, loops, and functions. The program simulates a simple banking system where a user can manage their account balance with core functionalities.

## How It Works

1. **Menu-driven Interface:** The program runs a continuous loop, presenting the user with options to:
   - Show current balance
   - Deposit money
   - Withdraw money
   - Exit the program

2. **Balance Tracking:** The balance is maintained in a variable initialized at zero and updated based on deposits and withdrawals.

3. **Deposits:** When the user chooses to deposit, the program asks for an amount and verifies it is greater than zero before adding it to the balance.

4. **Withdrawals:** Before allowing a withdrawal, the program checks that the requested amount is positive and does not exceed the current balance, preventing overdrafts.

5. **Input Validation:** The program handles invalid numeric inputs by rejecting negative or zero amounts for deposits and withdrawals, and invalid menu choices display error messages prompting correct input.

6. **Program Exit:** Users can exit the loop and end the program by selecting the exit option.

## Why It Works

- **Modular Design:** The use of separate functions for displaying balance, handling deposit, and handling withdrawal promotes clear structure and easy maintenance.

- **Consistent Validation:** Input checks ensure program robustness by preventing invalid transactions, such as withdrawing more than the available funds or depositing non-positive amounts.

- **User-friendly Feedback:** Clear print statements guide the user through the available options and alert them when input errors occur.

## Educational Value

This program demonstrates fundamental programming principles:
- Use of input/output functions
- Control flow with conditional branches
- Looping for persistent menu display
- Simple arithmetic and variable updates
- Basic user input validation

It’s ideal for beginners learning to combine these concepts into a functional application.

## How to Use

Simply run the program. Follow the on-screen menu prompts:
- Enter `1` to check your balance.
- Enter `2` to deposit money.
- Enter `3` to withdraw money.
- Enter `4` to exit.

Users receive feedback after every operation, and invalid inputs are handled gracefully.
