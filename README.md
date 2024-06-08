# CODTECH-Task2
Name : Tejas Vilas Desale
ID : CT6WDS140
Domain : Python Programming
Mentor : SRAVANI GOUNI

Overview of project :
Overview of the Library Management System (LMS) Project
The Library Management System (LMS) project is designed to manage the basic operations of a library. This includes functionalities such as adding new books and members, checking out and returning books, and maintaining records of transactions. The project utilizes Python as the programming language, SQLite for database management, and Tkinter for the graphical user interface (GUI).

Key Components
Database Initialization:

SQLite Database: The database is created using SQLite, a lightweight, disk-based database. Three main tables are used:
books: Stores information about the books in the library.
members: Stores information about the library members.
transactions: Stores information about the transactions (checkouts and returns) that take place.
Graphical User Interface (GUI):

Tkinter: The GUI is built using Tkinter, which is the standard Python interface to the Tk GUI toolkit. The interface is divided into three main tabs: Books, Members, and Transactions.
Functionalities:

Book Management:
Add new books with details such as title, author, year of publication, and ISBN.
View a list of all books in the library.
Member Management:
Add new members with details such as name, email, and phone number.
View a list of all members.
Transaction Management:
Checkout books to members and record the transaction.
Return books and update the transaction record.
View transaction history.
Detailed Description
Database Initialization:

The initialize_db() function sets up the SQLite database and creates the necessary tables if they do not exist. This function ensures that the database is ready for storing and retrieving data.
Graphical User Interface (GUI):

Tabs: The main window contains three tabs: Books, Members, and Transactions.
Book Management:
A form to input book details and a button to add the book to the database.
A Treeview widget to display the list of books.
Member Management:
A form to input member details and a button to add the member to the database.
A Treeview widget to display the list of members.
Transaction Management:
Forms to input book ID and member ID for checking out and returning books.
Buttons to perform checkout and return operations.
A Treeview widget to display the transaction history.
Functionalities:

Add Book: Collects book details from the user, validates the input, and adds the book to the database.
Add Member: Collects member details from the user, validates the input, and adds the member to the database.
Checkout Book: Validates the availability of the book and member details, records the transaction, and updates the book's availability status.
Return Book: Validates the book ID, updates the transaction record with the return date, and marks the book as available.
Load Data: Functions to load and display data from the database in the Treeview widgets.
