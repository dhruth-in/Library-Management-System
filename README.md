# Library Management System

## Overview

This Library Management System was developed as a DBMS project during my second year of studies. The project utilizes Bootstrap CSS, JavaScript, and PHP, with the database managed using phpMyAdmin and MySQL. The system provides two primary interfaces: one for admins and one for students.

## Features

### Admin Interface
- **Login:** Admins can log in using a username and password.
- **Dashboard:** Upon successful login, admins are redirected to a dashboard where they can:
  - Access and manage books.
  - Access and manage users.
  - Issue books to students.
- **Profile Management:** Admins can view and update their profile and change their password.

### Student Interface
- **Registration:** New students can register, and their information is stored in the database.
- **Login:** Registered students can log in to access their dashboard.
- **Dashboard:** The student dashboard allows students to:
  - View books they have issued.
- **Profile Management:** Students can view and update their profile and change their password.

## Technology Stack
- **Frontend:** Bootstrap CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL (managed via phpMyAdmin)

## Installation and Setup

### Prerequisites
- XAMPP or WAMP server
- PHP 7.4 or higher
- MySQL 5.7 or higher

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/dhruth-in/Library-Management-System.git
   ```

2. **Start the server:**
   - Launch XAMPP or WAMP server.
   - Ensure Apache and MySQL services are running.

3. **Set up the database:**
   - Open phpMyAdmin.
   - Create a new database named `library_db`.
   - Import the `library_db.sql` file located in the `database` folder of the cloned repository.

4. **Configure database connection:**
   - Open the `config.php` file in the root directory.
   - Update the following lines with your database credentials:
     ```php
     define('DB_SERVER', 'localhost');
     define('DB_USERNAME', 'root');
     define('DB_PASSWORD', '');
     define('DB_NAME', 'library_db');
     ```

5. **Run the application:**
   - Place the project folder in the `htdocs` directory (for XAMPP) or the `www` directory (for WAMP).
   - Open a web browser and navigate to `http://localhost/library-management-system`.

## Usage
1. **Admin Login:**
   - Navigate to `http://localhost/library-management-system/admin_login.php`.
   - Enter the admin credentials to access the dashboard.

2. **Student Registration and Login:**
   - Navigate to `http://localhost/library-management-system/student_register.php` to register.
   - After registration, log in at `http://localhost/library-management-system/student_login.php` to access the student dashboard.

##Snapshots

- Admin Login Page
![WhatsApp Image 2024-02-19 at 20 14 56_b2ad13db](https://github.com/user-attachments/assets/d1e2022c-8a46-4f8e-a1b2-424a4d14c8e9)

- Admin Dashboard
![WhatsApp Image 2024-02-19 at 20 25 25_6d9725fc](https://github.com/user-attachments/assets/02a74d0c-4dcc-41d4-ba71-77427df168f6)

- Admin Issue Books
![WhatsApp Image 2024-02-19 at 20 28 34_3bd82765](https://github.com/user-attachments/assets/68a892ac-e51d-4aa9-a659-a708e5b37b02)

- User Registration Page
![WhatsApp Image 2024-02-19 at 20 16 36_5eef17be](https://github.com/user-attachments/assets/bd2da146-fb1b-44ca-8590-c9f039eef7f9)

- User Login Page
![WhatsApp Image 2024-02-19 at 20 18 09_5802799b](https://github.com/user-attachments/assets/e95f3ba1-fe87-4896-8249-1d0d5fdb9e85)

- User Dashboard
![WhatsApp Image 2024-02-19 at 20 19 54_8a8885d5](https://github.com/user-attachments/assets/eac1b119-3b4d-469b-a365-9d1e8064261e)

- User Issued Books
![WhatsApp Image 2024-02-19 at 20 20 52_8578df79](https://github.com/user-attachments/assets/a4b0e05e-5f69-49a2-987f-f5ae132fc6c1)

## Author
Dhruthi N
