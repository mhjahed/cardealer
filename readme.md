🚗 Car Dealer Web Project

A modern, responsive, and feature-rich web application for managing car listings, users, and dealerships. Built with Django, HTML, CSS, and JavaScript.

🌟 Features

User Authentication & Authorization

Sign up, login, logout functionality

User roles: Admin, Dealer, Customer

Car Listings Management

Add, edit, delete cars (Admin & Dealer)

Search and filter by brand, model, price, and type

Detailed car view page with images and specifications

Responsive Design

Fully responsive UI with HTML, CSS, and JavaScript

Mobile-first approach for seamless browsing

Rich Text Editor

Integrated CKEditor for detailed car descriptions

Real-time Features

Dynamic car search and filtering

Client-side interactivity with JS

Database Management

PostgreSQL or SQLite for storing user and car data

Django ORM for easy database operations

Deployment Ready

Configured for production deployment

Supports static files management and security best practices

🛠️ Technologies Used

Backend: Python, Django, Django Allauth

Frontend: HTML5, CSS3, JavaScript

Database: SQLite / PostgreSQL

Libraries & Tools:

django-ckeditor for rich text editing

django-multiselectfield for multi-choice fields

django-js-asset for JS asset management

whitenoise for static files handling

Deployment: Heroku / any preferred server

🎨 Screenshots

Home Page


Car Listing Page


Car Detail Page


🚀 Installation

Clone the repository

git clone https://github.com/yourusername/cardealer-web.git
cd cardealer-web


Create & activate virtual environment

python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate


Install dependencies

pip install -r requirements.txt


Apply migrations

python manage.py migrate


Create superuser (optional)

python manage.py createsuperuser


Run the development server

python manage.py runserver


Open in browser

http://127.0.0.1:8000

🌐 Deployment

The project is deployed and accessible online:
Visit Live Site

Uses Whitenoise for static files handling

Secure production-ready settings configured

🧩 Project Structure
CarDealerWeb/
│
├── cardealer/              # Django app
│   ├── templates/          # HTML templates
│   ├── static/             # CSS, JS, images
│   ├── models.py           # Database models
│   ├── views.py            # App views
│   └── urls.py             # App URLs
│
├── .venv/                  # Python virtual environment
├── manage.py               # Django management script
└── requirements.txt        # Python dependencies

⚙️ Notes

CKEditor bundled version may have security warnings; consider updating to CKEditor 5 for production.

Use psycopg2-binary for PostgreSQL support on Windows.

📜 License

This project is licensed under the MIT License.

💡 Future Improvements

Add payment gateway for online car purchases

Implement real-time chat between customers and dealers

Add car recommendation system using AI/ML

Integrate email notifications for users

🙌 Author
JAHED | https:github.com/mhjahed
