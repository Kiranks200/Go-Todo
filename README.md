# Go-Todo
A simple CRUD based todolist using Golang and Mysql with a basic html frontend.

Actions to be taken in Mysql
Create a database called demo_todo by running the following SQL command:
CREATE DATABASE demo_todo;

Create the Todos Table
CREATE TABLE todos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    completed BOOLEAN NOT NULL,
    created_at DATETIME NOT NULL
);


SHOW TABLES;
You can also check the table structure with:
