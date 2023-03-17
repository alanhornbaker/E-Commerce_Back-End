# E-Commerce Back End

## Table of Contents

1.[Description and Purpose](#description)

2.[User Story](#userStory)

3.[Acceptance Criteria](#acceptanceCriteria)

4.[Wireframes and Mock-Ups](#mockups)

5.[Database Models and Associations](#databaseModels)

6.[Installation](#installation)

7.[Usage](#usage)

8.[Contribution](#contribution)

9.[License](#license)

10.[Questions](#questions)

11.[Bonus](#Bonus)

## Description

The project is a basic setup for handling financial exchanges online using CRUD methods, models, etc.

The project is intended to allow clients to securely monetize their online presence and use a website to produce income.

## User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria

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

## Wireframes and Mock-Ups

<!-- ![ Table Tree Image](./assets/images/table_tree.png "Tables Example") -->

## Database Models and Association

Model Associations:
Product belongs to Category, as a category can have multiple products but a product can only belong to one category.
Category has many Product models.
Product belongs to many Tag models. Using the ProductTag through model, allow products to have multiple tags and tags to have many products.
Tag belongs to many Product models.

## Installation

You can install this application by forking the repository from github.com/alanhornbaker/E-Commerce_Back-End and opening the repository in your text editor. You will also want the LTS version of NPM so the node works.

## Usage

Functions that you will use to to use the application once you have installed it:
Add Functions

## Contribution

You can contribute to this application by opening a pull request at github.com/alanhornbaker/E-Commerce_Back-End. Currently there are no rules or standards for contribution.

## License

The Alan License

## Questions

Known erros and other issues can be raised to the repository on github at github.com/alanhornbaker/E-Commerce_Back-End , or can be sent to my github profile at github.com/alanhornbaker. As last resort, questions can be emailed to me directly at alanhornbaker@gmail.com.

## Bonus
