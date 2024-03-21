# Project_150
Introduction:
This project aims to develop a console-based School Management System,utilizing file systems,for effective student and teacher administration.The system will focus on student management ,teacher management system all accessible through a command-line interface.

Structures:
student: Contains information about a student, such as ID, name, parent names, date of birth, mobile number, guide teacher, admitted class, and admission date.
teacher: Stores details of a teacher including ID, name, date of birth, mobile number, subject, and joining date.
result: Holds student's result data including ID, name, grade point, subject, and guide teacher.

Functions:
clear_screen(): Clears the console screen.
get_total_number_of_student(): Retrieves the total number of students from a file.
get_total_number_of_teacher(): Retrieves the total number of teachers from a file.
print_student(): Prints the list of students with their details.
print_teacher(): Prints the list of teachers with their details.
get_date(): Returns the current date in the format DD-MM-YYYY.
show_student_list(): Parses and displays the student list from a file.
show_teacher_list(): Parses and displays the teacher list from a file.
add_new_student(): Adds a new student to the system and updates the student list file.
add_new_teacher(): Adds a new teacher to the system and updates the teacher list file.
search(): Searches for a student or teacher by name and displays the details.
make_result(): Generates results for a particular class by taking inputs for grade points from the user.
show_result(): Displays the result of a particular class.
school_overview(): Provides an overview of the school, including the total number of students, class-wise student count, total number of teachers, and subject-wise teacher count.
login(): Authenticates the user login for the admin.
login_as_teacher(): Authenticates the login for a teacher.
registration(): Registers a new school with username and password.

Main Functionality:
The program provides a menu-driven interface for administrators and teachers.
Administrators can add new students, add new teachers, search for students or teachers, show student or teacher lists, generate and display results, and view the school overview.
Teachers can view their guided student list, create results, and view results for their classes.

File Handling:
The system reads and writes student and teacher information from/to text files.
Student and teacher lists are stored in separate text files.

User Authentication:
Users need to log in with their credentials (username and password) to access the system.
Admins and teachers have separate login functionalities.


Overall, the School Management System allows administrators and teachers to manage student and teacher information, generate results, and obtain an overview of the school's data. It provides a user-friendly interface with menu options for easy navigation and operation.
