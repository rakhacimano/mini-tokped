# Express.js MongoDB CRUD Product Project

## Installation

1. Ensure Node.js and npm are installed on your computer.
2. Clone this repository:

    ```bash
    git clone https://github.com/rakhacimano/mini-tokped.git
    ```

3. Navigate to the project directory:

    ```bash
    cd mini-tokped
    ```

4. Install dependencies:

    ```bash
    npm install
    ```
    MONGODB_URI=mongodb://localhost:27017/db_name
    ```

6. Run the application:

    ```bash
    npm run serve
    ```

## Endpoints

### 1. GET /products

Retrieve a list of all products.

### 2. GET /products/:id

Retrieve a single product by ID.

### 3. POST /products

Add a new product. Send product data in JSON format.

### 4. PUT /products/:id

Update a product by ID. Send updated product data in JSON format.

### 5. DELETE /products/:id

Delete a product by ID.

## Example Usage with Postman

1. **Get All Products (GET):**

    - URL: `http://localhost:3000/products`
    - Method: GET

2. **Get One Product (GET):**

    - URL: `http://localhost:3000/products/{product_id}`
    - Method: GET

3. **Add New Product (POST):**

    - URL: `http://localhost:3000/products`
    - Method: POST
    - Body: Set as JSON and enter the product data you want to add.

4. **Update Product (PUT):**

    - URL: `http://localhost:3000/products/{product_id}`
    - Method: PUT
    - Body: Set as JSON and enter the product data you want to update.

5. **Delete Product (DELETE):**

    - URL: `http://localhost:3000/products/{product_id}`
    - Method: DELETE

## Notes

Make sure to replace `{product_id}` with the corresponding product ID.

Thank you for using the CRUD Product application with Express.js and MongoDB! If you have any questions or issues, feel free to contact us.
