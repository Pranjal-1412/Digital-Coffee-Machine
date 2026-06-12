# ☕ Digital Coffee Machine

A simple command-line based **Digital Coffee Machine** built using **Python**. The program simulates the working of a coffee vending machine where users can order different types of coffee, insert coins for payment, and receive their drink if sufficient resources are available.

## 🚀 Features

* Supports three coffee options:

  * Espresso
  * Latte
  * Cappuccino
* Checks whether enough ingredients are available before preparing a drink.
* Accepts coin-based payments.
* Calculates and returns change automatically.
* Maintains a running profit counter.
* Displays the current status of resources and earnings using the `report` command.
* Allows the machine to be turned off using the `off` command.

## 📂 Project Structure

```
Digital-Coffee-Machine/
│
├── main.py
├── README.md
└── .gitignore
```

## 🛠️ Technologies Used

* Python 3
* Dictionaries
* Functions
* Loops and Conditional Statements
* Basic Input/Output Operations

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/Pranjal-1412/Digital-Coffee-Machine.git
```

2. Navigate to the project directory:

```bash
cd Digital-Coffee-Machine
```

3. Run the program:

```bash
python main.py
```

## ☕ Available Drinks

| Drink      | Cost  |
| ---------- | ----- |
| Espresso   | $1.50 |
| Latte      | $2.50 |
| Cappuccino | $3.00 |

## 💰 Commands

* `espresso` → Order Espresso
* `latte` → Order Latte
* `cappuccino` → Order Cappuccino
* `report` → Display current resources and profit
* `off` → Turn off the machine

## 📸 Sample Interaction

```
What would you like? (espresso/latte/cappuccino): latte

Please insert coins.
How many quarters?: 10
How many dimes?: 0
How many nickles?: 0
How many pennies?: 0

Here is $0.0 in change.
Here is your latte ☕
```

## 📚 Learning Objectives

This project demonstrates:

* Function decomposition
* Resource management using dictionaries
* User input handling
* Conditional logic
* Simple transaction processing
* Code organization and modular programming

## 👨‍💻 Author

**Pranjal Srivastava**

Feel free to fork the repository, suggest improvements, or build upon this project for learning purposes.
