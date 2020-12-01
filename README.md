# ProjectManagementPortal

This is a full stack web portal developed for NITK Web Club's Winter of Code. 

## Technologies Used: 
Nodejs,Expressjs,Reactjs,SQL,Sequelize ORM,GraphQL,CORS,Redis


## Description:
 
 This portal was developed to cater to the needs of students and mentors involved with NITK Winter of Code. Later this was modified a bit(mainly frontend) and deployed to form the main web portal for the program.  
 The frontend was rendered using Reactjs and the backend consists of a typical Nodejs web app.  
 We have used GraphQL to query the data from the backend and returning it to the client.  
 The database service used is MySQL and we have used Sequelize ORM to query the data from the database to the backend.. 
 
## Setup instructions:

1. Clone this repository. 
2. Install MySQL if you don't have it already. Follow any of these to install MySQL.  
3. Import the SQL dump: mysql -u <USERNAME> -p <DB NAME> < <dump file path>. 
4. Install Redis and start the service. Follow these instructions.  
5. Make sure you have node and npm installed. Follow this to install them.  
6. Create a .env file in the server folder. Copy the contents of .env.example and paste it in .env, and fill in the appropriate values.  
7. Run npm install in the server and client folders to install the dependencies.  
8. Run the server and client both in different terminal sessions with npm start. The client should have started on localhost:3000 and the server on localhost:4000, which opens an interactive GraphQL Playground in the browser.  

Temporarily hosted at https://woc-portal-demo.herokuapp.com/.   
The main web portal is hosted at : https://woc-nitk.github.io/#/

