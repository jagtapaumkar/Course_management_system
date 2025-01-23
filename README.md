# Course_management_system

This is a simple Student Management System project implemented using Java and MySQL. It allows users to perform CRUD (Create, Read, Update, Delete) operations on student data such as ID, first name, last name, major, phone number, GPA, and date of birth.

For a step-by-step guide to design and develop this application, visit: [Step by Step Guide](https://iq.opengenus.org/student-management-system-in-java/)

## Features
- **Add a New Student**: Input student details to register a new student.
- **View Student Data**: Display all registered students in a tabular format.
- **Update Student Data**: Modify existing student information.
- **Search for a Student**: Find specific student records based on criteria.
- **Sort Students**: Sort the student list by major, last name, or first name.

## Requirements
- **Java**: Version 8 or higher.
- **MySQL Server**: Ensure MySQL is installed and running.


2. **Create a MySQL Database**:
- Create a new database in MySQL.
- Import the `student_data.sql` file to create the required tables and sample data.

3. **Update Database Connection Details**:
- Modify the database connection settings in the `dbConnect` class to match your MySQL configuration.

4. **Build and Run the Project**:
- Use your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse) or command-line tools to build and run the project.

5. **Import `student_data.sql` into Your MySQL Database**:
- Open your terminal and type:
  ```
  mysql -u username -p database_name < student_data.sql
  ```
- Replace `username` with your MySQL username.
- Replace `database_name` with the name of your database.
- If prompted, enter your password.

## Usage
- Launch the application.
- Select the desired operation from the main menu.
- Follow the prompts to enter or update student data.

## Database Columns
The database table used in this project has the following columns:

| Column Name    | Description                                      |
|----------------|--------------------------------------------------|
| Student_ID     | The unique identifier for each student.          |
| first_name     | The first name of the student.                   |
| last_name      | The last name of the student.                    |
| major          | The major that the student is studying.          |
| phone          | The phone number of the student.                 |
| GPA            | The grade point average of the student.          |
| DOB            | The date of birth of the student.                |

## Future Enhancements
- Implement fee tracking functionality.
- Add attendance management features.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



