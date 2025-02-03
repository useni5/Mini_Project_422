# Mini_Project_422
Bank Account: The Account structure holds the account number, holder's name, and balance. Functions: The deposit, withdraw, and display functions perform operations on the account. Menu: The program provides options to deposit money, withdraw money, or view the balance.


Here are some sample test cases:

Here are 10 test cases for the bank account program, covering various scenarios, including edge cases and error conditions:

Valid Input Cases:

Normal Deposit and Withdrawal:

Account Number: 12345
Name: John Doe
Deposit: 1000
Withdrawal: 500
Expected Result: Balance should be 500.
Multiple Deposits and Withdrawals:

Account Number: 67890
Name: Jane Smith
Deposit: 200, 300, 100
Withdrawal: 150, 250
Expected Result: Balance should be 200.
Zero Deposit:

Account Number: 13579
Name: Peter Jones
Deposit: 0
Expected Result: Balance should remain 0.
Withdrawal Equal to Balance:

Account Number: 24680
Name: Alice Johnson
Deposit: 500
Withdrawal: 500
Expected Result: Balance should be 0.
Display without Transactions:

Account Number: 98765
Name: Bob Williams
Expected Result: Balance should be 0.
Invalid Input/Error Cases:

Invalid Account Number (Non-numeric):

Account Number: abcde
Expected Result: Error message for invalid input.
Invalid Deposit/Withdrawal Amount (Non-numeric):

Deposit: xyz
Expected Result: Error message for invalid input.
Insufficient Funds:

Account Number: 11223
Name: Eve Davis
Deposit: 100
Withdrawal: 200
Expected Result: "Insufficient balance" message.
Negative Deposit/Withdrawal:

Deposit: -100
Expected Result: Error message for invalid (negative) input.
Long Name:

Account Number: 55667
Name: ThisIsAVeryLongNameThatExceedsTheLimit
Expected Result: The program should handle this gracefully, either truncating the name or displaying an error message (depending on how you've implemented the name input). It should not crash. This tests for buffer overflows.
How to Use These Test Cases:

Run the program.
For each test case, provide the input values as specified.
Verify that the program's output matches the expected result. Pay close attention to error messages and how the program handles invalid input.
