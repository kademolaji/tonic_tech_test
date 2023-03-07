# Qustion

Design a basic bank-versioned API with the ability to signup, sign in, and initiate transfers between accounts with ExpressJS (Node.js Framework). Your API should utilize refresh token mechanism for re-authenticating users using Redis; the persistent storage should be MongoDB, while your cache storage should be Redis (not mandatory to implement a caching system), with at least one route(s) requiring authentication, and another requiring authorization (2 role types definition should do) implemented.



## Requirements

Before starting, you need to have Git and Node.js installed. Alternatively, you can download the code as a zip file.

You will also need to create a .env file at the root directory, and you will need to create a MongoDB database. Insert the following into the .env file:
MONGO_URI: The URI of your MongoDB database. JWT_SECRET: The secret key used to sign the JWT. PORT: The port the application will run on.

Kindly ensure that you are in the root directory before running the following commands.

## Install dependencies
    npm install

## Start server
    node index
