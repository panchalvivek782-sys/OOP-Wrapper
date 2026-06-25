## # Employee Management System
## 
## ## Description
## This Python project demonstrates Object-Oriented Programming (OOP) principles through a command-line Employee Management System.
## It features a base class for employees and inherited classes for specific roles like managers and developers.
## The program uses getters, setters, decorators, inheritance, and method overriding to manage workforce data.
## 
## ## Key OOP Concepts Covered
## * **Encapsulation**: Uses protected attributes for employee ID and salary with property getters and setters.
## * **Inheritance**: The `Manager` and `Developer` classes inherit core attributes and methods from the `Employee` base class.
## * **Polymorphism**: The `display()` method is overridden in subclasses to extend functionality and print role-specific details.
## 
## ## Class Structure
## * **Employee**: The base class containing core attributes (`name`, `age`, `employee_id`, `salary`).
## * **Manager**: A subclass of `Employee` that adds a `department` attribute.
## * **Developer**: A subclass of `Employee` that adds a `programming_language` attribute (ready for future integration).
## 
## ## How to Run
## 1. Ensure you have Python installed on your system.
## 2. Copy the code into a file named `employee_system.py`.
## 3. Open your terminal or command prompt.
## 4. Run the file using the command: `python employee_system.py`
## 
## ## Interactive Menu Options
## * **Option 1**: Create a generic Person record (only contains name and age).
## * **Option 2**: Create a full Employee record (includes ID and salary).
## * **Option 3**: Create a Manager record (includes ID, salary, and department).
## * **Option 4**: Display details of any currently stored record.
## * **Option 5**: Safely delete all active object instances and exit the application.
