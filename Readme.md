# Car Rental is a project for the NTUA Databases course.
An application which implements a user interface for a car rental business. It enables the user to view and manage all the business entities such as Stores, Employees, Customers, Vehicles and vehicle booking procedure.

## Technologies used
  - Backend
    - MySQL
    - php
  - Frontend
    - html, css
    - Javascript
    - jQuery

## Deploy
1. Run mysql server and set a desired user and password.
    - Run `create-database.sql` with your mysql client to create the database schema.
    - (Optionally) Run `initialize-data.sql` for mock data.
2. Modify `htdocs/php/common.php` and set the mysql user and password.
3. Setup a php server and copy the `htdocs` contents to your php server deployment location (for development preferably choose xampp)


**Note**: The E-D diagram of the database is located in the file phpmyadmin-relational.png in the current folder.
