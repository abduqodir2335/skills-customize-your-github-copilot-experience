# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API in Python with FastAPI to practice defining endpoints, handling JSON data, and using HTTP methods.

## 📝 Tasks

### 🛠️ Create Item Endpoints

#### Description
Use the provided starter code to build endpoints for viewing items in an in-memory collection.

#### Requirements
Completed program should:

- Implement a `GET /items` endpoint that returns the collection as JSON
- Start successfully as a FastAPI application
- Return an empty collection when no items have been added

### 🛠️ Add Items to the Collection

#### Description
Add an endpoint that accepts a new item in a JSON request and stores it in the collection.

#### Requirements
Completed program should:

- Implement a `POST /items` endpoint that accepts an item with a `name`
- Add the new item to the in-memory collection
- Return the created item as JSON
