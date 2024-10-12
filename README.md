# SREC QUESTIFY - Automatic Question Paper Generator

SREC QUESTIFY is a web-based application designed to generate question papers automatically from a database of questions. It utilizes a question bank stored in MySQL and dynamically creates random question papers each time a user interacts with the system. The project is developed using HTML, CSS, Bootstrap, PHP, and MySQL, and it runs on XAMPP or any similar local server environment.

## Features
- **Dynamic Question Paper Generation:** Randomly generates question papers using a question bank stored in a MySQL database.
- **User-Friendly Interface:** The application features a clean and responsive UI developed with HTML, CSS, and Bootstrap.
- **Customizable Question Bank:** Administrators can easily manage and update the question bank.
- **PHP Backend:** The application’s logic is powered by PHP, ensuring dynamic data fetching and processing from the MySQL database.
- **Secure Access:** Includes basic authentication and security checks for database operations.

## Prerequisites
- XAMPP (or any local server environment like MAMP or WAMP)
- Web browser (Google Chrome, Mozilla Firefox, etc.)

### Technologies Used
- **HTML5:** For structuring the web pages.
- **CSS3 & Bootstrap:** For styling and responsive design.
- **PHP:** For backend functionality and server-side scripting.
- **MySQL:** For storing and managing the question bank.
- **JavaScript:** For client-side interactivity.

## Installation

- Set Up XAMPP [Download XAMPP](https://www.apachefriends.org/index.html) and install it on your machine.
- Start **Apache** and **MySQL** services from the XAMPP control panel.
- Clone this repository or download the project files.
```bash
   git clone https://github.com/yourusername/srec-questify.git
  ``` 
- Copy the project folder into the htdocs directory of your XAMPP installation.
```bash
C:/xampp/htdocs/srec-questify/
```
- Set Up the MySQL Database
Open phpMyAdmin by navigating to `http://localhost/phpmyadmin/` in your browser.
Create a new database called questify_db.

- Update Database Configuration
Update the database credentials if needed (default settings for XAMPP should work fine).
```bash
<?php
$host = 'localhost';
$user = 'root';
$password = '';
$dbname = 'questify_db';
?>
```
- Run the Application
Open your browser and go to `http://localhost/SREC-QUESTIFY/GENERATOR/login_form.php`.
You should now be able to interact with the SREC QUESTIFY application.

## Example Screenshots
![1](https://github.com/user-attachments/assets/7acce6f9-9cd8-4e89-868c-c8fcb5e77188)
![2](https://github.com/user-attachments/assets/107c5513-3180-4c86-9e62-be802c370236)
