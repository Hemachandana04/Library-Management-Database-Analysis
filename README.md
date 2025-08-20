# Library-Management-Database-Analysis
This Task demonstrates the creation and management of a Library Database using SQLite in Python. The notebook walks through schema design, table creation, data insertion, and relational integrity enforcement.

📂 Tables Implemented

PUBLISHER → Stores publisher details (Name, Address, Phone).

BOOK → Contains book information with references to publishers.

BOOK_AUTHORS → Maps books to their authors.

LIBRARY_BRANCH → Stores library branch details.

BOOK_COPIES → Tracks the number of book copies at each branch.

BOOK_LENDING → Records lending activity (Book ID, Branch, Card No, Date).

⚙️ Features

Database Connection using sqlite3

Schema Creation with multiple related tables

Foreign Key Constraints to enforce relationships

Sample Data Insertion for testing

Sample Data Analysis 
