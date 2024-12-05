# Library-Project
It is the project of my 12th class, Made with Python and Mysql.
Showing basic structure of a Library.


Introduction
Project on Library Management
explores the enduring significance of
libraries in our information-driven
society. It delves into the challenges
faced by librarians, including cataloging,
circulation, acquisitions, and user
services.
The project highlights the importance of
embracing modern technology and
management systems to optimize
library operations. Libraries have
evolved from conventional book
repositories to dynamic information
centers. This project aims to enhance
our understanding of efficient library
management and the evolving role of
libraries in the digital age.


Imported Files & Used Functions Modules :-

The script uses mysql.connector to
connect to a MySQL database.
Built in functions :-

1. connect()- For database and table
connection

3. cursor()- For row by row
processing of records in resultset

5. execute()- For execute an SQL
statement

7. commit()- For change/update the
database

9. fetchall()- For fetch all rows

10. fetchone()- For fetch one row.

    
User defined functions :-

1. addbook()- adds books with name,
code, quantity, and subject to the
"books" table.

3. issueb()-issues a book to a student,
updating quantities in "books."

5. submitb()-records returned books,
updating quantities in "books."

7. bookup()- updates book
quantities; called by issueb() and
submitb() .

9. dbook()- deletes books from
"books" based on their code.

11. dispbook()- displays book details.
    
12. main()- offers a menu to perform
actions.
           
13. pswd() checks a password (default:
"1234) to access the main menu.
