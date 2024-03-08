# Employee Management System

A simple C++ program for managing employee!
---

<h3>Features:</h3> 
1. Add Employee with Details such as Name, Age, ID, Designation, Salary
2. Display All Employees
3. Search Employee
4. Modify Employee
5. Delete Employee

---
The code first creates a vector called employees to store the employee data. The Employee structure is used to store the Employee data. It has the following members:

    name: The employee's name
    age: The employee's age
    id: The employee's ID
    designation: The employee's designation
    salary: The employee's salary

The addEmployee() function adds an employee to the employees vector. It takes the employee's name, age, ID, designation, and salary as input and stores them in the Employee structure. The employee is then added to the employees vector.

The displayEmployees() function displays all the employees in the employees vector. It iterates through the vector and prints the employee's name, age, ID, designation, and salary.

The searchEmployee() function searches for an employee in the employees vector by ID. It takes the employee's ID as input and iterates through the vector. If the employee's ID is found, the employee's information is printed. If the employee's ID is not found, a message is printed stating that the employee was not found.

The modifyEmployee() function modifies an employee's record in the employees vector. It takes the employee's ID as input and iterates through the vector. If the employee's ID is found, the employee's information is updated with the new information. If the employee's ID is not found, a message is printed stating that the employee was not found.

The deleteEmployee() function deletes an employee from the employees vector. It takes the employee's ID as input and iterates through the vector. If the employee's ID is found, the employee is removed from the vector. If the employee's ID is not found, a message is printed stating that the employee was not found.

The code also has a main function that allows the user to interact with the employee management system. The user can add employees, display employees, search for employees, modify employees, and delete employees.

I hope this explanation is helpful. Please let me know if you have any other questions.
