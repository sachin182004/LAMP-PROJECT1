


![OIP](https://github.com/user-attachments/assets/38e094d0-18c4-4334-abf7-6667c4e1dc03)














LAMP PROJECT
 
 Introduction:
 
 This project demonstrates a simple web application built using the LAMP stack:
 Linux, Apache, MariaDB, and PHP. The app contains a form (sample.php) that
 collects user input and a script (submit.php) that stores it into MariaDB.
 Objective:
 To deploy a working LAMP-based app that collects form data, processes it with PHP,
 stores it in MariaDB, and returns a success response.

 commands used:
 
 1. Linux – Base OS for the server.
 2. Apache (httpd) – Serves PHP pages and handles HTTP requests.
 3. PHP – Processes form submissions and connects to the database.
 4. MariaDB 10.5 – Stores user details.

 Application Flow:
 
 1. User opens sample.php.
 2. Apache serves the form.
 3. User submits data to submit.php.
 4. PHP validates input and inserts it into MariaDB.
 5. MariaDB stores the record.
 6. PHP returns success output.
 Architecture (Vertical Layout):
 Web Browser → Apache httpd → PHP → MariaDB 10.5

 Features:

- User form interface- Backend PHP processing- Database insertion- Dynamic output- Works on any Linux server

 Folder Structure:

 /var/www/html/
 sample.php
 submit.php
 Database Schema:
 Database: lampdb
 Table: users (id, name, email, website, comment, gender)

Installation Steps Summary:

 1. Install Apache, PHP, MariaDB.
 2. Start services.
 3. Create PHP files.
 4. Create database & table.
 5. Test application.

 Conclusion:
 
 This LAMP project demonstrates backend development fundamentals, including
 form handling, PHP scripting, and database operations
