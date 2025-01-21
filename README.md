# Student-Management-System
Singly Linked List: Student Management System
This is a Student Management System implemented using a Singly Linked List in C++. The system allows users to manage a list of students, track their marks, and apply grace marks to students who have obtained fewer than 30 marks.

Features

1. Add Students:  Add new students by providing their name and marks.

2. Display Students:  Display a list of all students with their names, marks, and grace status.

3. Apply Grace Marks:  Automatically apply 5 grace marks to students with marks below 30, if grace marks haven't been given yet.

4. SinglyLinked List:  The students' data is managed using a Singly linked list, which ensures that the list is efficiently traversed

5. Menu-Driven Interface:  Choose options from a menu to interact with the system, including adding students, displaying student data, and applying grace marks.



Prerequisites

To run this project, you'll need:

A C++ compiler such as GCC or Clang.

Basic knowledge of C++ and Linked Lists.

Installation


Clone the repository to your local machine using the following command:


bash

git clone https://github.com/bhanuudhay/Student-Management-System.git


Navigate to the project directory:

bash

cd Student-Management-System


Compile the C++ code:

bash

g++ student_management.cpp -o student_management


Run the program:

bash

./student_management


Usage


Menu Options


1.  Add a Student:

2.  Enter the student's name and marks. The student will be added to the Singly linked list.
 
3. Displays the list of students, including their names, marks, and whether grace marks have been applied.

4. Provide Grace Marks:

5. Apply 5 grace marks to students with marks less than 30 who haven't already received grace.

6. Exit:

Exits the program.



Example Interaction:

Menu
1. Add student
2. Display Student
3. Provide Grace Marks
4. Exit
   
Enter your choice: 1

Enter student's name: 
Alice
Enter marks obtained: 28
Student added successfully!

Menu
1. Add student
2. Display Student
3. Provide Grace Marks
4. Exit
   
Enter your choice: 2

Name:

Alice Marks: 
28 Grace Given: No

Menu
1. Add student
2. Display Student
3. Provide Grace Marks
4. Exit
   
Enter your choice: 3

Grace marks given to Alice

Menu
1. Add student
2. Display Student
3. Provide Grace Marks
4. Exit
   
Enter your choice: 2

Name:
Alice Marks: 33 Grace Given: Yes


