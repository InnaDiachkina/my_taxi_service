# Taxi Service

Taxi Service is the functional model for business in Transport Service. We have the opportunity to display current 
list drivers and cars. Also, we have the opportunity to update, add and delete information about them. 
Solid principles have been implemented in the project - code is easy to scale and maintain. 

## Project structure
three-tier architecture
+ the presentation tier (controllers)
+ the application logic tier (services)
+ the data tier (DAO)

## Used technologies
+ JDK 18
+ Tomcat 9.0.71
+ Maven 3.8.6
+ JSP
+ JDBC
+ MySQL 8.0

## You can use this project
+ fork this project
+ use file [init_db.sql](src/main/resources/resources/init_db.sql) for create a schema and tables
+ change parameters in ConnectionUtil
+ configure Tomcat
+ just run this 
