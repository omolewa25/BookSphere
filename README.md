# BookSphere
Library Management System


__[LinkedIn](https://www.linkedin.com/in/omolewa-adaramola)__

Overview

The Library Management System is a Python-based application designed to manage a library's operations more effectively. It is an interactive portal meant to automate all processes and provide excellent user experience. It is intended to overcome the restrictiveness, or lack thereof of brick-and-mortar institutions, providing boundless access to a wider reading audience. This system is purely online and as such the features will reflect the desire of this project to meaningfully impact its community of users. The target user is anyone intent on learning, especially those who by circumstance are or may find themselves in book deserts.

Features

•	Book Management: Add, update, delete, and search books by title, author, or ISBN.

•	Administration: Manage library members, including adding new users, viewing user details, and deleting users.

•	Transaction Management: Issue books to users, book returns and tracking due dates: Generate fines for late returns (optional).

•	Book searching by title, author, genre, or ISBN: Filter books based on availability, name or category.

•	Database Integration: use a document-based database (MongoDB) for persistent storage of variety of media.

Installation
1.	Clone the repository:
bash
Copy/Edit
git clone https://github.com/yourusername/library-management-system.git
cd library-management-system
2.	Install the required dependencies:
bash
CopyEdit
pip install -r requirements.txt
3.	Run the application:
bash
CopyEdit
python app.py
Requirements
•	Python 3.7 or higher
•	MongoDB (or your preferred database)
•	Dependencies listed in requirements.txt 

Usage
1.	Add Books: Add new books to the library catalog.
2.	Register Users: Register new members and assign them unique IDs.
3.	Issue Books: Issue books to users by specifying the user ID and book ID.
4.	Return Books: Mark books as returned and calculate fines for overdue returns.
5.	View Reports: Generate lists of issued books, available books, or user histories.

Folder Structure

perl

CopyEdit

library-management-system/

│

├── app.py      # Main application script

├── database/

│   └── library.db     #MongoDB database file

├── modules/

│   ├── book_management.py # Book-related operations

│   ├── user_management.py # User-related operations

│   └── transaction.py  # Issue and return operations

├── tests/

│   ├── test_books.py  # Unit tests for book management

│   ├── test_users.py  # Unit tests for user management

│   └── test_transactions.py # Unit tests for transactions

├── requirements.txt  # Python dependencies

└── README.md  # Documentation

Contributions

Contributions are encouraged! Please follow these steps:
1.	Fork the repository.
2.	Create a new branch (git checkout -b feature-name).
3.	Commit your changes (git commit -m 'Add feature-name').
4.	Push to the branch (git push origin feature-name).
5.	Open a pull request.

TECHNOLOGY STACK

1.	Front-end: NodeJS
2.	Backend: Python
3.	Database: MongoDB
4.	AWS EC2

License

This project is licensed under the MIT License. See the LICENSE file for details.
