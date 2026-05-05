## Django Custom Dashoard

A custom Django admin dashboard for Users, Products, Orders, Analytics/Charts and Roles/Permissions. This is not using Django's default admin interface as the main dashboard. <br><br>

### Features
Responsive Design<br>
Customizable UI<br>
Lightweight<br>
Modular Structure<br>
Developer-Friendly<br><br>

### Tech Stack
Backend: Django<br>
Language: Python<br>
Frontend: HTML<br><br>

### Structure
`CustomDashboard/`<br>
`│── accounts/`<br>
`│   ├── __init__.py`<br>
`│   ├── admin.py`<br>
`│   ├── apps.py`<br>
`│   ├── models.py`<br>
`│   ├── tests.py`<br>
`│   ├── urls.py`<br>
`│   └── views.py`<br>
`│`<br>
`│── CustomDashboard/`<br>
`│   ├── __init__.py`<br>
`│   ├── asgi.py`<br>
`│   ├── settings.py`<br>
`│   ├── urls.py`<br>
`│   └── wsgis.py`<br>
`│`<br>
`│── dashboard/`<br>
`│   ├── templates/dashboard/`<br>
`│   │   ├── accounts/templates/dashboard/`<br>
`│   │   │   └── login.html`<br>
`│   │   ├── dashboard/templates/dashboard/`<br>
`│   │   │   ├── base.html`<br>
`│   │   │   └── index.html`<br>
`│   │   ├── orders/templates/dashboard/`<br>
`│   │   └── products/templates/dashboard/`<br>
`│   ├── __init__.py`<br>
`│   ├── admin.py`<br>
`│   ├── apps.py`<br>
`│   ├── models.py`<br>
`│   ├── tests.py`<br>
`│   ├── urls.py`<br>
`│   └── views.py`<br>
`│`<br>
`│── orders/`<br>
`│   ├── __init__.py`<br>
`│   ├── admin.py`<br>
`│   ├── apps.py`<br>
`│   ├── models.py`<br>
`│   ├── tests.py`<br>
`│   ├── urls.py`<br>
`│   └── views.py`<br>
`│`<br>
`│── products/`<br>
`│   ├── __init__.py`<br>
`│   ├── admin.py`<br>
`│   ├── apps.py`<br>
`│   ├── models.py`<br>
`│   ├── tests.py`<br>
`│   ├── urls.py`<br>
`│   └── views.py`<br>
`│`<br>
`│── static/`<br>
`│   ├── css/`<br>
`│   ├── images/`<br>
`│   └── js/`<br>
`│`<br>
`│── main.py`<br>
`└── manage.py`<br><br>

### Setup
`git clone <your-repo-link>`<br>
`cd <repo>`<br>
`pip install django`<br>
`python manage.py migrate`<br>
`python manage.py runserver`<br>

Open:

`http://127.0.0.1:8000/`<br><br>

### Troubleshooting
TemplateSyntaxError (`endblock`)<br>
    → Fix incorrect `{% block %}` structure<br>
Template not found<br>
    → Add templates directory in `settings.py`<br>
Static files not loading (CSS/JS/images)<br>
    → Use: `{% load static %}` in templates<br><br>

### Preview
Custom Dashboard
<img width="1919" height="1078" alt="Screenshot 2026-05-05 075518" src="https://github.com/user-attachments/assets/b9c8e914-31ef-41de-9e91-50b394eec3c0" />
Dashboard
<img width="1849" height="933" alt="Screenshot 2026-05-05 075526" src="https://github.com/user-attachments/assets/bfd9af77-40c6-4f74-b703-6058e346bb88" /><br><br>

### Future Work
Improved UI<br>
Improved security systems<br>
Improved functionability<br><br>

### Author

Charno A.<br><br>
