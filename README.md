# Task & Productivity Planner API

## Overview

Task & Productivity Planner API is a RESTful backend service that helps users manage their daily tasks and track their productivity effectively. Built with Python and the FastAPI framework, this API offers a modular and scalable structure, making it easy to maintain and extend.

The API uses SQLite as the database for managing task data through SQLAlchemy ORM, ensuring a lightweight but powerful storage mechanism. User authentication is handled securely using JSON Web Tokens (JWT), providing safe access controls.

---

## Features

- *User Authentication:*  
  Secure signup and login endpoints using JWT. Only authorized users can access their tasks.

- *Task Management:*  
  Full CRUD (Create, Read, Update, Delete) operations on tasks. Users can add new tasks, update existing ones, delete completed or obsolete tasks, and fetch lists of their tasks.

- *Productivity Analytics:*  
  Provides basic productivity statistics based on tasks completed, helping users understand their performance trends.

- *Interactive API Docs:*  
  Automatically generated API documentation with Swagger UI and ReDoc, accessible during development for easy testing.

---

## Technologies Used

- *Programming Language:* Python 3.8+  
- *Web Framework:* FastAPI - for building fast and high-performance APIs  
- *Database:* SQLite - lightweight database engine  
- *ORM:* SQLAlchemy - to interact with the SQLite database using Python objects  
- *Authentication:* JWT (JSON Web Tokens) - secure token-based authentication mechanism

---

## Installation & Running Instructions


1. *Clone the repository* to your local machine:
    git clone <repository-url>
    cd <repository-folder>

2. *Create a virtual environment* to isolate dependencies and activate it:  
- On Windows:  
  python -m venv venv
  venv\Scripts\activate

- On Linux/macOS:  
  python3 -m venv venv
  source venv/bin/activate

3. *Install required Python packages* using pip:
  pip install -r requirements.txt

4. *Start the FastAPI server* with automatic reload for development: 
  uvicorn app.main:app --reload 

5. *Open your browser* and navigate to the interactive API docs at:  
  http://127.0.0.1:8000/docs

You are now ready to use and test the API locally.
