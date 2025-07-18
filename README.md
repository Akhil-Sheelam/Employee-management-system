# Employee-management-system
A beginner-friendly Employee Management System built using Python, Tkinter for the GUI, and MySQL as the database. This project allows you to add, view, update, promote, delete, and search employee records through a simple and intuitive graphical interface.

Features
✅ Add new employees with validation
📋 View all employee records
✏️ Update employee details (email, phone, address)
💹 Promote employee by increasing salary
🗑️ Delete employee record by ID
🔍 Search employee by ID
🖥️ Clean and user-friendly Tkinter interface

🛠️Technologies Used
 Python 3.x
 Tkinter (GUI module)
 MySQL with mysql-connector-python
 VS Code (recommended IDE)

employee-management/
│
├── main.py               # GUI and main menu (Tkinter)
├── employee_ops.py       # All backend operations (CRUD)
├── db_config.py          # MySQL connection configuration
├── create_table.sql      # SQL script to create the employee table
└── README.md             # Project description and usage

Setup Instructions:

1.Clone the repository
git clone https://github.com/yourusername/employee-management.git
cd employee-management

2.Install MySQL connector
pip install mysql-connector-python

3.Setup MySQL Database
-Open MySQL Workbench or your SQL client
-Run the create_table.sql file to create the database and table

4.Edit db_config.py
-Replace the placeholder credentials with your MySQL username and password

5.Run the application
python main.py


