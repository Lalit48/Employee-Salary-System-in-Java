# Employee-Salary-System-in-Java

The Employee Salary System is a console-based application that allows users to manage employee information, including calculating salaries based on hours worked and hourly rates. This system supports adding employees, updating employee hours, computing salaries, and displaying employee details.

#### Features

1. **Add Employee**:
   - Add new employees with details like name, ID, hourly rate, and hours worked.

2. **Update Hours Worked**:
   - Update the hours worked for an existing employee.

3. **Compute Salary**:
   - Calculate the salary based on the hourly rate and hours worked.

4. **Display Employee Information**:
   - Display the details of all employees including computed salary.


### Explanation

1. **Employee Class**:
   - Stores employee details: name, ID, hourly rate, and hours worked.
   - Provides methods to update hours worked, compute salary, and display employee information.

2. **EmployeeSalarySystem Class**:
   - Manages a list of employees using an `ArrayList`.
   - Provides a menu-driven interface for adding employees, updating hours worked, computing salary, and displaying employee information.
   - Uses a `Scanner` for user input.

3. **Menu Options**:
   - **Add Employee**: Prompts the user to enter employee details and adds the employee to the list.
   - **Update Hours Worked**: Updates the hours worked for a specified employee.
   - **Compute Salary**: Computes and displays the salary for a specified employee.
   - **Display Employee Information**: Displays information for all employees in the system.

### Running the Program

1. **Compile the Program**:
   - Use the `javac` command to compile the Java program:
     ```sh
     javac EmployeeSalarySystem.java
     ```

2. **Run the Program**:
   - Execute the compiled program using the `java` command:
     ```sh
     java EmployeeSalarySystem
     ```

This Employee Salary System provides a basic framework for managing employee details and computing salaries. It can be extended with additional features like data persistence (e.g., saving and loading employee data from a file), more sophisticated salary calculations, and a graphical user interface (GUI) for better user experience.
