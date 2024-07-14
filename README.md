# Kotlin Learning Roadmap

## Table of Contents
1. [Introduction to Kotlin](#1-introduction-to-kotlin)
   - [1.1 Basics of Kotlin](#11-basics-of-kotlin)
   - [1.2 Operators and Expressions](#12-operators-and-expressions)
   - [1.3 Simple Programs](#13-simple-programs)
2. [Control Flow](#2-control-flow)
   - [2.1 Conditional Statements](#21-conditional-statements)
   - [2.2 Loops](#22-loops)
   - [2.3 Complex Control Flow](#23-complex-control-flow)
3. [Functions and Lambdas](#3-functions-and-lambdas)
   - [3.1 Basic Functions](#31-basic-functions)
   - [3.2 Functions with Parameters and Return Types](#32-functions-with-parameters-and-return-types)
   - [3.3 Lambdas and Higher-Order Functions](#33-lambdas-and-higher-order-functions)
4. [Object-Oriented Programming (OOP)](#4-object-oriented-programming-oop)
   - [4.1 Classes and Objects](#41-classes-and-objects)
   - [4.2 Inheritance and Polymorphism](#42-inheritance-and-polymorphism)
   - [4.3 Advanced OOP](#43-advanced-oop)
5. [Collections and Data Structures](#5-collections-and-data-structures)
   - [5.1 Lists and Arrays](#51-lists-and-arrays)
   - [5.2 Sets and Maps](#52-sets-and-maps)
   - [5.3 Complex Data Structures](#53-complex-data-structures)
6. [Null Safety and Exception Handling](#6-null-safety-and-exception-handling)
   - [6.1 Null Safety](#61-null-safety)
   - [6.2 Exception Handling](#62-exception-handling)
   - [6.3 Advanced Exception Handling](#63-advanced-exception-handling)
7. [Advanced Kotlin Features](#7-advanced-kotlin-features)
   - [7.1 Extension Functions](#71-extension-functions)
   - [7.2 Higher-Order Functions](#72-higher-order-functions)
   - [7.3 Coroutines and Concurrency](#73-coroutines-and-concurrency)
8. [Working with Android](#8-working-with-android)
   - [8.1 Basic Android Development](#81-basic-android-development)
   - [8.2 Advanced Android Development](#82-advanced-android-development)
9. [Best Practices and Testing](#9-best-practices-and-testing)
   - [9.1 Code Quality](#91-code-quality)
   - [9.2 Unit Testing](#92-unit-testing)
   - [9.3 Performance Optimization](#93-performance-optimization)


## 1. Introduction to Kotlin

### 1.1 Basics of Kotlin
**Assignments:**
1. **Hello World:** Write a Kotlin program to print "Hello, World!".
2. **Data Types Display:** Create a Kotlin program that declares variables of different data types (String, Int, Float, Boolean) and prints them.

### 1.2 Operators and Expressions
**Assignments:**
1. **Basic Calculator:** Create a Kotlin program that acts as a basic calculator, performing operations like addition, subtraction, multiplication, and division based on user input.
2. **Average Calculator:** Write a Kotlin program to calculate the average of five numbers.

### 1.3 Simple Programs
**Assignments:**
1. **Bank Account Initializer:** Write a Kotlin program to initialize and display the details of a bank account with properties like `accountNumber`, `accountHolderName`, and `balance`.
2. **Simple Inventory System:** Write a Kotlin program to manage a small inventory system where you can add, update, and display the details of items such as `itemName`, `quantity`, and `price`.

## 2. Control Flow

### 2.1 Conditional Statements
**Assignments:**
1. **Employee Bonus Calculator:** Write a Kotlin program to calculate the bonus for employees based on their performance ratings using if-else statements.
2. **Temperature Converter:** Create a Kotlin program to convert temperatures between Celsius and Fahrenheit using when statements.

### 2.2 Loops
**Assignments:**
1. **Number Guessing Game:** Create a Kotlin program for a number guessing game where the user has to guess a number between 1 and 100 with feedback on whether the guess is too high or too low.
2. **Sum of Natural Numbers:** Write a Kotlin program to sum the first 50 natural numbers using a for loop.

### 2.3 Complex Control Flow
**Assignments:**
1. **Sales Data Analyzer:** Write a Kotlin program to analyze monthly sales data stored in a list and determine the highest, lowest, and average sales using loops.
2. **Pattern Printing:** Create a Kotlin program to print various patterns (e.g., asterisks in a pyramid shape) using nested loops.

## 3. Functions and Lambdas

### 3.1 Basic Functions
**Assignments:**
1. **Invoice Generator:** Write a Kotlin function to generate an invoice for a list of purchased items, calculating the total amount and applying a discount if applicable.
2. **GCD Calculator:** Create a Kotlin program with a function to calculate the greatest common divisor (GCD) of two numbers.

### 3.2 Functions with Parameters and Return Types
**Assignments:**
1. **Prime Number Checker:** Create a Kotlin program with a function to check if a given number is prime and another function to find all prime numbers within a range.
2. **Employee Salary Calculator:** Write a Kotlin program with functions to calculate the gross salary, net salary, and deductions for an employee.

### 3.3 Lambdas and Higher-Order Functions
**Assignments:**
1. **Employee Filter:** Write a Kotlin program using a lambda expression to filter a list of employees based on their department and salary.
2. **Task Scheduler:** Create a Kotlin program that demonstrates the use of higher-order functions by implementing a simple task scheduler that executes tasks at specific intervals.

## 4. Object-Oriented Programming (OOP)

### 4.1 Classes and Objects
**Assignments:**
1. **Library Management System:** Create a `Book` class with properties like `title`, `author`, and `isbn`. Then create a `Library` class to manage a collection of books, including methods to add, remove, and search for books.
2. **Bank Account Class:** Develop a `BankAccount` class with properties and methods to deposit and withdraw money, and to check the account balance.

### 4.2 Inheritance and Polymorphism
**Assignments:**
1. **Online Store:** Develop a `Product` class with properties like `name`, `price`, and `category`. Then create a `ShoppingCart` class that can add products, remove products, and calculate the total price.
2. **Vehicle Hierarchy:** Write a Kotlin program that creates a base class `Vehicle` and derived classes `Car` and `Bike`, each with specific properties and methods. Demonstrate polymorphism by overriding a method in the derived classes.

### 4.3 Advanced OOP
**Assignments:**
1. **Employee Management System:** Create a base class `Employee` with properties like `name`, `id`, and `salary`. Derive classes `Manager` and `Developer` with additional properties and methods.
2. **E-commerce Application:** Develop classes to represent `Customer`, `Order`, and `Product`, including methods for placing an order, processing payment, and generating an invoice.

## 5. Collections and Data Structures

### 5.1 Lists and Arrays
**Assignments:**
1. **Customer Management System:** Write a Kotlin program to manage customer data using a list. The program should allow adding new customers, updating existing customer details, and displaying all customers.
2. **To-Do List Application:** Create a Kotlin program that uses an array to store to-do tasks and allows the user to add, update, and delete tasks.

### 5.2 Sets and Maps
**Assignments:**
1. **Product Inventory:** Create a Kotlin program that uses a map to store product information with the product ID as the key and product details as the value. Implement functions to add, update, and search for products.
2. **Unique Email Collector:** Write a Kotlin program to collect unique email addresses using a set and print them.

### 5.3 Complex Data Structures
**Assignments:**
1. **Employee Attendance Tracker:** Write a Kotlin program to track employee attendance using a set. The program should allow marking attendance for employees and displaying the list of employees who attended on a given day.
2. **Multi-Dimensional Array:** Create a Kotlin program to manage a 2D array representing a tic-tac-toe game board. Implement functions to update the board and check for a winner.

## 6. Null Safety and Exception Handling

### 6.1 Null Safety
**Assignments:**
1. **User Login System:** Write a Kotlin program to simulate a user login system that checks for null values in the username and password fields and handles exceptions for incorrect login attempts.
2. **User Profile:** Create a Kotlin program that safely handles optional user profile details such as middle name and phone number.

### 6.2 Exception Handling
**Assignments:**
1. **File Reader:** Create a Kotlin program that reads data from a file and handles possible exceptions such as file not found or read errors.
2. **Order Processing System:** Write a Kotlin program to process customer orders, checking for null values in

 the order details and handling exceptions for invalid order data.

### 6.3 Advanced Exception Handling
**Assignments:**
1. **Transaction System:** Develop a Kotlin program for a simple banking transaction system that handles exceptions for insufficient balance and invalid account details.
2. **API Data Fetching:** Write a Kotlin program to fetch data from a mock API and handle exceptions for network errors and invalid responses.

## 7. Advanced Kotlin Features

### 7.1 Extension Functions
**Assignments:**
1. **String Utilities:** Write a Kotlin program that defines and uses an extension function for the String class to check if a string is a valid email address.
2. **List Extensions:** Create a Kotlin program that adds an extension function to the List class to find the second largest element in the list.

### 7.2 Higher-Order Functions
**Assignments:**
1. **Task Scheduler:** Create a Kotlin program that demonstrates the use of higher-order functions by implementing a simple task scheduler that executes tasks at specific intervals.
2. **Custom Sorting:** Write a Kotlin program that uses higher-order functions to sort a list of objects based on various properties.

### 7.3 Coroutines and Concurrency
**Assignments:**
1. **Concurrent Data Fetching:** Write a Kotlin program that uses coroutines to fetch data concurrently from multiple APIs and combines the results.
2. **Asynchronous File Processing:** Create a Kotlin program that reads and processes large files asynchronously using coroutines.

## 8. Working with Android

### 8.1 Basic Android Development
**Assignments:**
1. **User Registration App:** Create a simple Android app in Kotlin that allows users to register by entering their details such as name, email, and password. Display a confirmation message upon successful registration.
2. **To-Do List App:** Develop an Android app that allows users to add, update, and delete tasks from a to-do list. Use a RecyclerView to display the list of tasks.

### 8.2 Advanced Android Development
**Assignments:**
1. **Weather App:** Write an Android app that fetches and displays weather information for a given location. Use an API to get the weather data and display it in a user-friendly format.
2. **Expense Tracker:** Create an Android app that allows users to track their daily expenses. Users should be able to add, edit, and delete expense entries, and view a summary of their spending.

## 9. Best Practices and Testing

### 9.1 Code Quality
**Assignments:**
1. **Code Review:** Refactor a provided piece of Kotlin code to follow Kotlin coding conventions and best practices. Write comments to explain the changes.
2. **Documentation:** Write proper documentation for a given Kotlin class and its methods.

### 9.2 Unit Testing
**Assignments:**
1. **Unit Testing:** Write unit tests for a given Kotlin function using JUnit. Ensure that all edge cases are covered.
2. **Mocking:** Create unit tests for a class that interacts with an external service, using mocking to simulate the service.

### 9.3 Performance Optimization
**Assignments:**
1. **Performance Optimization:** Analyze a piece of Kotlin code for performance bottlenecks and suggest improvements. Implement the improvements and compare the performance before and after optimization.
2. **Memory Management:** Write a Kotlin program that demonstrates efficient memory management techniques, avoiding memory leaks.


