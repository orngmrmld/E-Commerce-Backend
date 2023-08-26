# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Task

The task is to build the back end for an e-commerce site by modifying starter code. I configured a working Express.js API to use Sequelize to interact with a MySQL database.

Because this application won’t be deployed, I also need to provide a link to a walkthrough video that demonstrates its functionality and all of the acceptance criteria being met. You’ll need to submit a link to the video and add it to the readme of your project.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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
```

## Installation

Clone the github repo and from the terminal, install inquierer and sequilize. You will need to have Node installed.

## Usage

In your terminal, run your mysql server and source the scheme.sql so we can populate the data base. After that, we can run    npm run watch    so we can monitor the database as we populate it or modify it in insomnia. You can also use    npm run start    in order to run the server. Within insomnia, we can populate or modify the sql database as seen in the demo video. 

## Links for Review

 * Video Link: https://drive.google.com/file/d/17hTh2uviYhEOPQbMhL5cDJfpoo4KlaDc/view?usp=sharing
 * Repository Link: https://github.com/orngmrmld/E-Commerce-Backend
 * Github Link: https://github.com/orngmrmld




---
© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
