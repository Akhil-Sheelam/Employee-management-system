# Employee-management-system
A beginner-friendly Employee Management System built using Python, Tkinter for the GUI, and MySQL as the database. This project allows you to add, view, update, promote, delete, and search employee records through a simple and intuitive graphical interface.

Features:<br>
✅ Add new employees with validation<br>
📋 View all employee records<br>
📋 View all employee records<br>
✏️ Update employee details (email, phone, address)<br>
💹 Promote employee by increasing salary<br>
🗑️ Delete employee record by ID<br>
🔍 Search employee by ID<br>
🖥️ Clean and user-friendly Tkinter interface<br>

🛠️Technologies Used:<br>
 Python 3.x<br>
 Tkinter (GUI module)<br>
 MySQL with mysql-connector-python<br>
 VS Code (recommended IDE)<br>

employee-management/<br>
│<br>
├── main.py          # GUI and main menu (Tkinter)<br>
├── employee_ops.py     # All backend operations (CRUD)<br>
├── db_config.py          # MySQL connection configuration<br>
├── create_table.sql      # SQL script to create the employee table<br>
└── README.md             # Project description and usage<br>

Setup Instructions:<br>

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


