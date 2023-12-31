# Django REST API - Student and Course Management

This Django REST project serves as an API for managing student and course data. It provides endpoints to handle student information (such as RG, CPF, and email) and course details (course name, course code, level, and period).

## Features

Authentication System: The API includes a robust authentication mechanism to ensure data security and privacy.

CRUD Operations: The project implements CRUD functionalities for both students and courses, allowing Create, Read, Update, and Delete operations on the respective endpoints.

## Setup Instructions:

Clone the Repository:

git clone https://github.com/Leckalmeida/django-rest-student-course.git

Install Dependencies:
pip install -r requirements.txt

Run Migrations:
python manage.py migrate

Start the Server:
python manage.py runserver

Access the API:
Open your web browser or API testing tool and go to http://localhost:8000/api/.

## API Endpoints

/api/students/: Endpoint to manage student data (GET, POST)
/api/students/<student_id>/: Endpoint to view, update, or delete a specific student (GET, PUT, DELETE)
/api/courses/: Endpoint to manage course data (GET, POST)
/api/courses/<course_id>/: Endpoint to view, update, or delete a specific course (GET, PUT, DELETE)

## Technologies Used

Python
Django
Django Rest Framework

Feel free to explore the API endpoints and utilize the functionalities provided.
