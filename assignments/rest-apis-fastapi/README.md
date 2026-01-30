# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a RESTful API using FastAPI that handles HTTP requests, processes data, and returns structured responses. Students will learn about API design, request/response handling, and data validation in Python.

## 📝 Tasks

### 🛠️	Create a Basic REST API

#### Description
Create a FastAPI application that serves as a simple REST API with multiple endpoints to handle different types of requests and return JSON responses.

#### Requirements
Completed program should:

- Define at least 3 routes with different HTTP methods (GET, POST, PUT, or DELETE)
- Accept and validate input data using Pydantic models
- Return properly formatted JSON responses with appropriate HTTP status codes
- Include basic error handling for invalid requests
- Use path parameters and query parameters appropriately
- Include docstrings for all endpoints

#### Example (endpoint)
```python
from fastapi import FastAPI
from pydantic import BaseModel

app = FastAPI()

class Item(BaseModel):
    name: str
    price: float

@app.get("/items/")
async def get_items():
    return [{"name": "Widget", "price": 9.99}]

@app.post("/items/")
async def create_item(item: Item):
    return {"created": item}
```

### 🛠️	Add Data Persistence and Testing

#### Description
Enhance the API with data storage and create basic tests to verify functionality.

#### Requirements

- Implement in-memory or file-based data storage (list or JSON file)
- Create at least 2 unit tests using `pytest` to verify API functionality
- Include a `/docs` endpoint (automatically provided by FastAPI)
- Document the API with clear request/response examples in comments
- Test the API using FastAPI's built-in testing utilities

