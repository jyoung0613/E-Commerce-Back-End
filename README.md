# Object-Relational Mapping (ORM): E-Commerce Back End

[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description 
Refactor starter-code to build the back-end for an e-commerce site, including configuring a working Express.js API using Sequelize to interact with a MySQL database. 


## Technologies Used
- JavaScript
- Node.js
- [NPM Express.js Package](https://www.npmjs.com/package/express)
- [NPM MySQL2 Package](https://www.npmjs.com/package/mysql2)
- [NPM Sequelize Package](https://www.npmjs.com/package/sequelize)
- [NPM DotENV Package](https://www.npmjs.com/package/dotenv)
- [NPM Router Package](https://www.npmjs.com/package/router)
- [NPM Nodemon Package](https://www.npmjs.com/package/nodemon)

## Installation & Usage

To use this app, you will need a MySQL account

To test the API routes in this app, you may wish to have an Insomnia account and to have the app installed on your machine. Documentation and instructions are available [here.](https://support.insomnia.rest/article/156-installation1) 

STEP 1

    1.1 Clone this E-Commerce-Back-End repo to your machine.

STEP 2

From Visual Studio Code or the code editor of your choice:

    2.1 Open the repo.  
    2.2 Create a .env file and make sure its on your .gitignore file
    2.3 Add your own MySQL DB Name Username and Password to the .env file.
    2.4 Save your changes.
    2.5 login to your sql account (mysql -u root -p)
    2.6 Run source db/schema.sql
    2.7 log out of mysql by typing quit in the command line

STEP 3

From your terminal, run:

    3.1 npm i
    3.2 npm run watch

STEP 4: API ROUTE TESTS

From your terminal, run:

    4.1 npm run seed

From Insomnia:

    4.2 Run tests for each API route (GET all, GET by id, PUSH, PUT, and DELETE) route using http://localhost:3001/api/ for each model (Category, Product, and Tag), with pathing listed as categories, products, and tags (i.e. GET http://localhost:3001/api/categories/).

## Demo 

Link: [E-Commerce Back End demo](https://drive.google.com/file/d/1OAcuVOr46UUz8rlrfwPnDPog3smaat-_/view)

## Contributing
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

## License
This project is licensed under the terms of the following license: **MIT**.

## Questions
GitHub: [jyoung0613](https://github.com/jyoung0613).  

For inquiries, please contact jwyoung0613@gmail.com.

