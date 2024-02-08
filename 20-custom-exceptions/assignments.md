#### Write a Java program that reads the contents of a file and prints them to the console. However, you must ensure that the file is closed properly after reading, even if an exception occurs during the reading process. Utilize try-with-resources for handling the file input stream.

#### Write a Java program to implement the following:
    - Define a BankAccount class with the following attributes:
        balance: a double representing the current balance in the account.
    - Implement a constructor for the BankAccount class that initializes the balance.
    - Implement a withdraw method that takes a double amount as a parameter and performs the withdrawal operation. This method should:
        
        Throw a custom exception InsufficientFundsException if the withdrawal amount exceeds the balance.

        Throw a custom exception InvalidWithdrawalException if the withdrawal amount is negative.

    - Define two custom exceptions:

        InsufficientFundsException: thrown when a withdrawal amount exceeds the balance.

        InvalidWithdrawalException: thrown when a withdrawal amount is negative.

    - Write a Main class to demonstrate the functionality of the BankAccount class. Create instances of BankAccount and perform withdrawals, catching and handling any custom exceptions that may occur.

Your program should demonstrate the following scenarios:

    Successful withdrawal.
    Attempting to withdraw more money than the account balance.
    Attempting to withdraw a negative amount.