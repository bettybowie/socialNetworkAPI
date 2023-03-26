# socialNetworkAPI

## Description

This is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. This application uses Express.js for routing, a MongoDB database, and the Mongoose ODM.

## Installation

To install necessary dependencies, run the following command:
   
```
npm i
```

To start the API server, run the following command:

```
npm start
```

## Usage

Once the server is started, the Mongoose models are synced to the MongoDB database.

The routes can be tested in Insomnia. 

API GET routes for users and thoughts will retrieve and display data in a formatted JSON.

API POST, PUT, DELETE routes can create, update, and delete users and thoughts in the database.

API POST and DELETE routes can also create and delete reactions to thoughts and add and remove friends to a user’s friend list.

## Visual

[Demo Video](https://drive.google.com/file/d/1kNmOlH8QHtZrNDA0ZJeKOz7Hn-hH2pCp/view)

## License

This project is licensed under MIT license.

