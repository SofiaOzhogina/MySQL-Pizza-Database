# MySQL-Pizza-Database
In this project, I've created a MySQL database in conjunction with Python to grasp the fundamental concepts of SQL and its integration with the language. The database enables user interaction, allowing individuals to place pizza orders with delivery services

**Project Setup Instructions**

This project includes code that requires access to a provided database stored in the "SQL db" folder. To get started, please follow these steps:

**Database Setup:**
1. Copy the database from the "SQL db" folder to your local machine.
2. Ensure you have MySQL installed and set up on your system.

**Code Configuration:**
1. Open the "attempt3.py" file in your preferred text editor or IDE.
2. Locate the line: 
    ```python
    engine = sqlalchemy.create_engine("mysql://****:*********@localhost/pizza", echo=False)
    ```
3. Replace the `****` with your MySQL username and `********` with your corresponding password.
   
**Running the Code:**
Once the database is set up and the necessary configurations in the code are adjusted, execute the provided code to interact with the database and explore its functionalities. 
