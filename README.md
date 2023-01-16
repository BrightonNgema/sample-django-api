# Django CRUD Application

This is a basic CRUD (Create, Read, Update, Delete) application built using Django. The application provides an API for the Country model, allowing users to perform CRUD operations on the model via the API.

## Requirements

- Python 3.6 or later
- Django 3.2 or later
- Django REST framework 3.12 or later

## Installation

1. Clone the repository
   git clone https://github.com/your-username/django-crud-application.git

2. Create a virtual environment and activate it
   `python -m venv env`
   `source env/bin/activate`

3. Install the required packages
   `pip install -r requirements.txt`
4. Apply the migrations
   `python manage.py makemigrations`
   `python manage.py migrate`

5. Start the development server
   `python manage.py runserver`

Usage
The API provides the following endpoints for the Country model:

- `/countries/:` provides a list of all countries.
- `/countries/<int:pk>/:` provides the details of a specific country.

You can use any API client (e.g: postman) to perform CRUD operations on the API.

### Contributing

Please feel free to contribute to this project by submitting pull requests and reporting bugs.

### License

This project is licensed under the MIT License - see the LICENSE file for details.
