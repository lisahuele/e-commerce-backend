# E-Commerce Backend
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
A mysql database and application backend for an e-commerce site. Built using MySQL2, Express, Sequelize and dotenv.

## Contents
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Built With](#built-with)
- [Questions](#questions)
- [Credits](#credits)

## Installation
To install all the dependencies, use the command below

```
npm  install express mysql2 sequelize dotenv
```

## Usage
To use this application, clone the repository to your local machine:
```
git clone https://github.com/lisahuele/e-commerce-backend.git
```

Then, ensure you have installed the dependencies with the command.

When you are ready to run the application, from the root directory, type the command:

```
mysql -u root -p
```

Enter PW when prompted

`source db/schema.sql`
`quit`
`npm run seed`
`npm start`

## Demo

### Setup and Start
![DB setup and start](./demo/01-startApplication.gif)

### GET all
![GET all](./demo/02-GET-routes.gif)

### GET by ID
![GET by ID](./demo/03-GET-routes-single.gif)

### POST, PUT, DELETE Categories
![POST, GET, DELETE Categories](./demo/04-categoryRoutes.gif)

### POST, PUT, DELETE Products
![POST, GET, DELETE Products](./demo/05-productRoutes.gif)

### POST, PUT, DELETE Tags
![POST, GET, DELETE Tags](./demo/06-tagRoutes.gif)

## Built With
- Express.js
- MYSQL2
- Sequelize
- dotenv

## Questions
If you have any questions about the repo, please contact me via email at lisahuele@gmail.com. You can find more of my work on my GitHub, [lisahuele](https://github.com/lisahuele).

## Credits
Created by Lisa Le.
