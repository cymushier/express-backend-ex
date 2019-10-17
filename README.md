This repo is defines the basic bare-minimum of express backend with MongoDB integration.

# Getting started

To get the Node server running locally:

- Clone this repo
- `npm install` to install all required dependencies
- `node server` to start the local server

# Code Overview

## Dependencies

- [expressjs](https://github.com/expressjs/express) - The server for handling and routing HTTP requests
- [mongoose](https://github.com/Automattic/mongoose) - For modeling and mapping MongoDB data to javascript 
- [body-parser](https://github.com/expressjs/body-parser) - Node.js body parsing middleware to improve parsing of request data.
- [dotenv](https://github.com/motdotla/dotenv) - Loads environment variables from `.env` file to easily define variables in a sepate file.

## Application Structure

- `server.js` - The entry point to the application. Bootstraps the server and express bindings.
- `app.js` - The application. This file defines our express server and connects it to MongoDB using mongoose. It also requires the routes and models we'll be using in the application.
- `models/` - This folder contains the schema definitions for our Mongoose models.


<br />

[![Brought to you by Cyrus Mushier](https://scontent-ams4-1.xx.fbcdn.net/v/t1.0-9/59051910_2387150698186154_7888275448528896000_n.jpg?_nc_cat=106&_nc_oc=AQkud7Z6m606ikk5TtCA17hJN3bieomKknF-IjOVXdi4Pu1tKUm5OubnSoHccOlWnbU&_nc_ht=scontent-ams4-1.xx&oh=f06701f7220abce07d50a9dafd920c2c&oe=5E1D06F0)](https://www.linkedin.com/in/mushierc/)
