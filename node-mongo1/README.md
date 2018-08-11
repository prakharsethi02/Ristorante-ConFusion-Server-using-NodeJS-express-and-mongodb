# Configuring Node Application to communicate with MongoDB server

The folder contains two files `index.js` and `operations.js`that allow node application to communicate with MongoDb server in order to perform certain database operations. 

## Development server

Run `mongo` to start mongo REPL shell. 

## index.js

`index.js` file allows to interact with the MongoDB database from a Node application.

## operations.js

`operations.js` file allows to perform various database operations on the MongoDB server from your Node application using the Node MongoDB driver.<br>

To avoid callback hell `promise` is used in both files.
