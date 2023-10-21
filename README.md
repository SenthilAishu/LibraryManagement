# LibraryManagement

# Index
     1)Introduction
     2)Objective
     3)Script
     4)Setup
     5)Running the Application
     6)usage
     7)Screenshot of the Output
     8)Contributors
     
# Introduction

A library management system CRUD application is a software program that helps libraries manage their Collections, Lending activities, and other related functions.
CRUD stands for Create, Read, Update, and Delete, which are the four basic functions that the application must support to effectively manage a library's collection of books, journals, and other materials.
The purpose of the library management system is to provide a comprehensive and efficient way to manage the library's resources and make it easy for staff to keep track of books.
Overall, a library management system CRUDapplication is an essential tool for modern libraries that want to efficiently manage theircollections and provide excellent service to their patrons.
    
# Objective 

This Java application implements a basic Library Management System with a SQL database. 
Users can perform CRUD operations on books in the library.

# Technology used
  Java[Core&Advanced],
  MySQL.
  
# Script

CREATE DATABASE library;
USE library;

CREATE TABLE books (
  id INT AUTO_INCREMENT PRIMARY KEY,
  title VARCHAR(255) NOT NULL,
  author VARCHAR(255) NOT NULL,
  isbn VARCHAR(13) NOT NULL UNIQUE,
  publication_year INT NOT NULL,
  genre VARCHAR(255)
);

## Setup

1. Set up a SQL database (MySQL) and create a database called `library`.
2. Run the SQL script provided in `Step 2` of the project setup to create the `books` table.

## Running the Application

1. Clone this repository to your local machine.
2. Open the project in  Java IDE (e.g., Eclipse, IntelliJ IDEA).
3. Add the JDBC Driver to the project.
4. Configure the database connection in the `LibraryDatabase` class.
5. Run the `LibraryManagementApp` class to start the application.

## Usage

- Follow the console - menu to perform CRUD operations on books in the library.

## ScreenShot of the Output
        - These tasks mainly focused on CRUD Application. Here are some of the output of the specific requirements.
          1) Add a Book to the library's collection
![Screenshot 2023-10-20 161648](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/e496fb6f-3b67-4ecb-b7f4-2f4752791fdc)
![Screenshot 2023-10-20 162658](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/f31ff03b-4b2a-4233-b30b-1ff561118d05)
          2)Display all the books in the library
![Screenshot 2023-10-20 164149](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/8bf593ef-2713-4612-b57c-96f9621ce31b)
![Screenshot 2023-10-20 164235](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/0efd5c59-f468-4c28-bc9e-2f359bcc3b89)
![Screenshot 2023-10-20 164254](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/5ea7fc43-018e-44f9-8d04-401d99734a13)
      - In MySQL Database view
![Screenshot 2023-10-20 163950](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/0d8c71f9-e1d2-4d0c-9679-3ebb9521e347)



## Contributors

- Senthilkumar.A

Feel free to contribute to the project or report issues.

