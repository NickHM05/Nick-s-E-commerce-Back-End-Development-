# Nick's E-Commerce-Back-End-Development-app

## Description
This application was mase to use Node.js, mySQL2, Sequelize, and Express in order to simulate a backend server for an Ecommerce website or application. When the user uses the API routes they can GET all the info from a table or even a single item of their choice, create a new item using the POST method, update an item with the PUT methoid, or DELETE an item if they choose to. The table has the inventory that is organized into products, categories, and tags. The schema has the database . The js files have the tables and the seeds that can put the example data into the table. 
## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Features](#features)
  - [Credits](#credits)
  - [Tests](#tests)
  - [Questions](#questions)

## Installation
Have the git clone of the repository on the user,s local machine. Run npm init and then npm install.  Change the .env with the user's proper mysql credentials. Login using the terminal into mysql and run the schema file using source db/schema.sql. Type in exit. Run "npm run seed" in the terminal if the example data is needed. Run node server.js or npm start in the terminal. Pull up your insomnia app and use http:localhost:3001/api. Use the GET, POST, PUT, and DELETE methods where the user chooses to. 

## Usage
Using GET routes: return all categories, all products, and all tags. For example, use GET and localhost:3001/api/categories, sub in tags, or even products after api instead. Single use of the GET route return would be to run after api/ either a single category (api/category/1), tag, or a product just similar to the example before. Using POST: Switch BODY to JSON and write in a "category_name", "product_name", or a "tag_name". In the POST top section write to your chooisng of either localhost:3001/api/categories, products or even tags. Using PUT: its similar to POST but you are updating the category, product, or the tag to something different using the id(localhost:3001/categories/6) and writing in the respective category, product or tag in the JSON to what it should be changed to. Using DELETE: choose the category, product, or tag you wish to be deleted.  WARNING: DELETE single items, not whole categories section. (localhost:3001/categories/6 for example.) not (localhost:3001/categories).

- ![Screenshot of the VS Code running file](./Screenshot%20(252).png)
- ![Screenshot of the Insomnia server running file](./Screenshot%20(253).png)

## License 
  This application is licensed under [MIT](https://opensource.org/licenses/MIT) license. Click the link for license rights and limitations.
## Badges
MIT [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Features
GET, POST, PUT, and DELETE options can be used in the server to organize the inventory of your eccomerce website. 

## Credits
Nicholas Mamberger (author). Alexis San Javier (tutor) no github i know of. Ramon Sanchez (tutor) no github i know of. 
Here is the github repo: https://github.com/NickHM05/Nick-s-E-commerce-Back-End-Development-

## Tests
More so listed in the usage section on what you can do with it but there is a db/schema with the server.

## Questions
[Link to my Github Profile](https://github.com/NickHM05

For any additional questions, you can email me at:

nhmamberger@gmail.com
