# Taxi Service

![Alt text](readme.images/taxi-logo.png?raw=true "Database")

This is a simple Web application that supports authentication, registration, other CRUD operations and simulates a work of a simple taxi service.
It provides following functionality:
- display all Drivers
- display all Cars
- display all current Cars
- display all Manufacturers
- create new Driver
- create new Car
- create new Manufacturer
- add driver to car
---
## 3-layer architecture
1. DAO - Data access layer
2. Service - Application layer
3. Controllers - Presentation layer
---
## Technologies
- Java 11
- Tomcat - version 9.0.59
- MySQL
- JDBC
- Servlet
- JSTL
- JSP
- HTML, CSS
---
## How to run a project
To correctly use this service you have to install MySQL and Apache Tomcat version 9.
1. Configure Apache Tomcat for your IDE.
2. Use ```/resources/init_db.sql``` for creating a Schema and tables.
3. Configure ```/util/ConnectionUtil.java``` with your URL, USERNAME, PASSWORD, JDBC_DRIVER.
4. In the ```src/main/resources/log4j2.xml``` at line ```File name = "File" fileName = "logs\app.log"``` you need to change ```logs\app.log``` with absolute path to ```.log``` file
5. Configure the tomcat library path in the startup settings.
6. Go ahead and use it!