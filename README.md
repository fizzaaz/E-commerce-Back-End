<h1 align="center">Object-Relational Mapping (ORM): E-Commerce Back End 👋</h1>
  
<p align="center">
    <img src="https://img.shields.io/github/repo-size/jpd61/e-commerce-backend" />
    <img src="https://img.shields.io/github/languages/top/jpd61/e-commerce-backend"  />
    <img src="https://img.shields.io/github/issues/jpd61/e-commerce-backend" />
    <img src="https://img.shields.io/github/last-commit/jpd61/e-commerce-backend" >
    <a href="https://github.com/jpd61"><img src="https://img.shields.io/github/followers/jpd61?style=social" target="_blank" /></a>
    <a href="https://twitter.com/jpdewoody">
        <img alt="Twitter: jpdewoody" src="https://img.shields.io/twitter/follow/jpdewoody.svg?style=social" target="_blank" />
    </a>
</p>
  
<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/express-orange" />
    <img src="https://img.shields.io/badge/Sequelize-blue"  />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
    <img src="https://img.shields.io/badge/dotenv-green" />
</p>
   
<h4>Designed and coded by <a href="https://github.com/fizzaaz">FIZZA ZAIDI</a></h4>

## Description

🔍 A mysql database and application backend for an e-commerce site. This application used Express.js API and Sequelize to interact with a MySQL database. This application displays creation of database using mySQL with models and associations. Then demonstrates the API Routes to perform RESTful CRUD operations displayed in my walk through videos.

✋ [GitHub Repository](https://github.com/fizzaaz/E-commerce-Back-End)

💻 Below is the gif showing the functionality of the application:

### 🎥 Schema and Seed the Database
![DB Setup and Start](./assets/demo/db.gif)

### 🎥 GET ALL ROUTES

![GET All](./assets/demo/getAll.gif)

### 🎥 GET SPECIFIC ROUTE

![GET All by ID](./assets/demo/getByID.gif)

### 🎥 POST PUT DELETE Categories

![POST PUT DELETE Categories](./assets/demo/categoryCRUD.gif)

### 🎥 POST PUT DELETE Products 

![POST PUT DELETE Products](./assets/demo/productCRUD.gif)

### 🎥 POST PUT DELETE Tags 

![POST PUT DELETE Tags](./assets/demo/tagCRUD.gif)


## ✋User Requirements
  
AS A manager at an internet retail company. The user wants a back end for my e-commerce website that uses the latest technologies SO THAT the user's company can compete with other e-commerce companies.
  

## ✋Project Requirements
  
* WHEN the user add my database name, MySQL username, and MySQL password to an environment variable file THEN the user am able to connect to a database using Sequelize.
* WHEN the user enter schema and seed commands THEN a development database is created and is seeded with test data.
* WHEN the user enter the command to invoke the application THEN my server is started and the Sequelize models are synced to the MySQL database.
* WHEN the user open API GET routes in Insomnia for categories, products, or tags THEN the data for each of these routes is displayed in a formatted JSON.
* WHEN the user test API POST, PUT, and DELETE routes in Insomnia THEN the user am able to successfully create, update, and delete data in my database.


## Table of Contents
- [Description](#description)
- [User Requirements](#user-requirements)
- [Project Requirements](#project-requirements)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contribution](#contribution)
- [Questions](#questions)

## 💾Installation

`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## 💻Usage
  
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter PW when promted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`


## ✏️Testing

No testing is currently set up

## 👪Contribution

  Email me 

## Questions

 If you have any queries feel free to contact me at ✉️ fizz.zehra14@gmail.com.
 You can also reach me out through my Github profile at  👋[fizzaaz](https://github.com/fizzaaz/).
