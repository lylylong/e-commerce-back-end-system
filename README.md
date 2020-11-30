# E-commerce Back-end System

## Description

This E-commerce Back-end System is a very useful tool for internet retail companies. It's designed for the manager who wants a back end for his/her e-commerce website that uses the latest technologies. So that company can compete with other e-commerce companies.

Let's look into this back-end system, this is a functional Express.js API:

1. First, the user needs to add his/her database name, MySQL username, and MySQL password to an environment variable file, then the user is able to connect to a database using Sequelize. The user needs to coninue to enter schema and seed commands, then a development database is created and is seeded with test data.

2. Second, the user continues to enter the command to invoke the application, so the server will be started and the Sequelize models are synced to the MySQL database.

3. Thrid, it's time to open API GET routes in Insomnia Core. After inputing the routes for categories, products, and tags, the user can:
   - Test API GET, POST, PUT, and DELETE routes in Insomnia Core;
   - Be able to successfully read, create, update, and delete data in the database;
   - The data for each of these routes are displayed in a formatted JSON.

## Process Video

[![Video](https://user-images.githubusercontent.com/70302749/100561810-e17d6f80-3287-11eb-91de-ac3f666743af.png)](https://drive.google.com/file/d/18t08EYYUbg3e7HKQlQWUkc0SmA1rZbRh/view)
https://drive.google.com/file/d/18t08EYYUbg3e7HKQlQWUkc0SmA1rZbRh/view

## Installation

To install the dependencies, run following command:

- npm i

- Update your password:
  - create .env at the root
  - add the following and don't forget to input your password:
    - DB_NAME='ecommerce_db'
    - DB_USER='root'
    - DB_PW='yourPasswordGoesHere'

## Testing

- mysql -u root -p
  - source db/schema.sql
  - show databases;
  - use ecommerce_db;
  - quit
- npm run seed
- npm start
- Insomnia Core

## Built With

- JavaScript
- Node.js
- MySQL
- Sequelize
- Dotenv

## Contributor

- Xandromus
- lylylong
