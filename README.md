# Flask REST API

This is a very simple REST API built with Flask. The API allows users to retrieve and add data to an SQLite database. 
The tutorial followed was by Dave Gray on Youtube
It includes two endpoints:

- **GET /api/users/**: Returns a list of all users in the database.
- **POST /api/users/**: Adds a new user to the database.

## Requirements

Before you run this, make sure you have the following installed:

- Python 3.x
- pip (Python package manager)

## Setup

1. **Clone the repository** to your local machine
2. **Create and activate a virtual environment**
3. **Install required dependencies**
4. Database will automatically be created the first time the service runs
5. Start the Flask application
6. Test GET/api/users & POST/api/users with **http://127.0.0.1:5000/api/users/** in the browser or Postman 
7. You can add new data with Postman in JSON format:
  {"name": "test", "email": "test@test.com"}

