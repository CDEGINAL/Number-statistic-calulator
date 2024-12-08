# Number-statistic-calulator


Number Statistics Application
This Django application allows users to input numbers either through a form or file upload and calculates various statistics including sum, mean, median, mode, range, prime numbers, and Armstrong numbers.
Setup Instructions

Create a virtual environment and activate it:

bashCopypython -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

Install required packages:

bashCopypip install django

Navigate to the project directory and run migrations:

bashCopypython manage.py makemigrations
python manage.py migrate

Start the development server:

bashCopypython manage.py runserver

Open your web browser and visit: http://127.0.0.1:8000/

Features

Input numbers via text area (comma-separated)
Upload file containing numbers (comma-separated)
Cart showing count of unique numbers
Calculation of various statistics:

Sum
Mean
Median
Mode
Range
Prime numbers
Armstrong numbers



Project Structure
Copyassignment/
├── manage.py
├── assignment/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── statistics/
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── forms.py
    ├── models.py
    ├── urls.py
    ├── views.py
    ├── templates/
    │   └── statistics/
    │       ├── base.html
    │       ├── home.html
    │       └── results.html
    └── static/
        └── statistics/
            └── css/
                └── style.css
