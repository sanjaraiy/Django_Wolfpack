# 🚀 JWT System
A Django project with Django Rest Framework (DRF) for JWT-based authentication, including a custom user model and authentication serializer.

## ✨ Features
- 🛠️ Custom User Model with email-based authentication.
- 🔑 JWT-based authentication for user registration and login.
- 🌐 REST APIs for user registration and login.
- ✅ Proper validation and error handling in APIs.

## 📝 Prerequisites
- 🐍 Python 3.10 or above
- 🌟 Django 3.2 or above
- 📦 Django Rest Framework
- 🔒 Django Rest Framework SimpleJWT

## ⚙️ Setup Instructions
### 1. Clone the Repository
```sh
gh repo clone sanjaraiy/Django_Wolfpack
cd jwtsystem
```

### 2. Create and Activate Virtual Environment (on Window)
```sh
python -m venv env
.\env\Scripts\activate
```

### 3. Install Dependencies 
```sh
pip install -r requirements.txt
```

### 4. Setup Environment Variables
Create a .env file in the root directory and add the following variables:
```
SECRET_KEY=your_secret_key_here
DEBUG=True
```

### 5. Run Migrations 
```sh
python manage.py makemigrations
python manage.py migrate
```

### 6. Create Superuser
```sh
python manage.py createsuperuser
```

### Run the Server
```sh
python manage.py runserver
```

## 🗂️ Project Structure
```plaintext
jwtsystem/
├── jwtsystem/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── myapp/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── serializers.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── manage.py
└── requirements.txt
```

