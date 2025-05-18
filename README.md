# Library-Management-app
This is a simple command-line Python application that allows users to manage a library system with functionalities such as displaying available books, lending books to users, adding new books, and returning borrowed books.
Features:

📖 Display Books: View the list of all books available in the library.

🙋‍♂️ Lend a Book: Assign a book to a user and update the lending record.

➕ Add a Book: Add new books to the library and update the database file.

🔁 Return a Book: Return a previously borrowed book and update the lending record.

Key Concepts Used:

Object-Oriented Programming (OOP) in Python

File handling for maintaining the book database

Dictionary data structure for tracking lending status

Input validation and interactive CLI menu

How It Works:

On startup, the app loads books from a text file (entered by the user).

It uses a Library class to manage all operations.

Users interact via a simple text-based menu.

Lending status is maintained using a dictionary (lendDict).

New books are appended to the existing database file.

Ideal For:

Beginners learning Python

Practicing OOP, file handling, and conditionals

Building small-scale CLI-based utilities
