# FastAPI CRUD Example

A simple FastAPI application demonstrating basic CRUD operations (Create, Read, Update, Delete) for managing student data using path parameters, query parameters, and request bodies with Pydantic models.

## Features

- Get student details by ID (path parameter)  
- Search student by name (query parameter)  
- Create new student records (POST)  
- Update existing student data (PUT)  
- Delete student records (DELETE)  

## Technologies Used

- Python 3.13.0  
- FastAPI  
- Pydantic  

## Installation (Mac)

1. Clone the repository:

   ```bash
   git clone https://github.com/saararamsy/fastapi-crud.git
   cd fastapi-crud

2. Create a Python virtual environment:

   ```bash
   python3 -m venv venv

 3. Activate the virtual environment:

   ```bash
  source venv/bin/activate
```

 4. Install dependencies:

   ```bash
  pip install fastapi uvicorn

  ```
Running the Application (Mac)
Start the FastAPI server with:

  ```bash
uvicorn myapi:app --reload
```
(Replace myapi with your actual Python filename without the .py extension.)

The API will be available at: http://127.0.0.1:8000

