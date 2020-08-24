# the-bank-job

You have been hired by the owner of a international bank. They have many services that they offer to the public:

* Current Accounts
* Savings Accounts **(No overdraft facility)**
* Junior Accounts **(No overdraft facility)**
* Mortgages **(Minimum 10-year contract)**
* Interest-Loans **(Low interest)**
* Payday-Loans **(scandalously high interest)**

## Things to think about

1. A customer may want to select one or multiple options when signing up. They will be assigned a customer number and an **account number** with a **sort code** for each account that they take out
2. They need to be able to withdraw, deposit, check their balance, change their pin number for the accounts that they have access to
3. An overdraft will add interest for each day that it is active. You can choose the interest rates
4. A junior account can be taken out in a child's name but will be associated with an adult current / savings account. It cannot be opened on its own.
5. An interest-loan / payday-loan can only be taken out if they have a current or savings account.

## Technologies needed: 

* Vanilla JS
* React or HBS
* Node w/ Express
* MongoDB or SQL
