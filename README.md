# API-Postman--Testing--Practice
API Testing practice using Postman, Newman and Swagger

Steps to start:
Download Postman, Node, Newman, etc.

Links for reference: 

Postman installation link: https://postman.com/downloads

Node installation link: https://nodejs.org

Download Newman in CMD using following command: npm install -g newman

Application Links Used for testing practice: 

Contact List app: https://thinking-tester-contact-list.herokuapp.com

- URL for login: https://thinking-tester-contact-list.herokuapp.com/users/login

- Postman documentation for Contact List app: https://documenter.getpostman.com/view/4012288/2s8YRiKDbu


Created a Collection named Contact List with 2 folders: 

- Basic Endpoint Tests
  
- Negative Tests


\\\\\\
Command to run the Collection using Newman: 

newman run Contact_List_postman_collection.json -e Contact_List_postman_environment.json --env-var "baseURL=https://thinking-tester-contact-list.herokuapp.com"

\\\\\\


Pet Store API: https://petstore.swagger.io

Poke API: https://pokeapi.co




Postman Docs: https://learning.postman.com/docs/introduction/overview/
