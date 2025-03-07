# Hands-on Practice: Clean Architecture with Python
This project is a hands-on practice for implementing the Clean Architecture design pattern using Python. It is part of the curriculum for the Software Engineering Academy at Institut Teknologi Bandung (ITB).

## Prerequisites

- Python 3.x
- Flask
- Flask-SQLAlchemy

## Getting Started

1. Clone this repository.
2. Install the required packages using the following command:
   ```
   pip install flask flask_sqlalchemy
   ```
3. Run the application using the following command:
   ```
   python app.py
   ```

## How to test

```bash
# Create a user:
curl -X POST http://127.0.0.1:5000/users -H "Content-Type: application/json" -d '{"name": "John Doe", "email": "john@example.com"}'

# Fetch users:
curl -X GET http://127.0.0.1:5000/users
```
