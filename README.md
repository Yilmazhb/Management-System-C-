# Student Management System
A simple console based DBMS project to handle CRUD operations.

## About
This is a console-based Student Management System, which is a simple application designed to manage student records, including creating, updating, and deleting student information. Additionally, it allows for the assignment of courses to students, inserting student marks, calculating GPA, and viewing available courses and departments.

### Key functionalities of this Student Management System include:
Create Student: Users can input a student's ID, first name, last name, date of birth, and department ID to create a new student record in the database.

Show Students: This function retrieves and displays a list of all students stored in the database, including their basic information like name, date of birth, and department ID.

Update Student: Users can update the information of an existing student by providing their ID and modifying their first name, last name, date of birth, and department ID.

Delete Student: Allows the removal of a student record by specifying the student's ID.

Add Course to Student: This feature allows users to assign courses to students by selecting a student's ID and a course ID from a list of available courses.

Insert Marks and Calculate GPA: Users can enter marks for a student in a specific course, and the system will automatically calculate the GPA based on the provided marks.

Search Student: This function allows users to search for a specific student by their ID and displays detailed information about the student, including the courses they are enrolled in and their corresponding grades.

View Courses and Departments: Users can view a list of available courses and departments, and they can also insert new courses and departments.

The code interacts with a SQL Server database using SQL commands for data retrieval, insertion, updating, and deletion. It includes error handling to provide feedback on the success or failure of database operations.

Overall, this Student Management System serves as a basic tool for managing student information and academic records, making it useful for educational institutions or organizations that require a straightforward means of handling student data. Further improvements could include enhanced user interface features and additional functionalities like grade reporting, student enrollment management, and data analytics.

## Dependencies
- C#
- .NET SDK (7.0.403)
- Microsoft SQL Server (SQL Express 2022)
- Microsoft Data.SqlClient (5.1.2)

## How to use
Clone the repository
Create Database or Import Database from backup
Open the project in Visual Studio Code
Install C# Dev Kit
Run the project
Note

You can also use Visual Studio or your favorite IDE to run this project.
