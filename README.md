# Jokes API
## Overview
The Jokes API is a simple RESTful API that allows you to manage a collection of jokes. You can retrieve random jokes, search for jokes by ID or type, add new jokes, update existing ones, and delete jokes.

## Detailed documentation
https://documenter.getpostman.com/view/6048123/2s9XxsTv8Y#5cfcfd0f-2f73-4e73-b5a0-e46dcba3eec1

# API Endpoints
## 1. Get a Random Joke
URL: /random
Method: GET
Description: Retrieves a random joke from the collection.
## 2. Get a Specific Joke
URL: /jokes/:id
Method: GET
Description: Retrieves a specific joke by its ID.
## 3. Get Jokes by Type
URL: /filter
Method: GET
Description: Retrieves jokes filtered by type.
Query Parameters:
type: The type of jokes to filter by.
## 4. Add a New Joke
URL: /jokes
Method: POST
Description: Adds a new joke to the collection.
Body Parameters:
text: The text of the joke.
type: The type of the joke.
## 5. Update a Joke
URL: /jokes/:id
Method: PUT
Description: Updates an existing joke by its ID.
Body Parameters:
text: The updated text of the joke.
type: The updated type of the joke.
## 6. Partially Update a Joke
URL: /jokes/:id
Method: PATCH
Description: Partially updates an existing joke by its ID.
Body Parameters (Optional):
text: The updated text of the joke.
type: The updated type of the joke.
## 7. Delete a Specific Joke
URL: /jokes/:id
Method: DELETE
Description: Deletes a specific joke by its ID.
## 8. Delete All Jokes
URL: /all
Method: DELETE
Description: Deletes all jokes from the collection.
Query Parameters:
key: The master key to authorize this action.

## Example Jokes

![image](https://github.com/Joelft94/JokeAPI/assets/107083554/6cf603d3-8d56-4b95-87e8-239431d86bd9)



# Setup
To run the server locally:

Clone the repository.

Install dependencies using npm install.

Start the server using running node index.js

The server will be running at http://localhost:3000.


