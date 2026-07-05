# Hotel Management System

Hotel Management System is a web-based application developed to simplify hotel room reservation and management. It allows customers to register, book rooms, view reservations, and manage their profiles, while administrators can efficiently manage reservations through a dedicated admin panel.
This project was created as a learning exercise to understand web development concepts using PHP, MySQL, JavaScript, HTML, and CSS. It is intended for educational purposes and demonstrates CRUD operations, user authentication, database management, and responsive web interfaces.

FEATURES
Customer Features:
User Registration and Login,
Secure Authentication,
Room Pricing Display,
Online Room Reservation,
View Reservation History,
Update User Profile,
Responsive User Interface.

Admin Features
Admin Login,
Manage Customer Reservations,
View Booking Details,
Update Reservation Status,
Manage Customer Information.

TECHNOLOGY USED
 Frontend :- HTML, CSS, JavaScript.
 Backend :-  PHP
 Database :- MYSQL

## Table of Contents
- [Setup](#setup)
- [Screenshots](#screenshots)
- [For developer](#for-developer)

## Setup
1. Make sure you have `MySQL` and a web server to run/interpret `PHP` in your system.
2. Clone or download the repo and put it to `xampp/htdocs/` if you're using windows, otherwise check tutorial(s) for your corresponding web server and OS. 
3. Install dependencies for JavaScript, `npm install` and PHP, `composer install`.
4. Create a database named `hotel` and run the script [`hotel.sql`](https://github.com/tramyardg/hotel-mgmt-system/blob/master/hotel.sql) to create tables and populate data. Make sure your configuration matches with [`app/DB.php`](https://github.com/tramyardg/hotel-mgmt-system/blob/master/app/DB.php#L14), otherwise make the desired changes.
5. Run the app.

## Create an account
1. Go to the registration page (register.php) i.e. http://hotel.local/register.php
2. Enter your info.
3. To make an admin account
   - 3.1 go to your hotel database
   - 3.2 select table customer
   - 3.3 select an account
   - 3.4 change the value of isadmin to 1
 

## Screenshots
**Customer**
- Room pricing
![room_pricing](https://user-images.githubusercontent.com/5623994/51089111-f0131a00-1735-11e9-8758-847091e9b68e.PNG)
- Reservation form
![reservation_form](https://user-images.githubusercontent.com/5623994/51089124-218be580-1736-11e9-9400-3cfd5454fe56.PNG)
- View reservation(s)
![view_booking](https://user-images.githubusercontent.com/5623994/51089133-38cad300-1736-11e9-857a-64f9956b9f17.PNG)
- About user
![about_user](https://user-images.githubusercontent.com/5623994/51089140-4f712a00-1736-11e9-850f-6bb67151711e.PNG)

**Admin**
- Manage reservations
![manage_booking](https://user-images.githubusercontent.com/5623994/51089150-6d3e8f00-1736-11e9-9af0-601ef58847b4.PNG)

## For developer

Software/ Tools Used
● Visual Studio Code
● XAMPP Server
● MySQL Database
● Google Chrome Browser
Run step by stephStep
1: Install XAMPPFirst, install XAMPP on your system
.XAMPP provides:
● Apache Server
● MySQL Database
● PHP Support
Download from:https://www.apachefriends.org
After installation, open XAMPP Control Panel 
.Step 2: Start Apache and MySQL
In XAMPP Control Panel, click:
● Start Apache
● Start MySQL
Both services should turn green.
Step 3: Copy Project Folder
Copy your project folder
Hotel Management System
Paste it inside:
C:\xampp\htdocs\
Example:  C:\xampp\htdocs\hotel_management_system
Step 4: Open phpMyAdmin
Open browser and type:
http://localhost/phpmyadmin
Click New and create database.
Example database name:hotel
Step 5: Import Database
Inside database → click Import
Choose the .sql file from project folder.
Example:  hotel.sql
       Then click Go Database tables will be created automatically. 
Step 6: Check Database Connection
Open project file: db.php
Check database name:
  $conn = mysqli_connect("localhost","root","","hotel");
Make sure database name matches phpMyAdmin database.
Step 7: Run Project
 Open browser and type:http://localhost/hotel_management_system 
Step 8: Admin LoginIf admin panel is available, 
open:http://localhost/hotel_management_system/admin
Login using admin username and password.
