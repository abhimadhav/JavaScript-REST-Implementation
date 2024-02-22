# About

This project is a RESTful API application built with Node.js and Express.js that provides endpoints for managing hospital and ventilator information in a MongoDB database. The API implements user authentication and authorization using JSON Web Tokens (JWT) to secure the endpoints.

## Features

User Authentication: Users can authenticate by providing a username and password to obtain a JWT token for accessing protected routes.

Ventilator Management: The API allows CRUD operations (Create, Read, Update, Delete) on ventilators, including adding new ventilators, updating the status of existing ventilators, and deleting ventilators.

Hospital Information: The API provides endpoints to retrieve details of all hospitals and search for hospitals by name.

Ventilator Search: Users can search for ventilators based on their status (e.g., available, occupied) or the hospital name.

Protected Routes: All API endpoints are protected by JWT authentication, ensuring that only authenticated users can access and manipulate the data.

## Technologies Used

Node.js

Express.js

JSON Web Tokens (JWT)

MongoDB

RESTful API Design

## API Endpoints

POST /login: Authenticate with a username and password to obtain a JWT token.

GET /HospitalDetails: Retrieve all hospital details.

GET /VentilatorDetails: Retrieve all ventilator details.

POST /SearchVentilatorStatus: Search for ventilators by status.

POST /Searchventbyname: Search for ventilators by hospital name.

POST /Searchhospbyname: Search for hospitals by name.

PUT /UpdateVentilator: Update the status of a ventilator.

POST /AddVentilator: Add a new ventilator.

DELETE /deleteventilator: Delete a ventilator.
