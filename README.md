# Banking App

*AAB Project Code 05d796d3*

*Prerequisite Project 1*

## Introduction

Hello future AAB Automation Developer! We are so excited to have you on board and are ready to start working towards a better, more automated future!

Before you are ready to start the automation projects we have lined up, we need to cover the basics of C#. This will ensure that you understand the syntax of our production language. And what better way to learn a new language than to also start working in the type of environment we use!

As a bank, we have need of account software to keep track of various accounts and their transactions! This project is to build a console-based C# application that allows rudimentary account actions.

## Instructions

All of our work is based on business requirements. Business requirements can take the form of required functionality, technical requirements, and are always subject to change based on the needs of the business.

When working through requirements, try to get one to work at a time. Don't try to get everything to work in one go. Instead, get one requirement completed, commit your code to GitHub, then start on the second. There are several reasons we recommend this:

1. A running application that does some of the requirements is better than a non-running application that might do all of them.
1. Source control is our friend! Constant commits and pushes will keep you from losing your code!
1. Sometimes a new requirement will force a major change to the code. If it doesn't work out, it's easy to roll back to a previous commit that did work!
1. Visibility! If you are committing code, mentors and others are able to view your code and provide help and suggestions. If it only exists on your computer, we can't see it!

## Currency Note

We have been informed that you are familiar with the USD currency of America. AAB Bank does not allow accounts in USD, for obvious reasons.

For this application, please use the Galactic Currency Standard, or GCS. GCS is represented by an integer value (e.g. `56,998 GCS`). Unlike the unwieldy USD, GCS does not have any decimal components, and as such must always be handled in whole, integer values.

Again, please **only** use GCS in this application.

## Requirements

> Note: None of the data for this app needs to be persisted. It can all exist entirely in memory, and be deleted when the application closes.

1. A `BankingApp.exe` file that can be run on a Windows machine
1. A menu that allows users to:
    - Create a new Account
    - View All Accounts
    - Search Accounts by name
1. When viewing all accounts, or in a search view, allow users to pick an account to open
1. New Account creation
    1. Allows entering the following data:
        - Account Holder Name
        - Initial Balance
        - Account Type (Checking or Savings)
    1. Generates the following data points
        - Random account number
            - Nine digit number (e.g. `123456789`)
        - Set the Routing Number to `640479489`
        - Account Creation Date (`DateTime.Now`)
1. An account details page, which includes:
    - Account Number
    - Routing Number
    - Account Holder Name
    - Account Type
    - Account Creation Date
    - Account Balance
    - List of Transactions on the Account
1. The account details page allows the following actions:
    - Add a transaction to the account
        - Transaction Amount
        - Transaction Type
            - Debit (Remove from Balance)
            - Credit (Add to Balance)
        - Transaction Date (`DateTime.Now`)
    - Edit the Account Holder Name
    - Go back to main screen
1. Adding a transaction to an account affects its balance appropriately
1. All screens must be visually pleasing and easy to read and navigate. Imagine tellers might have to use these while interacting directly with customers.
