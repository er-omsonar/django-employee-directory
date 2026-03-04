📁 Django Employee Directory

A simple Employee Directory Web Application built using Django and Bootstrap.

🚀 Features

Add employees using Django Admin Panel

Upload employee photo

Display all employees on homepage in table format

Click on employee name to view detailed profile

Clean Bootstrap UI

Image upload support

Structured database design

🛠 Tech Stack

Python

Django

Bootstrap

SQLite (default Django DB)

📋 Employee Fields

Each employee record contains:

First Name

Last Name

Designation

Email

Phone Number

Profile Photo

🖥 Application Workflow

Admin logs into Django Admin Panel

Adds employee details

Homepage displays all employees in table format

Clicking employee name opens detail page showing:

Photo

Full Name

Designation

Email

Phone

📂 Project Structure
employee-directory/
│
├── employee_app/
├── templates/
├── static/
├── manage.py
└── requirements.txt
⚙ How to Run Locally

Clone the repository:

git clone 
cd django-employee-directory

Create virtual environment:

python -m venv env
source env/bin/activate  # Mac/Linux
env\Scripts\activate     # Windows

Install dependencies:

pip install -r requirements.txt

Run migrations:

python manage.py migrate

Create superuser:

python manage.py createsuperuser

Run server:

python manage.py runserver
👨‍💻 Author

Om Sonar
Computer Engineering Student
Learning Django, React, and Full Stack Development
