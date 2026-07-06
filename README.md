# Employee Management System (Python OOP)

## Project Description
The Employee Management System is a simple Python application developed using the principles of Object-Oriented Programming (OOP). It allows users to create and manage Person, Employee, and Manager records through a menu-driven interface.

The project demonstrates the use of:
- Classes and Objects
- Inheritance
- Method Overriding (Polymorphism)
- Constructors
- User Input
- Loops and Conditional Statements

---

## Features
- Create a Person
- Create an Employee
- Create a Manager
- Display details of Person, Employee, and Manager
- Menu-driven interface
- Exit the application safely

---

## Technologies Used
- Python 3.x
- Object-Oriented Programming (OOP)

---

## Class Structure

### 1. Person
**Attributes:**
- name
- age

**Method:**
- show_details()

---

### 2. Employee (Inherits Person)
**Additional Attributes:**
- employee_id
- salary

**Method:**
- show_details() (Overridden)

---

### 3. Manager (Inherits Employee)
**Additional Attribute:**
- department

**Method:**
- show_details() (Overridden)

---

## How to Run

1. Install Python 3.
2. Save the program as:

```
employee_management.py
```

3. Open Command Prompt or Terminal.
4. Navigate to the project folder.
5. Run:

```bash
python employee_management.py
```

---

## Menu Options

```
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Show Details
5. Exit
```

---

## Sample Output

```
--- Python OOP Project: Employee Management System ---

1. Create a Person
2. Create an Employee
3. Create a Manager
4. Show Details
5. Exit

Enter your choice: 2

Enter Name: John
Enter Age: 25
Enter Employee ID: EMP101
Enter Salary: 50000

Employee created successfully.
```

---

## OOP Concepts Used

- ✔ Classes and Objects
- ✔ Inheritance
- ✔ Constructor (__init__)
- ✔ Method Overriding
- ✔ Encapsulation
- ✔ Code Reusability

---

## Future Improvements

- Store multiple employees using lists.
- Search employee by ID.
- Update employee details.
- Delete employee records.
- Save data to a file or database.
- Add exception handling and input validation.

---

## Author

**Name:** Grisha Bhimani

---

## License

This project is created for educational and learning purposes.
  
