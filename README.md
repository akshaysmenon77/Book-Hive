# About Book Hive Application
Created a full backend application were User’s able to view and place order of the books. As well as it has another Admin user were he/she able to add, update and delete books from database. The level of authentication rule is set by using JWT Authentication. 


# Function used in the project:

## For User:

1) view books 
2) search by book_name 
3) search by book_id
4) Place order by book_id
5) View placed order by using order_id or order_name
6) Delete orders by using book_id

## For Admin:

1) ViewBooks
2) Add new Books to Database 
3) Delete existing Books in Database
4) Update existing Books in Database
5) View orders of the user by order_id or by order name
6) Can place an order to User.
7) Delete the orders of the User

All function was tested using Post-Man and TestNG

# Implementation 

The application was developed uisng Spring Boot Application and database used as MySql. All the funcations were tested using Post-Man and Test-Ng. In order to run this application use Intellij IDE and configure MySql server and create database name as BookHive. You can make your own database and do the nesseracy changes in application.properties. 



## How to run the application?

  ### Prerequisites:
  - Java jdk 8 or above
  - vs code or any code editior 
  - Intellij IDE
  - Spring Boot
  - Post-Man
  - MySql 

  1. Install JDK or Java Development Kit 8 or above version 
  2. run CapstoneProjectApplication.java file using Intellij IDE (After configuring Database)
  3. copy localhost:8080/ to browser
  4. do the opertions by browsing to controller file or by runing Test-Ng scripts.
