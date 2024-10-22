# The Bank Job

### Ready to pull off the ultimate bank heist... of coding skills? 💼💻

Welcome, junior developers! You’ve been hired by a very important client—a prestigious international bank. No pressure, right? 🏦 Your job? Build their entire customer-facing system, including everything from signing up for accounts to handling mortgages. 

But before you even start cracking the code, **Git** is your new best friend. Use it religiously; branches, issues, commits, the whole shebang. Oh, and don't forget your design toolkit **Figma** is a must before typing a single line of code. Ready to dive in? Let’s get to work!

---

## The Bank Services 🏦💳

Here’s what this fictional bank offers:

- **Current Accounts**
- **Savings Accounts** (No overdraft)
- **Joint Accounts** (Only available with an existing customer)
- **Junior Accounts** (No overdraft, linked to an adult’s account)
- **Mortgages** (Minimum term: 10 years)
- **Interest-Loans** (Low interest rates)
- **Payday-Loans** (Brace yourself for scandalous interest rates)

---

## Key Features to Implement 🚀

Your project should include the following functionality:

1. **Customer Registration & Account Creation**
   - Customers can sign up for one or multiple accounts.
   - Each customer is assigned a **customer number**, and each account receives an **account number** and **sort code**.
   
2. **Account Features**
   - Customers can:
     - **Deposit** and **withdraw** funds.
     - **Check balances**.
     - **Change their PIN** for any of their accounts.
   - **Overdrafts** will accrue interest daily (you decide the rates).

3. **Junior Accounts**
   - Must be linked to an adult's current or savings account. These accounts can’t exist on their own.

4. **Loans**
   - Customers can only apply for **interest loans** or **payday loans** if they have a current or savings account.

5. **Security**
   - Passwords must be **hashed**.
   - Implement **sessions** to manage secure login access.

6. **Additional Requirements**
   - **Error handling** for all user actions.
   - **User-friendly interface** and smooth user experience.
   - **Testing** for key functionality.
   - **Documentation**: Create both a **User Guide** and a thorough **README**.
   - **Deploy the project** on Heroku.

---

## The Customer Experience 🧑‍💻

Once registered, customers can:

- Sign up for one or more accounts with basic details (fabricated for this project).
- Get a **customer number**, create a password, and set a security question.
- Use the **password reset** feature if needed (via customer number + DOB, address, or security question).
- Log in to view a **summary of their accounts**. Each account should have a clickable link to view more details or recent activity.

---

## The Admin Portal 🛠️

Admins should have a powerful control center to:

- **Approve/deny** new accounts and **overdrafts**.
- **Review** account details and statuses.
- **Approve/deny mortgages**.
- **Modify/delete accounts**.
- **Lock accounts** due to suspicious activity.
- Generate reports on **new customers** and **financial summaries**.

---

## Tech Stack 🛠️

To build this system, you'll use:

- **Vanilla JavaScript** for the client-side
- **React** for a dynamic UI
- **Node.js with Express** for the backend
- **SQL** for the database

---

## Project Setup & Documentation 📄

Make sure to include a **README** that covers:

- A brief **description** of the project.
- The **goals and aims** of the application.
- The **contributor(s)**.
- A list of the **technologies** used.

To get up and running:

```bash
npm install  // To install all dependencies
// Include any required .env variables here
