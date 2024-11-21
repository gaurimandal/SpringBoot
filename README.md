# Fee Manager Application
A Spring Boot application designed to simplify fee management processes, built with Maven and developed in Spring Tool Suite (STS). The project leverages an in-memory H2 database for seamless operation.
# Features
Perform CRUD operations (Create, Read, Update, Delete) on fee records.
Manage fees by academic year and class/standard.
# Installation
Clone the Repository
git clone https://github.com/gaurimandal/SpringBoot.git 

Import the Project
Open STS and navigate to File > Import....
Choose Existing Maven Projects, select the project folder, and click Finish.

Build the Project
Right-click on the project, select Maven > Update Project..., and click OK.

Run the Application
Right-click the project, go to Run As > Spring Boot App.

Access the Application
Open your browser and go to http://localhost:8080.
Access the H2 database console at http://localhost:8080/h2-console.

# Configuration
The application uses an H2 in-memory database by default. Database configurations can be modified in the application.properties file:
spring.datasource.url=jdbc:h2:mem:feeManager  
spring.datasource.driverClassName=org.h2.Driver  
spring.datasource.username=fee  
spring.datasource.password=fee  
