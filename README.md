# Django Rest Framework Product API

This repository contains a Django Rest Framework project that provides CRUD (Create, Read, Update, Delete) operations for a Product model.
The implementation utilizes both generic views and viewsets to demonstrate different approaches for building API endpoints.

## Features

- **Generic Views:**
  - Implementation of CRUD operations using Django Rest Framework's generic views.
  - Clear and concise views for handling common API patterns.

- **Viewsets:**
  - Utilization of Django Rest Framework's viewsets for a more modular and organized API structure.
  - Demonstrates the power of viewsets with automatic CRUD functionality.

- **Product Model:**
  - A simple Django model representing a product with fields such as name, description, price, etc.

## Installation
Api Endpoints using Generic views are :-
1. http://52.62.146.145/v1/api/products/  (To get all products)
2. http://52.62.146.145/v1/api/products/  (To create a product)
3. http://52.62.146.145/v1/api/products/3/  (To update a product)
4. http://52.62.146.145/v1/api/products/3/  (To delete a product)

Api Endpoints using viewsets are :-
1. http://52.62.146.145/v1/products/  (To get all products)
2. http://52.62.146.145/v1/products/   (To create a product)
3. http://52.62.146.145/v1/products/7/ (To update a product)
4. http://52.62.146.145/v1/products/7/  (To delete a product)
