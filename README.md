# E-Commerce Backend
User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies.

---
## **Acceptance Criteria**

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## **Installation**

You will need to run the folllwing commands

"mysql -u root -p" you will be asked to enter your password

source db/schema.sql

quit

npm run seed

npm start

## **Walkthrough Video**




https://user-images.githubusercontent.com/94266004/177710113-3c1e0d84-3283-40e4-863f-f44e168d1347.mp4


