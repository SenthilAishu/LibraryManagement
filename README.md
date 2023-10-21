# LibraryManagement

# Index
     1)Introduction
     2)Objective
     3)Script
     4)Setup
     5)Running the Application
     6)usage
     7)Screenshot of the Output
     8)Contributor
     
# Introduction

A library management system CRUD application is a software program that helps libraries manage their Collections, Lending activities, and other related functions.
CRUD stands for Create, Read, Update, and Delete, which are the four basic functions that the application must support to effectively manage a library's collection of books, journals, and other materials.
The purpose of the library management system is to provide a comprehensive and efficient way to manage the library's resources and make it easy for staff to keep track of books.
Overall, a library management system CRUDapplication is an essential tool for modern libraries that want to efficiently manage theircollections and provide excellent service to their patrons.
    
# Objective 

This Java application implements a basic Library Management System with a  MYSQL database. 
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

          3)Edit Book Details based on ISBN
![Screenshot 2023-10-20 164630](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/ec8a3ff3-af5d-4c3b-9374-4eb563ab86cd)
![Screenshot 2023-10-20 164652](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/cfd10e44-229b-4ef5-af09-da89984463ab)
![Screenshot 2023-10-20 164720](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/5762d7e1-94d3-41e4-a416-85c3754c2657)
           -After Editing The Book Details
           -Here I changed the Genre Column
![Screenshot 2023-10-20 165014](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/6d06f6a8-750a-4121-b083-024c27a42da9)

          4)Delete a book from the library
![Screenshot 2023-10-20 165105](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/da286fa6-fb23-416f-9586-da0a884c77e8)
![Screenshot 2023-10-20 165124](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/595714ea-14d9-432e-a179-d5ddfcb566ec)

           -Before Delete the book 
![Screenshot 2023-10-20 165014](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/7837b372-2d49-441a-966a-577d18f39043)

           -After Delete the book
![Screenshot 2023-10-20 165153](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/0f9aa40a-0b30-4047-9390-678a38c2f4ef)

         5) For Exit the Program
![Screenshot 2023-10-20 165235](https://github.com/SenthilAishu/LibraryManagement/assets/91359845/e8f9f541-2420-47eb-b8b7-8562a048465e)
      

## Contributors

- Senthilkumar.A

Feel free to contribute to the project or report issues.

