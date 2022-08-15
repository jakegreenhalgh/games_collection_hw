What is responsible for defining the routes of the games resource?

create_router

What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?

the server retrieves the games collection from the databse, the client brings it to the frontend

What are the the responsibilities of server.js?

retrieving and managing the games collection onto the database

What are the responsibilities of the gamesRouter?

formats the data into restful routes

What process does the the client (front-end) use to communicate with the server?

uses a fetch request to the server


What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs

An init object that allows you to control a number of different settings:

Which of the games API routes does the front-end application consume (i.e. make requests to)?

the games collection as a json

What are we using the MongoDB Driver for?

Allows the database to connect with node files