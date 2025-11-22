🧭 Online Tourism Management System

A dynamic web application built using PHP + MySQL that allows users to browse tour packages, book trips, send enquiries, and manage their profile. Admins can manage packages, users, bookings, and website content through a secure dashboard.

🌟 Features
$User Features

>Browse tour packages

>View package details

>Check date availability

>Book packages

>User signup/login

>Profile management

>Change password

>Contact / enquiry form


$Admin Features

>Manage tour packages (add, update, delete)

>Manage bookings

>Manage users

>View and reply to enquiries

>Admin authentication

>Dashboard statistics

🗂️ Project Structure

onlinetourism/
│── sql file/
│   └── tms.sql            # Database schema & sample data
│── tms/
│   ├── admin/             # Admin dashboard files
│   ├── css/               # Stylesheets
│   ├── fonts/
│   ├── images/
│   ├── includes/          # Header, Footer, Config, Login/Signup
│   ├── js/                # JavaScript files
│   ├── index.php          # Homepage
│   ├── package-list.php
│   ├── package-details.php
│   ├── enquiry.php
│   └── ...


💾 Installation & Setup
1. Clone the Repository
  git clone https://github.com/your-username/onlinetourism.git

2. Move Project to Server Directory For XAMPP:

  htdocs/onlinetourism/

3. Import Database

  Open phpMyAdmin

  Create a database: tms

  Import file: sql file/tms.sql

4. Configure Database Connection

  /tms/includes/config.php

  $servername = "localhost";
  $username   = "root";
  $password   = "";
  $dbname     = "tms";

5. Run the Project
  http://localhost/onlinetourism/tms/

🔐 Admin Login

  Default admin credentials (if included in SQL):

  Email: admin@gmail.com
  Password: Test@123


🛠️ Technologies Used

PHP

MySQL

HTML / CSS / JS

Bootstrap

jQuery
