📚 Student Management System
A simple console-based C++ program that allows you to manage student records. This includes adding, displaying, searching, updating, and deleting student information using a menu-driven interface.

🛠 Features
➕ Add a new student

📋 Display all students

🔍 Search student by Roll No

✏️ Update student details (Roll No, Name, or Age)

❌ Delete student by Name

💾 Uses a dynamic list (std::vector) to store student data

📦 Technologies Used
Language: C++

Standard Library: iostream, vector, string

Compiler: Compatible with any C++ compiler (GCC, MSVC, etc.)

📄 How It Works
The system maintains a list of students in memory using std::vector. Each student is represented by a Student class containing:

Roll Number

Name

Age

The application is menu-driven, allowing users to interactively perform operations such as adding or modifying records.

🚀 Getting Started
1. Clone the Repository or Copy the Code
Save the code in a file, for example:
student_management.cpp

2. Compile the Code
Using g++:

📸 Sample Menu
--------------------------------
*** Student Management System ***
--------------------------------
 1. Add New Student
 2. Display All Student
 3. Search Student
 4. Update Student
 5. Delete Student
 6. Exit

Enter Your Choice :

📝 Notes
Student records are not saved persistently (data is lost after program termination).

Duplicate roll numbers are not allowed.

Deletion and update are performed based on student name (case-sensitive).

🙌 Contributing
If you have suggestions or want to enhance the program (e.g., add file I/O, GUI, or sorting), feel free to fork and submit a pull request.

