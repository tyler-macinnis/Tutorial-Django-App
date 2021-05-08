# Tutorial-Django-App
Django Tutorial App from Documentation

## Setup

1. ```python -m venv venv```

2. ```source venv/bin/activate```

3. ```pip install -r requirements.txt```

## Usage

1. ```cd Tutorial-Django-App/```

2. ```source venv/bin/activate```

3. ```cd mysite/```

4. ```python manage.py migrate```

5. ```python manage.py makemigrationsmigrations polls```

6. ```python manage.py migrate```

Now it's time to make a superuser so you can login as an admin,

7. ```python manage.py createsuperuser```

8. ```python manage.py runserver```

Now go to [Polls](http://localhost:8000/polls/) if you want to access polls as a user or [Admin Login](http://localhost:8000/admin/) if you want to access polls as an admin.