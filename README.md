# e-commerce
challenge #13

## Task
- AS A manager at an internet retail company I WANT a back end for my e-commerce website that uses the latest technologies SO THAT my company can compete with other e-commerce companies.
- GIVEN a functional Express.js API WHEN I add my database name, MySQL username, and MySQL password to an environment variable file THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia THEN I am able to successfully create, update, and delete data in my database

## Process
- Import sequelize connection, sync connection before connecting to server, utilize sequelize to connect to SQL database
- Create routes for Product, Category, and Tags
    - GET all, GET by id
    - POST
    - PUT
    - DELETE
- Build the associations between tables
- Use insomnia to test each route

## What I Learned
- I learned how to build each type of route using RESTful properties
- How to add associations between tables
- Solidified my knowledge of sequelize, and how to utilize it to connect the database to node server
- I learned how to build project folders in insomnia to organize all routes

## View the video demo here: https://drive.google.com/file/d/1065uKsJjQbvKtOsYYLhjzoASKx-dksFy/view

## Screenshots

### Insomia Route Structure
![Screenshot 2023-05-23 at 1 04 17 PM](https://github.com/bigcat86/e-commerce/assets/122062578/738d6d40-ae4d-41ce-8b05-dc5485179880)
