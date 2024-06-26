# JDBC Connectivity with MySQL using Eclipse

## Description
This project demonstrates how to connect a Java application to a MySQL database using JDBC in Eclipse IDE. It includes basic operations like connecting to the database, executing SQL queries, and retrieving results.

## Requirements
- Java Development Kit (JDK)
- Eclipse IDE
- MySQL Database
- MySQL Connector/J (JDBC driver)

## Setup Instructions

### 1. Install MySQL
- Download and install MySQL from the [official website](https://dev.mysql.com/downloads/installer/).

### 2. Create a Database
- Create a new database in MySQL. For example:
  ```sql
  CREATE DATABASE svdata;

  git clone https://github.com/Gowsika4/JDBC-Connectivity-with-MySQL.git

  Open Eclipse:

### Open Eclipse IDE.
- Select File -> Open Projects from File System... and import the cloned project.
- Add MySQL Connector/J to the Project:

### Download MySQL Connector/J from the official website.
- In Eclipse, right-click the project and select Build Path -> Configure Build Path....
- Go to the Libraries tab and click Add External JARs....
- Add the downloaded MySQL Connector/J JAR file.
### Configure Database Connection
Update the database connection details in the Java code. 
- For example:
java
Copy code
String url = "jdbc:mysql://localhost:3306/svdata";
String username = "root";
String password = "root";


