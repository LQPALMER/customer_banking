# customer_banking
[M3_Starter_Code (1).zip](https://github.com/user-attachments/files/15934730/M3_Starter_Code.1.zip)

"""Import the Account class from the Account.py file."""
from Accounts import Account


# Define a function for the Savings Account

def create_savings_account(balance, interest_rate, months):
    # Create an instance of the Account class with balance and interest_rate parameters
    account = Account(balance, 0, )  
    balance = 1000
interest_rate = 5
savings_account_instance = SavingsAccount(balance, interest_rate)


       # Set the updated balance and interest earned using the Account class methods
account.set_balance(updated_balance)
account.set_interest(interest_earned)

  
    # Create an instance of the `Account` class and pass in the balance and interest parameters.
account_instance = Account(balance, interest)

    # Calculate interest earned
interest_earned = balance * (interest_rate/100 * months/12)

    # Update the savings account balance by adding the interest earned
updated_balance = balance + interest_earned

    # Pass the updated_balance to the set balance method using the instance of the SavingsAccount class.
savings_account_instance.set_balance(updated_balance)

    # Pass the interest_earned to the set interest method using the instance of the SavingsAccount class.
savings_account_instance.set_interest(interest_earned)

    # Return the updated balance and interest earned.
return updated_balance, interest_earned

