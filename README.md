# Student-Management-System

The Student Management System is a desktop application designed to manage student records efficiently. 

This system provides a user-friendly interface for adding, viewing, searching, and deleting student information. 

Built using Python and Tkinter for the graphical user interface (GUI) and MySQL for the database.

## Features

- **Add Student**: Add a new student record with name, contact, email, roll number, and branch.
- **View Students**: Display all student records in a tabular format.
- **Search Student**: Search for student records by name.
- **Delete Student**: Delete selected student records.
- **Reset Form**: Clear the input fields and refresh the data display.

## Requirements

- Python 3.x
- Tkinter
- MySQL
- MySQL Connector for Python

## Installation

1. Install the required Python packages:

    pip install mysql-connector-pytho

2. Set up the MySQL database:
    - Create a new database called `studentdb`.
      
    ```python
    conn = mysql.connector.connect(
        host="localhost",  # change to your host
        user="root",       # change to your user
        password="password",  # change to your password
        database="studentdb"  # change to your database
    )
    ```
    
## Usage

1. **Adding a Student**: Enter the student's details in the input fields on the left and click the `Submit` button.
2. **Viewing All Students**: Click the `View All` button to display all student records.
3. **Searching for a Student**: Enter the student's name in the search field and click the `Search` button.
4. **Deleting a Student**: Select a student record from the table and click the `Delete` button.
5. **Resetting the Form**: Click the `Reset` button to clear the input fields and refresh the data display.

## Screenshots

1) Adding a student details
![Option1](https://github.com/user-attachments/assets/740dce05-9c38-4aca-bd7a-16e32718a35a)

2) Searching of a student
![Option2](https://github.com/user-attachments/assets/ffcb8bb3-225d-4c7e-b7da-8e79b07b1b4a)

3) Data store in MySQL
![Option13](https://github.com/user-attachments/assets/86f88dc1-51da-4f6a-9428-17b0685b1e55)
