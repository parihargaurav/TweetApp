Twitter-like Application

This is a Twitter-like application built with Django on the backend and HTML + Bootstrap on the frontend. The app allows users to register, log in, create, edit, and delete their own tweets. Authentication is implemented so that only authorized users can edit or delete their posts.
Features

    User Registration & Login: Users can create an account and log in securely.

    Create, Edit, and Delete Tweets: After logging in, users can create their own tweets, edit them, or delete them.

    Authentication: Only authorized users can edit or delete their own tweets. Non-authorized users cannot modify posts.

    CRUD Operations: The project demonstrates the importance of CRUD operations (Create, Read, Update, Delete) in Django.

    Django Forms: Utilized Django forms for handling input validation and submission.

    Jinja Templates: Used for rendering dynamic content and page layouts.

Technologies Used

    Backend: Django (Python)

    Frontend: HTML, Bootstrap

    Authentication: Django’s built-in authentication system

    Database: SQLite (default in Django)

Setup Instructions
Prerequisites

    Python 3.x

    Django 3.x or later

    Bootstrap (integrated in HTML)

Steps to Run the Project

Clone the repository-

git clone https://github.com/your-username/twitter-like-app.git

cd twitter-like-app

Create and activate a virtual environment:

python -m venv venv

venv\Scripts\activate  # For Windows

source venv/bin/activate  # For Linux/macOS

Install required dependencies:

pip install -r requirements.txt

Apply migrations:

python manage.py migrate

Run the server:

    python manage.py runserver

    Open your browser and go to http://127.0.0.1:8000/.

Learnings from this Project

    Django Forms: Handled form creation, validation, and submission.

    CRUD Operations: Implemented Create, Read, Update, Delete functionality for tweets.

    Authentication: Implemented user authentication so that only authorized users can edit or delete their tweets.

    Django Templates (Jinja): Rendered dynamic content using Jinja templates to build interactive web pages.

Contributing

Feel free to fork the repository, make changes, and submit pull requests. Contributions are welcome!
