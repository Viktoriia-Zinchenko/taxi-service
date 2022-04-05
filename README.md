
![Logo](https://allroader.ru/wp-content/uploads/2017/03/taxi.png)

**Taxi Service** is a simple web application that simulates the work of a taxi service.

The project is implemented in Java with SOLID principles & Dependency Injection,
has a 3-tier architecture.
***
##Functionality of Taxi Service 🚕
___
* Register
* Login / logout

The following steps are available only after successful authentication
* Display All Drivers
* Display All Cars
* Display All Current Cars
* Display All Manufacturers
* Create new Driver
* Create new Car
* Create new Manufacturer
* Add Driver to Car
***
##Structure: 3-tier architecture 🚕
___
* DAO - Data Tier
* Service - Business Tier
* Controllers - Presentation Tier
***
##Technologies 🚕
___
* Java 11
* Tomcat 9.0.60
* Maven
* MySQL
* JDBC
* Servlet
* JSTL
* JSP
* HTML, CSS
***
##How to run a project 🚕
___
You need to install Ultimate IntelliJ IDEA, MySQL, TomСat webserver (version 9).
1. Configure TomСat.
2. Copy, paste and run the script from this file ```src/main/resources/init_db.sql``` into MySQL.
3.In order to connect to the database it is necessary to add current data in the following fields
URL, USERNAME, PASSWORD, JDBC_DRIVER in this file ```src/main/java/taxi/util/ConnectionUtil.java```.
4. Add configurations in TomCat Server.
5. Start the project.
