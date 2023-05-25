# Ecommerce-Backend

## Description

A back-end for an ecommerce website using the latest technologies to get, post, and delete products, categories, and tags in a database.

## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage] (#usage)
- [Technologies](#Technologies)
- [Questions](#Questions)

## Installation

To get started clone this repository using

git clone https://github.com/Breeannr180/ecommerce-backend
Both Node.js and MySQL must be installed on your computer.

Install dependencies

npm init --y
npm install express sequelize mysql2
Open up MySQL shell and input

source db/schema.sql
and

use ecommerce_db
Then quit MySQL shell and input the following in your terminal

npm run seed
to start running application simply input

node server.js
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## Usage

We’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database. This application won’t be deployed. See images below showcasing application running in insomnia.
Watch video here https://watch.screencastify.com/v/wGK0M93MVhj0y0onmxqc


![alt text](/Images/Get%20Categories.png)
[!alt text](/Images/Get%20Products.png)
[!alt text](/Images/Get%20tags.png)
[!alt text](/Images/Post%20categories.png)
[!alt text](/Images/Put%20indv%20category.png)
[!alt text](/Images/Delete%20indv%20category.png)

## Technologies

- Javascript
- Node.js
- Sequelize
- MySQL2
- Express
- Dotenv

## Questions

For questions about this repository, please contact me.












