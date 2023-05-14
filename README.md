# E-commerce Backend
[![Application Workflow](./images/get-categories.jpg)](https://drive.google.com/file/d/17oqUnd35OCWvdrYMy0G_BYAlWZN6cdKL/view) <br>
Click video above for application walkthrough using seeded data!
 
![NodeJS](https://img.shields.io/badge/-NodeJS-339933?logo=node.js&logoColor=white&style=flat)
![Express](https://img.shields.io/badge/-Express-000000?logo=Express&logoColor=white&style=flat)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=MySQL&logoColor=white&style=flat)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?logo=Sequelize&logoColor=white&style=flat)
![Insomnia](https://img.shields.io/badge/Insomnia-4000BF?logo=Insomnia&logoColor=white&style=flat)
![Nodemon](https://img.shields.io/badge/Nodemon-76D04B?logo=Nodemon&logoColor=white&style=flat)

## Table of Contents 
* [Description](#Description) 

* [Installation](#Installation) 

* [Usage](#Usage) 

* [License](#License) 

* [Contributing](#Contributing) 

* [Testing](#Testing) 

* [Questions](#Questions) 

* [Screenshots](#Screenshots) 

### Description
A backend application intended to be paired with an e-commerce front end. The application uses Sequelize, a modern Object Relational Mapper used with MySQL database. Insomnia was used to ensure functionality of routes and will be shown in the application walkthrough video. 

### Installation
1. Project is setup to use an .env file to protect sensitive database usernames and passwords. Using the supplied .env.EXAMPLE file in root directory, rename file to be that of .env (removing .EXAMPLE) and fill in required variables of DB_USER and DB_PASSWORD with your own mySQL username and password.
2. Run mySQL in root folder. source db/schema.sql to setup working database. 
3. `npm install` into root directory, to install required application dependencies. 
    - [optional] `npm run seed` to seed database with pre-supplied data.
4. `npm start` to start application.

### Usage
Available npm scripts: 
- test
- start
- watch
- seed

Available /api routes:
- /categories
- /products
- /tags

Live application can be found <a href="#">here</a>

### License
Further information regarding this specific license can be found via: https://opensource.org/license/mit/. <br>
![License Badge](https://img.shields.io/badge/License-MIT-yellow.svg) 

### Contributing
Open <a href="https://github.com/MisterBham/ecom-backend/issues">Issues</a> on the Github repo!

### Testing
npm test

### Questions
Should you have any further questions, please reach the developer at: misterbham.dev@gmail.com. <br>
GitHub: <a href="https://github.com/MisterBham">MisterBham</a>

### Screenshots
<img src="./images/get-categories.jpg" width=85% height=85%> <br>
<img src="./images/post-products.jpg" width=85% height=85%> <br>
<img src="./images/put-tags.jpg" width=85% height=85%> <br>
<img src="./images/del-categories.jpg" width=85% height=85%> <br>
