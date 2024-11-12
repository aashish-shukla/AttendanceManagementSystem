# Attendance Management System (PHP)

## Overview
The Attendance Management System is a web-based application developed using **PHP**, **MySQL**, and **JavaScript**. It automates the process of attendance tracking for educational institutions or workplaces, offering an intuitive user interface for both administrators and regular users. The system allows attendance to be marked, monitored, and analyzed with ease, improving overall efficiency and accuracy.

## Features
- **Role-Based Access Control**: 
  - Admins can manage user roles, view attendance records, and generate reports.
  - Regular users can mark and view their own attendance.
  
- **Real-Time Attendance Tracking**: 
  - Attendance is updated in real-time, ensuring accuracy and immediacy.

- **Secure Data Handling**:
  - User passwords are securely hashed using encryption techniques.
  - Prevents SQL injection and Cross-Site Scripting (XSS) attacks through proper validation and sanitation.

- **Attendance Reports**:
  - Admins can generate detailed attendance reports with visual statistics.
  - Attendance data can be exported for offline storage and review.

- **Scalability**: 
  - Designed to support a variety of institutions and organizations, scalable to meet growing needs.

## Technologies Used
- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript, AJAX
- **Security**: Password Encryption, SQL Injection Prevention, XSS Protection

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/attendance-management-system.git
2. Set up a MySQL database and import the provided SQL file to create the necessary tables.

3. Configure the database connection settings in the config.php file.

4. Deploy the project on a PHP-compatible web server.

5. Access the system via your browser by navigating to the root directory.

