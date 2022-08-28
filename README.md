# Project: 

SuperHero Application

# Description: 

This is a NodeJs application and it provides few of the API's to get the SuperHero details and     also updating the details of superhero power stats.

# Domain: 

http://localhost:4201 (Local Running)

# Installation and Run the project: 
        A) NPM install  (To install node modules)
        B) node index.js (To run the project)

# Project Usage:
        After running the project, Need to make a API calls and it has to connect with MySQL database. Then by using POSTMAN tool we can test the API's. 

# Files Usage:
        1) index.js (It has required packages and execution starts from this file).
        2) routing.js (It has all the API's).
        3) modals.js (It has a Application Logic and query's to execute )
        4) db.js (It creates the connection between backend and database).
        5) db.config.js (It has credentials of the database and database name).

# API's:
        1) /superhero/:name (GET Method)
        2) /editsuperhero (POST Method)

        Here I am giviing some sample examples of API's
        1) http://localhost:4201/superhero/oracle (GET)
        2) http://localhost:4201/editsuperhero (POST)
