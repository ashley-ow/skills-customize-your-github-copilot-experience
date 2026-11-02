# 📘 Assignment: REST APIs with FastAPI

## 🎯 Objective

Build a small REST API with FastAPI to manage a collection of items. You will create endpoints, accept validated request data, and return appropriate responses when items are missing.

## 📝 Tasks

### 🛠️ Create the API and List Items

#### Description
Create a FastAPI application for managing items, such as books or board games. Start with an in-memory collection and an endpoint that returns all items.

#### Requirements
Completed program should:

- Create a FastAPI application instance in `main.py`.
- Define an in-memory collection containing at least two items, each with a unique integer ID and a name.
- Implement `GET /items` to return the collection as JSON.
- Run the app locally and confirm the endpoint works using the interactive API documentation at `/docs`.

### 🛠️ Add and Retrieve Items

#### Description
Add endpoints for creating an item and retrieving one item by its ID. Use a Pydantic model to validate the data sent when creating an item.

#### Requirements
Completed program should:

- Define a Pydantic model that requires an item's name.
- Implement `POST /items` to accept a valid item, assign it a unique ID, store it, and return the created item.
- Implement `GET /items/{item_id}` to return the matching item.
- Return a `404 Not Found` response when the requested ID does not exist.

### 🛠️ Delete Items and Check Responses

#### Description
Add an endpoint for deleting an item, then use the API documentation to test successful and unsuccessful requests.

#### Requirements
Completed program should:

- Implement `DELETE /items/{item_id}` to remove an existing item.
- Return a clear success response when an item is deleted.
- Return a `404 Not Found` response when attempting to delete an ID that does not exist.
- Test listing, creating, retrieving, and deleting items through `/docs`, including invalid item data and unknown IDs.
