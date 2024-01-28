
# Banking System C++ Project

### Overview : 
This C++ project implements a simple banking system. It allows users to perform various banking operations such as opening an account, checking balance, depositing, withdrawing, closing an account, and viewing all accounts. The project utilizes object-oriented programming principles and file handling for data persistence.

### Features :
- **Open Account**: Users can open a new bank account by providing their first name, last name, and initial balance.

- **Balance Enquiry**: Users can check the balance of their account by providing the account number.

- **Deposit**: Users can deposit a specified amount into their account.

- **Withdrawal**: Users can withdraw a specified amount from their account, with a check for minimum balance.

- **Close Account**: Users can close their account, which removes it from the system.

- **Show All Accounts**: Displays details of all existing accounts.

### Code Structure:
The project consists of two main classes:

1. Account: Represents a bank account with attributes such as account number, first name, last name, and balance. It includes methods for deposit, withdrawal, and file I/O operations.

2. Bank: Manages a collection of accounts and provides methods for various banking operations. It reads and writes account data to a file for persistence.

### Usage :
1. Compile the code using a C++ compiler.<br>
  ```bash
    g++ BankingSys.cpp -o BankingSys

2. Run the executable.<br>
  ```bash
    ./BankingSys

3. Follow the on-screen menu to perform different banking operations.

### File Persistence:
Account data is stored in a file named "Bank.data". The data is read at the start of the program, and changes are written back to the file when the program exits.

#### Note:
The project uses exception handling for insufficient funds during withdrawals.
It demonstrates the use of classes, file handling, and map container in C++.

#### Author:
Swapnil Pawar
