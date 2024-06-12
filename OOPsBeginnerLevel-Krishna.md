## Coding Questions

#### Question 1: Implementing a Simple Bank Account Class

Create a class `BankAccount` in Python which has the following attributes and methods:

- Attributes:
  - `account_number`: String
  - `balance`: Float
  - `owner`: String

- Methods:
  - `__init__(self, account_number, owner, balance=0.0)`: Constructor to initialize the attributes.
  - `deposit(self, amount)`: Method to deposit an amount to the balance.
  - `withdraw(self, amount)`: Method to withdraw an amount from the balance. It should not allow withdrawal if the amount exceeds the balance.
  - `get_balance(self)`: Method to return the current balance.
  - `__str__(self)`: Method to return the account details as a string.

Implement the class and create an instance of the `BankAccount` class. Perform a few deposits and withdrawals, and print the account details.

#### Question 2: Implementing an Inventory Management System

Create a class `Inventory` in Python which has the following attributes and methods:

- Attributes:
  - `items`: Dictionary where keys are item names and values are the quantity of items.

- Methods:
  - `__init__(self)`: Constructor to initialize the items dictionary.
  - `add_item(self, item_name, quantity)`: Method to add a certain quantity of an item to the inventory.
  - `remove_item(self, item_name, quantity)`: Method to remove a certain quantity of an item from the inventory. It should not allow removal if the quantity exceeds the current stock.
  - `get_stock(self, item_name)`: Method to return the current stock of a specific item.
  - `__str__(self)`: Method to return the inventory details as a string.

Implement the class and create an instance of the `Inventory` class. Add and remove some items, and print the inventory details.

#### Question 3: Implementing a Student Grading System

Create a class `Student` in Python which has the following attributes and methods:

- Attributes:
  - `name`: String
  - `student_id`: String
  - `grades`: Dictionary where keys are subject names and values are the grades.

- Methods:
  - `__init__(self, name, student_id)`: Constructor to initialize the attributes.
  - `add_grade(self, subject, grade)`: Method to add a grade for a subject.
  - `get_average_grade(self)`: Method to calculate and return the average grade.
  - `__str__(self)`: Method to return the student details as a string.

Implement the class and create an instance of the `Student` class. Add some grades, calculate the average grade, and print the student details.

---
