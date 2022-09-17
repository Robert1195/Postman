
# Trello.com

API tests for the Trello.com website using the Postman tool


## List of tests

To see full overview of the performed tests see attached html report: 
Trello.com_postman_test_report.html



## Installation :
  - To run Newman, ensure that you have Node.js >= v10. Install Node.js.
The easiest way to install Newman is using NPM. If you have Node.js installed, it is most likely that you have NPM installed as well.

    $ npm install -g newman
    
This installs Newman globally on your system allowing you to run it from anywhere. If you want to install it locally. Just remove the -g flag.

## Running Tests
    1. Run cmd command
    2. Go to the folder where you downloaded the Trello.com_collection and Trello.com_environment files

To run tests, run the following command

```bash
  newman run Trello.com_collection.json -e Trello.com_environment.json
```

# Simple API Book

API tests for the Simple API Book using the Postman tool

## List of tests

To see full overview of the performed tests see attached html report: 
Simple API Book_postman_test_report.html

## Running Tests
    1. Run cmd command
    2. Go to the folder where you downloaded the file Simple_API_Book_collection.json

To run tests, run the following command

```bash
  newman run Simple_API_Book_collection
               or
  newman run https://www.getpostman.com/collections/604b9a45ef01a3746ee7
```

