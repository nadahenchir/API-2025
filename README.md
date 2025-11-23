# API-2025

A Flask REST API with ID-based endpoints for managing specializations and course items, migrated from name-based to UUID-based structure.

## Features

- **ID-based endpoints** using UUIDs instead of names
- **CRUD operations** for Specializations and Course Items
- **Flask-Smorest** for automatic Swagger UI documentation
- **Separated resources** with proper database structure
- **Docker support** for containerization
- **RESTful API design** with proper HTTP status codes

## API Endpoints

### Specializations
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/specialization` | Get all specializations |
| POST | `/specialization` | Create a new specialization |
| GET | `/specialization/{id}` | Get a specific specialization |
| PUT | `/specialization/{id}` | Update a specialization |
| DELETE | `/specialization/{id}` | Delete a specialization |

### Course Items
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/course_item` | Get all course items |
| POST | `/course_item` | Create a new course item |
| GET | `/course_item/{id}` | Get a specific course item |
| PUT | `/course_item/{id}` | Update a course item |
| DELETE | `/course_item/{id}` | Delete a course item |

### Utility
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/ping` | Health check endpoint |
| GET | `/swagger-ui/` | Interactive API documentation |

## Setup & Installation

### Prerequisites
- Python 3.8+
- pip
- Docker (optional)

### Local Development
1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/API2025.git
   cd API2025
2. **Create the virtual environment**
   python -m venv venv
venv\Scripts\activate  # Windows
3. **Install the dependencies**
pip install -r requirements.txt
4. **Run the application**
flask run
5. **Access the API**
API: http://127.0.0.1:5000
Documentation: http://127.0.0.1:5000/swagger-ui/

Docker Development
docker-compose up --build


This project demonstrates the migration from:
-Name-based endpoints → ID-based endpoints
-Nested course items → Separated resources
-List data structure → Dictionary data structure
-Manual error handling → Standardized error responses

This project is for academic purposes.


   
