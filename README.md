# 🎓 E-Learning System (E-Gyan Portal)

A full-featured web-based **E-Learning Management System** built with **Django**.
This project allows students and teachers to interact through a secure, structured platform for online learning .

---

##  Features

- 👨‍🎓 Student registration, login, course enrollment
- 👩‍🏫 Teacher dashboard for uploading courses, assignments
- 🔒 Role-based access control (Student / Teacher ( Admin))
- 📄 Assignment uploads and submission tracking
- 📚 Course material uploads
- 📊 Dashboard, progress tracking

---

 **Tech Stack**

| Layer        | Technology                |
|--------------|----------------------------|
| Backend      | Python, Django             |
| Frontend     | HTML, CSS, Bootstrap       |
| Database     | SQLite (by default)        |
| Media Files  | Stored using Django's `media/` directory |
| Tools        | Git, VS Code, Django Admin |

---

**Requirements to Run the Project**

Make sure the following are installed and set up:

 1. System Requirements

Python: 3.8 or above
pip: Python package manager
(Optional but recommended) Virtual Environment: venv

2. Install Required Packages

Open your project in the terminal and run the following:

 Option 1: Install individually
pip install django
pip install pillow

 Option 2: Use requirements.txt (Recommended)
pip install -r requirements.txt

Make sure your requirements.txt file contains:

Django>=3.2
pillow>=8.0

3. Using a Virtual Environment (Optional but Recommended)
Create and activate a virtual environment:

python -m venv venv
On Windows:
  venv\Scripts\activate

4. Apply Migrations
Run the following command to apply database migrations:

  python manage.py migrate

5. (Optional) Create Superuser for Admin Panel
   
  python manage.py createsuperuser

6. Run the Development Server
 
  python manage.py runserver
  
Open in browser: http://127.0.0.1:8000

