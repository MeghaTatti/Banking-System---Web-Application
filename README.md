# Banking-System---Web-Application

### Project Description:
This Project is an online banking website application with backend database which operates on banker, customer and administrator entities.
The Banker can add, update or delete a Customer, can approve credit/debit money for customer, can approve money transfer to another merchant.
The Customer will be allowed to perform basic actions like creating an account, update information, internal fund transfer, money transfer to another merchant and can register a complaint to administrator.
Administrator is a secondary role for the system, takes care of the functionality problem registered by other two users.

### The following technologies were used to build the project:
Frontend: HTML, CSS, Bootstrap, JavaScript, Ajax.	

Backend: JSP, Java Beans, Servlets, MySQL, MongoDB, Python (Twitter API), MongoDB Server: Tomcat Apache Server.

______________________________________________________________________________

## BANKING SYSTEM (Chicago Bank) User Document:
______________________________________________________________________________

How many total lines of code written (Java and Javascript source code) ?
	
	Total lines of code written:
		1.) Java       : 3337
		2.) JavaScript : 20412


What features are implemented in the project?

a.) Servlet Based Web Application                                                                                                       
b.) Usage of plain text file to fetch data                                                                                              
C.) Implementation of CRUD operations in SQL database                                                                                   
d.) Implementation of NoSQL database (MongoDB)                                                                                           
e.) Trending & Data Analytics feature                                                                                                   
f.) All new code added for MySQL shall be placed in a class called MySQLDataStoreUtilities.java                                         
g.) All new code added for MongoDB shall be placed in a class called MongoDBDataStoreUtilities.java                                     
h.) Generation of transaction reports                                                                                                   
i.) Search Auto-Completion feature                                                                                                      
j.) Data Exploration feature                                                                                                             
k.) Implementation of Python and Twitter API                                                                                             
l.) Recommendation feature                                                                                                              
m.) Implentation of JS, JQuery, JSP, Java, Python, SQL, NoSQL, Tomcat, BootStrap, AJAX, HTML, CSS, Servlets                             
n.) Carousel feature  
	
3.)Instructions on show how to deploy and run the bank project:

	1. Start tomcat server
	2. Copy "BankingSystem" Project folder to the tomcat webapp folder.
	3. Start the MySQL database with database name as bns. The username is root and password is root to connect to the MySQL DB.
	4. Start the MongoDB server with mongo.exe and mongod.exe with database name as complaint and collection name as complaintStored.
	5. In order to start the application open the browser and type http://localhost/BankingSystem1/ or http://localhost/BankingSystem1/Home.


Note:

To compile Java files, use this command:
javac *.java

If in case it doesn't work then, use the following cmd:

javac -cp "C:/tommy/tomcat-7.0.34-preconfigured/apache-tomcat-7.0.34/lib/mongo-java-driver-3.2.2.jar;C:\tommy\tomcat-7.0.34-preconfigured\apache-tomcat-7.0.34\lib\servlet-api.jar;C:\tommy\tomcat-7.0.34-preconfigured\apache-tomcat-7.0.34\lib\mysql-connector-java-5.1.23-bin.jar;C:\tommy\tomcat-7.0.34-preconfigured\apache-tomcat-7.0.34\lib\gson-2.6.2.jar;" *.java

### Role Information

There are three ROLES:
a. Customer
b. Banker
c. Administrator


#### a.) Customer:
For testing purposes you can give as:	

User Name: Adi	

Password:  yaji

Customer can,
1.> Funds Transfer Within Bank 
2.> Funds Transfer to Other Bank 
3.> Register a Complaint 
4.> View Complaints' status 
5.> View Transactions 
6.> Change User Credentials 
5.> Log out

#### b.) Banker:

User Name: banker

Password:  urvi																

Banker can,
1.> Create New customer 
2.> Update a Customer 
3.> Delete a Customer 
4.> Register a Complaint 
5.> View Complaints' status 
6.> Add Customer Transactions 
7.> View all customer Transactions 
8.> Money Transfer Request 
9.> Change User Credentials 
10> Log out

##### c.) Administrator:
User Name: admin

Password:  admin

Admin can,
1.> View all the complaints registered.
2.> Able to change the status of the complaints.

This project was made in collbration with Urvi Sheth and Aditya Yaji as the submission for the subject Enterprise Web Application Here in folder attached code for the system and a dummy sql file for testing purposes.





