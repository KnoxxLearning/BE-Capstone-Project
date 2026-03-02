# BE-Capstone-Project

Ecommerce API
Project Overview
This project is a RESTful API built using Django and Django REST Framework.
It manages products and categories for an ecommerce platform.

Tech Stack
•	Python
•	Django
•	Django REST Framework
•	SQLite (development database) accessed through Django Object Relational Model

Features
•	Create, Read, Update, Delete Categories
•	Create, Read, Update, Delete Products
•	Product-to-Category relationship
•	RESTful endpoints returning JSON

API Endpoints
Categories
Method	Endpoint	Description
GET	/api/categories/	List all categories
POST	/api/categories/	Create category
GET	/api/categories/{id}/	Retrieve category
PUT	/api/categories/{id}/	Update category
DELETE	/api/categories/{id}/	Delete category

Products
Method	Endpoint	Description
GET	/api/products/	List all products
POST	/api/products/	Create product
GET	/api/products/{id}/	Retrieve product
PATCH	/api/products/{id}/	Partial update
DELETE	/api/products/{id}/	Delete product
