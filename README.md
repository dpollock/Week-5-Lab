# Week-5-Lab
Library Database



We're going to an API that allows people to lookup books, students, and what books are checked out. 

Normal Mode
------
The Following are the requirements of your API:

1. Create/Edit/Update/Delete Students
2. Create/Edit/Update/Delete Books
3. Books can be Checked Out/In
  1. Books will be checked out by calling the API and giving it the  book id and student id
  2. Books will be checked in by calling the API and passing the book id.
4. All books, students and what is checked out will be stored in a SQL Database
 
Hard Mode
-----
1. Seed your database with example students, books, and checkouts using EF Migrations.
2. Beef up your API to return an appropriate error message if checking out books that don't exist to students that don't exist.
3. Likewise - return an error message if checking in a book that doesn't exist or one that isn't currently checked out.


