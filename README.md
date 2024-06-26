 # School Demo PHP Project

This project is a simple PHP application for managing students and classes in a school environment. It allows you to perform CRUD operations on students and classes, upload images, and view student details with class information.

## Features

- Display a list of all students with their basic information and class details.
- Add, edit, and delete students.
- Manage classes including adding, editing, and deleting classes.
- Upload and display student profile images.
- Search functionality for students by name and class.
- Responsive design using Bootstrap for a clean UI.

## Project Structure
school_demo/
│
├── assets/ # CSS, JS, and image assets
│ ├── css/
│ ├── js/
│ └── img/
│
├── includes/ # PHP files for database connection and utility functions
│
├── index.php # Home page displaying list of students
├── create.php # Form to add a new student
├── view.php # View details of a student
├── edit.php # Edit details of a student
├── delete.php # Delete a student
├── classes.php # Manage classes (add, edit, delete)
│
├── edit_class.php # Edit details of a class
├── delete_class.php # Delete a class
│
├── README.md # Documentation file
└── school_db.sql # SQL script to create database and tables


## Getting Started

1. **Database Setup**:
   - Import `school_db.sql` into your MySQL database to create the necessary database (`school_db`) and tables (`student`, `classes`).

2. **Configuration**:
   - Update database connection details in PHP files (`index.php`, `create.php`, `edit.php`, `delete.php`, `classes.php`, `edit_class.php`, `delete_class.php`) under `includes/db_connect.php`.

3. **Usage**:
   - Navigate to `index.php` to view the list of students.
   - Use `create.php` to add new students and upload their profile images.
   - Edit or delete students using `edit.php` and `delete.php` respectively.
   - Manage classes with `classes.php`, and edit or delete classes with `edit_class.php` and `delete_class.php`.

4. **Notes**:
   - Ensure PHP server (`XAMPP`, `WAMP`, or similar) is set up to run PHP files.
   - Use modern browsers (Chrome, Firefox, Safari) for the best user experience.

## Technologies Used

- PHP
- MySQL
- HTML/CSS (Bootstrap)
- JavaScript (for image preview)

## Contributors

- Mahaveer Suthar(https://github.com/Mahaveer143s)





https://github.com/Mahaveer143s/Student-Project/assets/110727771/5d1732a2-e4f3-478c-9235-f5e3fed0e961
https://github.com/Mahaveer143s/Student-Project/assets/110727771/cc02de93-5bb6-4264-9361-95a889e7addb
https://github.com/Mahaveer143s/Student-Project/assets/110727771/fb2d40a8-7f2c-4e2f-9216-4cf877c0ef26
https://github.com/Mahaveer143s/Student-Project/assets/110727771/d0804334-3be3-4b34-8795-a0edb4e7f4b8
https://github.com/Mahaveer143s/Student-Project/assets/110727771/38e7c106-7d5b-43f0-9673-ab02316e8e5b
https://github.com/Mahaveer143s/Student-Project/assets/110727771/72ffd59c-ec70-450f-90de-30ad02b25cce
https://github.com/Mahaveer143s/Student-Project/assets/110727771/7c03e7be-b904-4c94-aec5-bb8461fb2688
https://github.com/Mahaveer143s/Student-Project/assets/110727771/3c5ac0ef-296c-4ba5-b6de-3768dc687f19
