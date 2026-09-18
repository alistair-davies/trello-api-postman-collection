Trello API Postman Collection
This project contains a Postman collection demonstrating practical API testing and workflow automation using the Trello REST API. It includes authenticated requests, request chaining, variable handling, and automated test scripts.

📌 What this collection does
Get all boards — retrieves your boards and stores the first board ID

Create a board — creates a new board with incrementing names

Get a single board — fetches board details

Create lists — creates Todo and Done lists

Create a card — adds a card to the Todo list

Move the card — moves the card to Done

Delete the board — deletes the board and verifies deletion

🔧 Features demonstrated
API authentication

Request chaining

Automated test scripts

JSON validation

Workflow automation

🚀 How to use this collection
Import the JSON file into Postman.

Open the Variables tab inside the collection.

Replace the dummy values for:

trellokey

trellotoken

Run the collection from top to bottom — each request sets variables for the next.

View test results in the Postman Tests tab.

🔒 Security
All sensitive values (API key and token) have been removed and replaced with placeholders.
You must add your own credentials locally to run the collection.

📁 Files included
Trello_API_Collection.json — full Postman collection with variables included
