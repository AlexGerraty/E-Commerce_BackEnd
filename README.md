# E-Commerce_BackEnd

This is a functional Express.js API that allows you to manage data in a MySQL database using Sequelize.

API Documentation
The following API routes are available:

Categories
GET /api/categories: Retrieves all categories.
POST /api/categories: Creates a new category.
PUT /api/categories/:id: Updates a category with the given id.
DELETE /api/categories/:id: Deletes a category with the given id.

Products
GET /api/products: Retrieves all products.
POST /api/products: Creates a new product.
PUT /api/products/:id: Updates a product with the given id.
DELETE /api/products/:id: Deletes a product with the given id.

Tags
GET /api/tags: Retrieves all tags.
POST /api/tags: Creates a new tag.
PUT /api/tags/:id: Updates a tag with the given id.
DELETE /api/tags/:id: Deletes a tag with the given id.
When you open the API GET routes in Insomnia Core for categories, products, or tags, the data for each of these routes will be displayed in a formatted JSON. When you test API POST, PUT, and DELETE routes in Insomnia Core, you will be able to successfully create, update, and delete data in the database.
