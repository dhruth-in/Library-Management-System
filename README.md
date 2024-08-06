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
   git clone https://github.com/yourusername/library-management-system.git
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

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any inquiries or issues, please contact me at dhruthin1907@gmail.com.
