# E-commerce Backend
## Description
This application is the backend portion of an E-commerce website using RESTful API routes to make requests. Express.js is used to create routes.
MySQL is used to create the e-commerce database while sequelize uses Models to create the Product, Category, Product Tag and Tag tables. With this
backend we are able to use GET, POST, PUT, and DELETE methods for each model. 

## How to Install
* You will need to have MySQL installed and have MySQL credentials to use this app.
* Clone this repository onto your local machine. [How to Clone a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).
* In your terminal cd into the root folder of the e-commerce-backend.
* While in the root folder, you must first run `npm install` to load all the dependancies needed for the app run.
* Next you should create a .env file in the root folder and edit it to contain your MySQL credentials. Your file should contain the following:

<img width="325" alt="Screen Shot 2021-05-22 at 6 11 44 PM" src="https://user-images.githubusercontent.com/77217156/119242137-9868f280-bb29-11eb-9bb4-e4f12eb49edb.png">

* Make sure DB_NAME='ecommerce_db'. Save the file.
* In your terminal while still in the root folder of e-commerce-backend run `mysql -u root -p` then enter your MySQL password when prompted.
* Now in the MySQL shell run `source db/schema.sql` to create the ecommerce_db database.
* Type `quit;` to exit the MySQL shell.
* To create the tables and seed the database run `npm run seed`. 

## How to Use
* To start the server run `npm start` or `node server.js`.
