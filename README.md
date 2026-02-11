#  Bank Service Application

A Java-based console banking application that performs basic banking operations such as balance inquiry and fund transfer using a clean layered architecture.

---

##  Overview

The Bank Service Application demonstrates the implementation of core banking functionalities using Object-Oriented Programming concepts in Java.

This project supports:

- Checking account balance
- Transferring funds between accounts
- Handling insufficient balance using custom exceptions

---

## Output

## Case 1: Success
- The system checks the available balance of the account.
- The account contains sufficient funds.
- The transfer operation is completed successfully.
- The transaction is processed and confirmation message is displayed as **SUCCESS**.

  
<img width="567" height="204" alt="Screenshot 2026-02-11 115504" src="https://github.com/user-attachments/assets/ec08c307-5bff-40b5-8731-5a1da1e32616" />




---

## Case 2: Insufficient Balance

- The system verifies the account balance before transfer.
- The available balance is less than the transfer amount.
- The application throws a custom `InsufficientFundsException`.
- The transaction is not processed.
- The system displays the message **INSUFFICIENT BALANCE**.

  

  <img width="512" height="250" alt="Screenshot 2026-02-11 115422" src="https://github.com/user-attachments/assets/9f16f515-b1c9-4f98-ba93-c48b7d98eb12" />





