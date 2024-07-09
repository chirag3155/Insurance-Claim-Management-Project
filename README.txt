Technologies Used in Insurance/Claim Management System
The key technologies for developing Insurance claim management system, include Spring Boot, React JS, MySQL, Maven, Bootstrap, and Java.
1. Java - Spring Boot Microservices
For the Backend Development of the project Insurance Management System, we have used Spring Boot Microservices and I have developed the Project using Spring Boot 3.0 and Spring Security 6.


2. React JS
React Js is a popular Javascript Library, We have used React Js for development projects frontend.
3. MySQL
MySQL is a widely used relational database management system, for storing our Insurance Claim Management application data we have used the MySQL server.
4. Maven
To simplify the project and the dependency management, we have used the Maven build tool.
5. BootStrap
For Styling the front end of the project we have used BootStrap which is a popular CSS framework for developing a responsive user interface.


Software Used
1. IntelliJ IDEA
For developing our backend, Insurance Claim Management System project using Spring Boot, we have used IntelliJ IDEA. But yes, we can use other IDEs like STS (Spring Tool Suite), Eclipse, etc.
2. VS Code (Visual Studio Code)
For developing our frontend, Claim management system project using React JS, we have used VS Code (Visual Studio Code).
3. MySQL Workbench
For efficient querying and manipulation of our application information, we have used MySQL Workbench. 


User Modules in Insurance Management System
The project basically has three user modules:


1) ADMINISTRATOR MODULE
2) SURVEYOR MODULE
3) CUSTOMER MODULE
Functional Modules
1) User Authentication Module: 
User Authentication and Authorization with Spring Boot and React. The registration and Login system has been added so that only authenticated users (Admin, Surveyor or Customer) can perform their functionalities.                                        
2) Policy Module: 
Add Policy, Add Coverage Details, Delete Coverage Detail, Delete Policy.
3) Policy Application Module: 
Apply Policy, Update Policy Application, Approve or Reject Customer Policy Application
4) Surveyor Module: 
Register Surveyor, View Surveyors, Delete Surveyor.
5) Claim Module: 
Apply Insurance Claim, View all claims, View Customer Claims, Assign Surveyor for Claim, Update Claim status, Accept or Reject Claim, etc.




OVERVIEW



The Insurance Management System or Insurance Claim Management System Project using Spring Boot & React Js ensures a seamless experience for all involved. As an administrator, you can easily add multiple Policies in the system by adding the policy details like name, premium amount and the coverage details. After adding the Policies, all the policies will be visible in the home page of the website. And Customers can view all policies details and from there they can apply for the policies.
Once Customers apply for any policies, Admin will be able to the see policy applications in his dashboard and from here Admin can accept or reject the application. Here, customer can only apply for the policy application after the login, so from the home page itself customer can register and login themself.
The Admin will also register the Surveyors in the system, so that they can survey the accidents for the customer claims to verify each and everything to approve or reject for the customer insurance claim.
So now let's suppose customer meets any accident or anything, then customer can raise the claim for their Insurance by entering the Claim Amount. Once Customer raise for the Insurance Claim, Admin will be able to see in the dashboard that Customer has raise for the Claim, so from here Admin will assign one of the Surveyor to survey by going to the location and verify each and everything.
Once Surveyor is assigned for the Claim, after surveyor login he will be able to see the Customer Claim and from here Surveyor can approve or reject the Customer claim. If surveyor approves the customer claim then he have to assign the amount for the customer claim.
Once Surveyor approves the customer claim and assigns the amount to the customer, then customer will be able to see the surveyor given amount after the login, from here customer can Accept the amount given by surveyor or he can Withdraw the Insurance Claim.
Project Structure of Insurance Management System Project
BACKEND:
For the backend development, we have employed Spring Boot Microservices. Hence, we have constructed a total of 5 microservices for the Insurance claim management System Project.
Claim Management System Spring Boot Microservices:
1) API Gateway Service
An API Gateway is a component that acts as a single entry point for client applications to interact with various microservices within the system.
2) Service Registry Service
A Service Registry is a component that facilitates service discovery and allows microservices to locate and communicate with each other dynamically.
3) User Service
The User Service will handle all the User-related Operations like user register, login, etc.
4) Policy Service
The Policy microservice will handle Insurance policy and policy application-related operations.
5) Claim Service
The Claim microservice will handle policy claim-related operations.


FRONTEND:
Frontend of the Insurance Management System is developed using React Js. 


DATABASE:
For the Database, we have used MySQL Server for storing the data.


THE PROJECT FLOW





1) At first, our all microservices will be registered to the SERVICE REGISTRY.


2) From the above picture, we can see firstly our request will flow from Frontend to the Backend.


3) In the Backend, Firstly request will go to the common server which is API GATEWAY.


4) From API GATEWAY, based on the request from the front end, it will route to the required SERVICE i.e. Train Service, Booking Service, Location Service & User Service.


5) And now, each microservices can communicate between them, to form the required response which we'll send to the front end.


6) Each microservices will be connected to a database  MySQL.

