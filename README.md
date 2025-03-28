# Employee-Management-System-in-C-Sharp
Employee Management System Documentation: 
 
1. Introduction 
The Employee Management System (EMS) is a desktop application built using C# and 
Windows Forms in Visual Studio 2022. It includes functionalities for managing 
employees, updating salaries, and tracking employee statistics. The system integrates a 
SQL Server database for data storage. 
 
 
2.1 Objectives 
• Enable efficient management of employee data (add, view, update, delete). 
• Allow administrators to manage employee salary information. 
• Display employee and salary-related statistics. 
• Provide a user-friendly and intuitive interface. 
 
 
2.2 Code Structure 
The project is divided into: 
1. Forms: 
o LoginForm.cs - Login page logic. 
o DashboardForm.cs - Employee statistics. 
o ManageEmployeesForm.cs - Add/Update employees. 
o SalaaryManagement 
2. Database Access: 
o EmployeeDB.cs - Handles database operations (CRUD). 
3. Business Logic: 
o Employee.cs - Employee model class with properties. 
 
3. System Design 
3.1 Architecture 
The EMS follows the 3-tier architecture: 
1. Presentation Layer: Windows Forms for the user interface. 
2. Business Logic Layer: Handles operations and logic for managing data. 
3. Data Access Layer: Manages database connections and queries. 
 
 
3.2 Database Design 
The system uses a SQL Server database. The key tables include: 
Employees Table 
 
Column Name Data Type Description 
employee_id int Primary Key, unique ID 
name varchar(50) Employee's full name 
gender varchar(10) Male/Female 
contact varchar(15) Contact number 
position varchar(30) Job position 
salary float Employee's salary 
update_date datetime Last salary update date
