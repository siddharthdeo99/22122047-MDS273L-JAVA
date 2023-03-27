Q.Create a Student class, that will store the details of the Student, below mentioned are the attributes of a student.
Reg. No.
Name
Email
Phone
Class
Department
The Student class will have the following methods:
A constructor to initialize the values of the Student
A method to print the Details of the Student.
A method (named 'toString()) that convert the student details to string, and can be used to write the student details to file.
In the main-method class, create an array of Student Class to hold maximum details of 100 Students.

In the menu-driven program, the menu options will have
Add a student
Adds the details of 1 student to the array of Student.
Search for a student
Search for the details of a student from the array of Student.
Searching can be done with Name or Register Number.
Update the details of a student
Update the student details based on the search based on name or register number.
Display all students
Displays the details of all students.
Save the details of each student in a file, with the student name as filename.

Note: Make use of functions to implement the menu options.

===============OUTPUT============

PS C:\Users\siddh\OneDrive\Desktop\22122047-MDS273L-JAVA\lab 6> java '-cp' 'C:\Users\siddh\AppData\Roaming\Code\User\workspaceStorage\83b8a9aa4e8b8ab7e12662b4717e1df3\redhat.java\jdt_ws\java_712b4dc4\bin' .\lab6.java
MENU
1. Add a student
2. Search for a student
3. Update the details of a student
4. Display all students
5. Save student details to file
6. Exit
Enter your choice: 1
Enter the details of the student:
Reg No.: 22122047

Name: Siddharth lal deo
Email: sid2gmail.com
Phone: 6204556
Class: mscds
Department: cs
Student added successfully
MENU
1. Add a student
2. Search for a student
3. Update the details of a student
4. Display all students
5. Save student details to file
6. Exit
Enter your choice: 4
Reg No.: 22122047
Name: Siddharth lal deo
Email: sid2gmail.com
Phone: 6204556
Class: mscds
Department: cs
MENU
1. Add a student
2. Search for a student
3. Update the details of a student
4. Display all students
5. Save student details to file
6. Exit
Enter your choice: 2
Enter the search term (name or register number):
name
Student not found
MENU
1. Add a student
2. Search for a student
3. Update the details of a student
4. Display all students
5. Save student details to file
6. Exit
Enter your choice: 2
Enter the search term (name or register number):
22122047
Reg No.: 22122047
Name: Siddharth lal deo
Email: sid2gmail.com
Phone: 6204556
Class: mscds
Department: cs
MENU
1. Add a student
2. Search for a student
3. Update the details of a student
4. Display all students
5. Save student details to file
6. Exit
Enter your choice: 3
Enter the search term (name or register number):
Siddharth lal deo
Enter the new details:
Name: sid
Email: siddharthlaldeo@gmail.com
Phone: 6204556171
Class: mscds
Department: data science
Student details updated successfully
MENU
1. Add a student
2. Search for a student
3. Update the details of a student
4. Display all students
5. Save student details to file
6. Exit
Enter your choice: 4
Reg No.: 22122047
Name: sid
Email: siddharthlaldeo@gmail.com
Phone: 6204556171
Class: mscds
Department: data science
MENU
1. Add a student
2. Search for a student
3. Update the details of a student
4. Display all students
5. Save student details to file
6. Exit
Enter your choice: 5
Enter the name of the student to save the details to file:
sid
Student details saved to file successfully
MENU
3. Update the details of a student
4. Display all students
5. Save student details to file
6. Exit
Enter your choice: 6
Exiting...