# ExpressJS API Server
*This server will return/update/create data at the described endpoints (URLs) below:*

## GET
##### URL: http://localhost:3000/api/characters
*Hitting this endpoint will load Harry Potter JSON data of 3 characters from local memory.*

## POST
##### URL: http://localhost:3000/api/characters/new
*Hitting this endpoint will add the object with Sirius Black onto the characters array with JSON data (4 item) to local memory.*

## PUT (UPDATE)
##### URL: http://localhost:3000/api/characters/update/:id
##### USE PATH VAR ID -> 5a12327c0f5ae10021650d94
*Hitting this endpoint and using this id will update the 3rd item in the JSON data's name from ***Salazar Slytherin*** to ***Tyler Ivie****

## DELETE
##### URL: http://localhost:3000/api/characters/delete/:id
##### USE PATH VAR ID -> 5a12327c0f5ae10021650d94
*Hitting this endpoint and using this id will delete the 3rd item in the JSON data.*