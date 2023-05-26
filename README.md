# Restaurant API

This is a simple Node.js application that creates a RESTful API for managing restaurants. It allows you to retrieve all restaurants, add a new restaurant, and delete a restaurant by ID. The API documentation is provided using Swagger UI.

## Prerequisites

To run this application, you need to have the following installed on your machine:

- Node.js
- npm (Node Package Manager)

## Getting Started

1. Clone the repository:

git clone https://github.com/AravAravind/REST-API-Swagger.git


2. Install the dependencies:

npm install


3. Start the server:

node index.js


The server will start running on `http://localhost:4000`.

4. Access the API documentation:

Open your web browser and navigate to `http://localhost:4000/api-docs`. Here, you can explore the API endpoints and interact with them using Swagger UI.

## API Endpoints

### Retrieve All Restaurants

- **Method:** GET
- **Response:** An array of restaurant objects

### Add a New Restaurant

- **Method:** POST
- **Request Body:** JSON object containing the `id` and `name` of the restaurant
- **Response:** Confirmation message with the created restaurant details

### Delete a Restaurant

- **Method:** DELETE
- **Description:** Delete a restaurant by ID
- **URL Parameter:** ID of the restaurant to be deleted
- **Response:** Confirmation message with the updated list of remaining restaurants

