# Java Swing Login Application
This is a Java Swing-based desktop login application connected to a MySQL database. The application allows users to log in with a username and password, and includes additional functionality to change the username or password securely.

## Features
- Login system with username and password authentication
- Change Username and Password form with validations
- MySQL database integration using JDBC
- User-friendly GUI built with NetBeans Swing GUI Builder

## Tech Stack and Tools
- Java (JDK 8 or higher)
- Swing (Java GUI)
- MySQL
- JDBC
- NetBeans IDE

## Database Schema
Make sure you create a MySQL database with the following structure:
```
CREATE DATABASE loginapp;
USE loginapp;
CREATE TABLE users (
    userid INT PRIMARY KEY AUTO_INCREMENT,
    username VARCHAR(50) UNIQUE,
    password VARCHAR(100)
);
Also Replace with your MySQL password when running locally
