# 👨‍💻 Basic Employee Website

A basic web application built with Django that allows you to manage employee data. It demonstrates how to create, read, update, and delete (CRUD) employee records using Django’s Model-View-Template (MVT) architecture.

---

## 🚀 Features

- Add new employees
- Edit existing employee information
- Delete employees
- View a list of all employees
- Admin panel access
- Responsive templates using HTML and CSS

---

## 🛠️ Tech Stack

- **Backend:** Python3, Django
- **Frontend:** HTML5, CSS3, Bootstrap
- **Database:** SQLite (default in Django)
- **Environment management:** `.env` variables

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/BasicEmployeeWebsite.git
cd BasicEmployeeWebsite
```

### 2. Set up a virtual environment (optional but recommended):
```
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 3. Install dependencies:
```
pip install -r requirements.txt
```

### 4. Set up environment variables:
Create a .env file in the root directory of your project.

### 5. Apply migrations:
```
python manage.py migrate
```

### 6. Run the development server:
```
python manage.py runserver
```

### 7. Access the app:
```
http://127.0.0.1:8000/
```

---

## 🗒️ Notes
To access the Django admin, create a superuser:
```
python manage.py createsuperuser
```
And go to:
```
http://127.0.0.1:8000/admin/
```
