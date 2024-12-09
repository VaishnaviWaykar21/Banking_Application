Banking Management System

A simple Java-based console application to manage customer banking operations. This project demonstrates basic CRUD operations using JDBC for database connectivity. It provides functionalities like adding customers, updating details, withdrawing, depositing money, and viewing customer data.


 Features

* Add Customers: Insert customer details into the database.

* Update Customer Details: Update customer name, balance, or account number.

* Delete Customers: Remove a customer record from the database.

* View All Customers: Retrieve and display all customer records.

* View Single Customer Details: Fetch details of a specific customer using their ID.

* Withdraw Funds: Deduct a specified amount from a customer’s balance.

* Deposit Funds: Add a specified amount to a customer’s balance.

 Project Structure

* Packages

  * com.Entity: Contains the core business logic (Bank.java).
  
  * com.Configuration: Handles database connection configuration (Config.java).
  
  * com.Unimplemented: Interface defining banking operations (BankUnimpl).
  
   Database Table

* customer: The table storing customer details.

* Columns:

  * id (INT): Customer ID
  
  * name (VARCHAR): Customer name
  
  * balance (DOUBLE): Account balance
  
  * account_no (BIGINT): Account number
  
  Prerequisites

  * Java Development Kit (JDK) 8 or higher
  
  * MySQL Database
  
  * JDBC Driver for MySQL
  
  * IDE (e.g., Eclipse, IntelliJ IDEA)
