# API-Postman--Testing--Practice
API Testing practice using Postman, Newman and Swagger
This repository showcases hands-on API testing using Postman, Newman, and Swagger. It includes test cases for real-world APIs, environment setup, and command-line execution using Newman.


Tools Required:
Download Postman, Node, Newman, etc.


Links for reference: 

Postman installation link: https://postman.com/downloads

Node installation link: https://nodejs.org

Download Newman in CMD using following command: npm install -g newman



Projects Included

Contact List app: https://thinking-tester-contact-list.herokuapp.com

- URL for login: https://thinking-tester-contact-list.herokuapp.com/users/login

- Postman documentation for Contact List app: https://documenter.getpostman.com/view/4012288/2s8YRiKDbu


Collection Structure: 

- Basic Endpoint Tests
  
- Negative Tests

## 🔗 Files
- [Contact_List_postman_collection.json](Contact_List_postman_collection.json)
- [Contact_List_postman_environment.json](Contact_List_postman_environment.json)


\\\\\\
Command to run the Collection using Newman: 

newman run Contact_List_postman_collection.json -e Contact_List_postman_environment.json --env-var "baseURL=https://thinking-tester-contact-list.herokuapp.com"

\\\\\\



Postman Docs: https://learning.postman.com/docs/introduction/overview/




In-Progress:---
Pet Store API: https://petstore.swagger.io

Poke API: https://pokeapi.co




