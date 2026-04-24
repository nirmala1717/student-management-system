# Student Management System

## Overview

This is a Python-based console application that allows users to manage student records efficiently. The system supports basic CRUD operations and stores data using a JSON file.

## Features

* Add new student with ID, name, scores, and skills
* Update existing student details
* Delete student records
* View all student details with statistics:

  * Average score
  * Highest score
  * Lowest score
* Search students based on skills
* Data persistence using JSON file

## Technologies Used

* Python
* JSON (File Handling)
* OS Module

## Project Structure

```
student-management-system/
│── student_app.py
│── 14_file_manage/
│   └── students.json
│── README.md
```

## How to Run the Project

1. Clone the repository:

   ```
   git clone https://github.com/nirmala1717/student-management-system.git
   ```
2. Navigate to the project folder:

   ```
   cd student-management-system
   ```
3. Run the application:

   ```
   python student_app.py
   ```

## Sample Functionalities

* Add Student → Enter ID, Name, Scores, Skills
* Update Student → Modify student name
* Delete Student → Remove student record
* Read Student → Display all students with analysis
* Search by Skill → Find students with a specific skill

## Example Output

```
ID: 102
Name: Mike
All Scores: [80, 90]
Average Score: 85.0
Highest Score: 90
Lowest Score: 80
All Skills: {'python', 'java'}
Skills Count: 2
```

## Future Improvements

* Add GUI using Tkinter or Web (Django/Flask)
* Add database support (MySQL/MongoDB)
* Add authentication (Login system)
* Improve error handling and validation

## Author

Nirmala Patlavath
