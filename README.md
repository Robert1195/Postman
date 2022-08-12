
# Trello.com

API tests for the Trello.com website using the Postman tool


## List of tests

- Create a Board

    √  Should verify status code

    √  Should verify board name

    √  Should verify length of id

- Get Boards that Member belongs to
  
    √  Should verify status code

    √  Should verify value of the name

- Create a List on a Board
  
    √  Should verify status code

    √  Should verify value of the name

    √  Should verify response id

- GET a list on a board
  
    √  Should verify status code

    √  Should verify closed value

    √  Should verify closed type

- Create a New Card
  
    √  Should verify status code

    √  Should verify idList

    √  Should verify idBoard

- Get Cards on a Board
 
    √  Should verify status code

    √  Should verify idList

    √  Should verify idBoard

    √  Should verify shortLink type

- Update a Card
  
    √  Should verify status code

    √  Should verify idList

    √  Should verify idBoard

    √  Should verify updated name value

    √  Should verify updated desc value

- Delete a Card
  
    √  Should verify status code

- Delete a Board
  
    √  Should verify status code



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


