Project Name
A simple CRUD application using Node.js, Express, MongoDB and Mongoose

Project Structure
The project is structured as follows:
app.js: The main application file
routes/: Directory containing route handlers
models/: Directory containing database schema definitions
views/: Directory containing template files
public/: Directory containing static assets
Dependencies
The project depends on the following packages:
express: Web framework for Node.js
mongoose: MongoDB ORM
express-handlebars: Templating engine
morgan: HTTP request logger
cookie-parser: Cookie parsing middleware
API Endpoints
The following API endpoints are available:
GET /: Render the index page
GET /get-data: Retrieve data from the database
POST /insert: Insert new data into the database
POST /update: Update existing data in the database
POST /delete: Delete data from the database
Database Schema
The database schema is defined as follows:
user-data: Collection containing documents with the following fields:
title: String
content: String
author: String
