# Social_Network_API

## Description
This project is an an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. Once the application is invoked, users can see that a server is started and synced to a database. Users can access other users, their thoughts, friends, and reactions to thoughts. Users can create, update, and delete users and thoughts from the database.

## Installation
To invoke the application, clone the repository at [https://github.com/jus10hollis/Social_Network_API] and from the terminal run `npm install` to install the application modules. Next, run `npm start' so that the application listens on localhost. To test the create, read, update, and delete functions, users should open Insomnia and run the API's POST, PUT, GET, and DELETE routes.

## Technologies used
This application uses Express.js for routing, a MongoDB database, and the Mongoose ODM. The application also uses the native JavaScript `Date` object to format timestamps. The application leverages a NoSQL database so that the website can handle large amounts of unstructured data.
