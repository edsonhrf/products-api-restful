# Product CRUD API

This is a CRUD (Create, Read, Update, Delete) project to manage products using a RESTful API in Spring Boot with PostgreSQL database.

## Installation

1. **PostgreSQL Database:**
    - Install PostgreSQL on your machine if you haven't already.
    - Create a database named `products-api` in PostgreSQL.

2. **Cloning the Repository:**
    - Clone this repository to your local machine.

3. **Project Setup:**
    - Open the project in your preferred IDE.
    - Make sure you have the dependencies listed in the `pom.xml` file installed in your development environment.

## Usage

This project provides endpoints to create, read, update, and delete products.

- **POST /products:** Create a new product. Requires a JSON body containing the product details.
- **GET /products:** Get all existing products.
- **GET /products/{id}:** Get a specific product by its ID.
- **PUT /products/{id}:** Update an existing product. Requires a JSON body containing the new product details.
- **DELETE /products/{id}:** Delete an existing product by its ID.

## Examples of HTTP Requests

You can test the API using tools like cURL, Postman, Insomnia, etc. Here are some examples of HTTP requests:

1. **Create a Product:**
   ```http
   POST /products
   Content-Type: application/json
   
   {
       "name": "Product Name",
       "description": "Product Description",
       "price": 99.99
   }

2. **Get All Products:**
   ```http
   GET /products

3. **Get a Product by ID:**
   ```http
   GET /products/{id}

4. **Update a Product:**
   ```http
   PUT /products/{id}
   Content-Type: application/json

   {
   "name": "New Product Name",
   "description": "New Product Description",
   "price": 129.99
   }

5. **Delete a Product:**
   ```http
   DELETE /products/{id}

5. **Contact:**
   For more information or support, please contact the project maintainer

   Email: edsonhrf@gmail.com



