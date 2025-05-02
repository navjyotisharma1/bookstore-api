# Bookstore API

This project is a simple Django REST API that manages a bookstore.

## Features:
- Create and view books and authors.
- RESTful API using Django REST Framework.
  
## Endpoints:
- `GET /api/items/`: List all books.
- `GET /api/items/<id>/`: Retrieve a specific book.
- `POST /api/items/`: Create a new book.

## Setup:
1. Clone the repository.
2. Create and activate a virtual environment.
3. Install dependencies with `pip install -r requirements.txt`.
4. Run migrations: `python manage.py migrate`.
5. Start the server: `python manage.py runserver`.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
