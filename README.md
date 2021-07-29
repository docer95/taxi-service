#Taxi-service

This project developed for taxi service.
With this application you have opportunity easy control your business.
Program allow created new database in which you add your cars,
create or register new driver and assign a car to the driver.

### Technologies in this project:
* SQL
* HTML
* JSP
* JSTL
* JDBC
* Web
* Servlet
* Apache Tomcat

### Setup
1. Download and install IntelliJ IDEA Ultimate
2. Download and install MySQL
3. Download and install Tomcat
4. Turn this project
5. In this project, open the file that is located at the address taxi-service/src/main/resources/init_db.sql
6. Copy this lines and paste in Workbench for create new database, schema and tables
7. In this project, open the file that is located at the address taxi-service/src/main/java/taxi/util/ConnectionUtil.java
   and change fields (URL - address behind which your database, USERNAME - your login,
   PASSWORD - your password, JDBC_DRIVER - path for JDBC driver)
8. In this project, open the file that is located at the address taxi-service/src/main/resources/log4j2.xml 
   and change path in field "filename" for logger
9. Add Configurations -> add new run configuration... -> Tomcat Server -> Local. 
   After than go to tab "Deployment" -> to push button "fix" -> taxi-service:war exploded.
   After than scroll below, in field "Application context" -> write - "/"
10. Push "Run"
