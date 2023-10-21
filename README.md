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
          1) Add a Book
          

## Contributors

- Senthilkumar.A

Feel free to contribute to the project or report issues.

