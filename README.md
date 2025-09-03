# Laboratorio3_Django

This is a project developed with Django.

# Project Structure 🤖

```
src/
|   requeriments.txt
│   db.sqlite3
│   manage.py
│
├── config/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── __pycache__/
│
├── quiz_app/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   ├── __pycache__/
│   ├── migrations/
│   │   ├── __init__.py
│   │   ├── 0001_initial.py
│   │   ├── 0002_examattempt_useranswer.py
│   │   └── __pycache__/
│   └── templates/
│       ├── base.html
│       └── quiz/
│           └── exam_detail.html
│           └── exam_form.html
│           └── exam_list.html
│           └── exam_result.html
│           └── question_form.html
│           └── take_exam.html
├── accounts/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   ├── __pycache__/
│   ├── migrations/
│   │   ├── __init__.py
│   │   ├── 0001_initial.py
│   │   └── __pycache__/
│   └── templates/
│       └── accounts/
│           └── edit_profile.html
│           └── profile.html
│       └── registration/
│           └── login.html
│           └── registrer.html

```

# Project installation 💯✅

1. 📍**Clone repository** 

  ```sh
   git clone https://github.com/your_user/your_repository.git
   cd your_repository/src
   ```

2. 📍**Create and activate a virtual environment**

  ```sh
   python -m venv venv
   venv\Scripts\activate   #Windows
   source venv/bin/activate  # Linux/Mac
   ```
3. 📍**Install the dependencies**

  ```sh
   pip install django
   ```

4. 📍**Perform the migrations**

  ```sh
   python manage.py makemigrations quizz
   python manage.py makemigrations accounts
   python manage.py migration
   ```

5.  📍**Create a superuser (for admin)**

  ```sh
   python manage.py createsuperuser
   ```

6.  📍**Run the server**

  ```sh
   python manage.py runserver
   ```

7.  📍**Access the application**

    - [http://127.0.0.1:8000/](http://127.0.0.1:8000/) for principal web.


# Annotations 🗒️

- Don't forget to add a `.gitignore` file to avoid uploading unnecessary files like `venv/`, `db.sqlite3`, `__pycache__/`, etc.
