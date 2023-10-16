# OnlineBank
Basic Personal Banking web app: Log in, deposit, withdraw, see balance.

# Project Title: 
Online Bank

# Description and Motivation: 
The banking web app helps users to conduct basic banking transactions, such as deposits, withdrawals, and checking the account balance.  I built my Online Bank for a class, but I could see it developing into a tool to assist any business that involves logging in and managing an account.

# Installation Guidelines:
Git clone, git pull.  In the terminal, in the project's directory, run NPM init and node index.js.  Then navigate to localhost:3000 to interact with the app.

# Technology Used:
Front end: React.js with Bootstrap navigation bar and cards.
Server: Node and Express
Data store: Mongodb in a Docker container

# Features:
- Create account: Define a name, email, and password
- Log in: Log into an existing account using an email and password.
- Deposit: Define how much money to add to the account.
- Withdrawal: Define how much money to take out of the account.  (The app prevents the user from overdrawing on the account.)
- Balance: View the balance of your account.
- All Data: View a list of all of the bank's accounts.  This feature allowed the developer to see that accounts and features are working properly.

# License: 
MIT
