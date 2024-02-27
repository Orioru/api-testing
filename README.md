# API Testing Project

This project contains Postman API tests for the Books API .

## Installation

To run the API tests, first make sure you have Node.js and npm installed on your system. Then, follow these steps:

1. Navigate to the project directory
2. Install the project dependencies by running the following command: npm install

## Running the Tests with CLI

Once you have installed the dependencies, you can run the API tests using Newman, which is a command-line tool for running Postman collections. Follow these steps to run the tests:

1. Make sure you are in the root directory of the project.

2. Run the following command to execute the API tests: newman run .\Books.postman_collection.json

## Running the Tests and generate report html

1. If you want the reports in html run this command: node .\executeTests.js

The report will be saved as html on the root of the project
