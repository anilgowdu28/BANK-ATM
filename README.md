# ATM Management System (Python – OOP) 

This project is a simple **ATM Management System** built using **Python** and **Object-Oriented Programming (OOP)** concepts. It simulates basic ATM operations like checking balance, depositing money, withdrawing money, and viewing account details through a menu-driven program.

---

## Features

* Menu-driven ATM interface
* Check account balance
* Deposit money
* Withdraw money with validation
* View account details
* Uses core OOP principles

---

## OOP Concepts Used

* **Abstraction**

  * Implemented using an abstract class `BankAccount` with an abstract method `transaction()`.

* **Encapsulation**

  * Account balance is kept private using `__balance`.
  * Getter and setter methods are used to access and modify balance safely.

* **Inheritance**

  * `ATM` class inherits from the `Account` class.

* **Method Overriding**

  * The `transaction()` method is overridden in the `ATM` class.

* **Class Method & Static Method**

  * `bank_name()` is a class method.
  * `valid_amount()` is a static method for validation.

---

## Technologies Used

* Python 3
* OOP concepts
* Command-line interface

---

## How the Program Works

1. User details are initialized (name, account number, balance).
2. ATM menu is displayed repeatedly until the user exits.
3. User selects an option:

   * Check Balance
   * Deposit Amount
   * Withdraw Amount
   * View Account Details
   * Exit
4. Input is validated before performing transactions.

---

## Sample Menu

```
1. Check Balance
2. Deposit
3. Withdraw
4. Account Details
5. Exit
```

---

## How to Run the Program

1. Install Python (version 3.x recommended).
2. Copy the code into a file named `atm_management.py`.
3. Open terminal or command prompt.
4. Run the program using:

```bash
python atm_management.py
```

---

## Example Output

```
WELCOME TO KIET BANK ATM
ATM Transaction Started

1.Check Balance
2.Deposit
3.Withdraw
4.Account Details
5.Exit
 
