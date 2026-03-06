E-Commerce Product API

This project is a REST API built using Express.js that manages product data for an e-commerce platform using an in-memory JSON array.

The API follows REST principles and implements:

3 GET Routes

1 POST Route

3 PUT Routes

Proper HTTP status codes

In-memory data storage (No database)

Technologies Used

Node.js

Express.js

CORS Middleware

Postman (API Testing)

Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/YOUR_USERNAME/ecommerce-api.git
2️⃣ Go to Project Folder
cd ecommerce-api
3️⃣ Install Dependencies
npm install
4️⃣ Run Server
node server.js

Server will start at:

http://localhost:3000
API Routes
GET Routes
1️⃣ Get All Products
GET /products

Returns all products.

Status Code:

200 OK
2️⃣ Get Product By ID
GET /products/:id

Example:

GET /products/3

Status Codes:

200 OK
404 Not Found
3️⃣ Get Products By Category
GET /products/category/:categoryName

Example:

GET /products/category/Electronics

Status Code:

200 OK
POST Route
4️⃣ Create New Product
POST /products

Body:

{
"name": "Bluetooth Speaker",
"category": "Electronics",
"price": 2999,
"stock": 20,
"rating": 4.6
}

Status Code:

201 Created
PUT Routes
5️⃣ Replace Product
PUT /products/:id

Example:

PUT /products/2

Body:

{
"name": "Sports Shoes",
"category": "Footwear",
"price": 1999,
"stock": 55,
"rating": 4.7
}

Status Codes:

200 OK
404 Not Found
6️⃣ Update Stock
PUT /products/:id/stock

Example:

PUT /products/3/stock

Body:

{
"stock": 60
}

Status Codes:

200 OK
404 Not Found
7️⃣ Update Price
PUT /products/:id/price

Example:

PUT /products/3/price

Body:

{
"price": 1299
}

Status Codes:

200 OK
404 Not Found
Sample Product Structure
{
"id": 1,
"name": "Wireless Mouse",
"category": "Electronics",
"price": 799,
"stock": 25,
"rating": 4.3
}
Project Features

RESTful API design

In-memory data storage

Dynamic product updates

Auto-generated IDs

Clean route structure

Proper status codes

Postman Documentation

Add your Postman link here:

POSTMAN_LINK_HERE

Example:

https://documenter.getpostman.com/view/xxxxx
Render Deployment

Add your Render API link here:

RENDER_LINK_HERE

Example:

https://ecommerce-api.onrender.com
Author

Your Name
