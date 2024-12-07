This project is a simple user management system that allows CRUD (Create, Read, Update, Delete) operations for user data. It uses PHP for the backend, MySQL for the database, and HTML/CSS for the frontend. The project Structure: project/ ├── index.html # Main page ├── styles.css # Stylesheet for the main page ├── script.js # JavaScript for client-side functionality ├── connect.php # Database connection script ├── cancel.php # Script to handle user cancellation ├── admin.php # Admin page displaying the user table ├── admin.css # Admin page styles ├── admin.js # Optional JS for admin functionality ├── update.php # Form to update user details ├── update_handler.php # Backend script to handle user updates ├── delete.php # Script to delete a user ├── README.md # Project documentation

Need some set-up to Run the project

Move Files to Server Directory { C:/xampp/htdocs/ }

Open XAMPP control panel and Start the Apache and MySQL services.

Create the Database
Open phpMyAdmin (typically available at http://localhost/phpmyadmin).

Create a new database named CustomerInfo.

Run the following SQL queries in the SQL tab to create the user table--------- 
CREATE TABLE user ( id INT AUTO_INCREMENT PRIMARY KEY,
name VARCHAR(255) NOT NULL,
email VARCHAR(255) NOT NULL UNIQUE,
phone VARCHAR(15),
address VARCHAR(255)
);

************* You are all good to run this project. *****************
