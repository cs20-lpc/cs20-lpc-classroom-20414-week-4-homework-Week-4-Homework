# Programming Question


**Problem Statement:**

Design and implement a singly linked list in C++ to manage student records. 
Each student has:
  1. An integer id
  2. A string name
  3. A floating-point gpa
     
Your linked list should support the following operations:
  1. Insert a student at the end of the list.
  2. Delete a student by id.
  3. Search for a student by id and display their details.
  4. Display all students in the list.
  5. Count the number of students in the list.
     
Requirements:
  1. Do not use std::list or other STL containers. Implement the linked list manually using pointers.

  2. Create a Node structure to represent each student.
  
  3. Write a LinkedList class that implements the required operations.
  
  4. In main(), present a menu-driven program to let the user test the functions.
  5. Make sure to name your Student class files as Student.cpp/hpp (note S is uppercase) and the file that has main() function as main.cpp

  ## Sample Output:
  ```
1. Insert Student
2. Delete Student
3. Search Student
4. Display All
5. Count Students
6. Exit
Enter choice: 1
Enter ID: 101
Enter Name: Alice
Enter GPA: 3.8

Enter choice: 1
Enter ID: 102
Enter Name: Bob
Enter GPA: 3.5

Enter choice: 4
Students in List:
101 Alice 3.8
102 Bob 3.5

Enter choice: 3
Enter ID to search: 102
Found: 102 Bob 3.5

Enter choice: 2
Enter ID to delete: 101
Deleted student with ID 101

Enter choice: 5
Total students: 1

  ```
Make sure to run several tests to ensure your code is tested properly for all edge cases.

Scoring:
  - 10 points: Program compiles and runs properly for at least one test case. 
  - 5 points: Test coverage - Make sure to indicate what scenario you are trying to test for each test case. - Upload to Canvas test results
  - 5 points: Ask the same question to chatGPT. Compare your implementation with chatGPT response and give at least 5 differences between your implementation and chatGPT implementation. 
