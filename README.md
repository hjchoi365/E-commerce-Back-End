# E-commerce-Back-End

## Purpose of Application
This application builds the back end for an e-commerce site.

## Description
This application uses Express.js API and configure it to use Sequelize to interact with a MySQL database.Db name, user name and password are saved in .env file using which user can connect to database using sequelize.

## User story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance crieteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

## Links
[GitHub](https://github.com/hjchoi365/E-commerce-Back-End)