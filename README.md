Setup and run
================

Note: This tutorial was completed on Windows Server 2016 with Python 3.7

Install virtual environment:
```
python -m venv django_env
```

Activate it:
```
./django_env/Scripts/activate
```

Install dependencies:
```
pip install -r requirements.txt
```

Run application:
```
cd mysite
python manage.py runserver
```

Open browser at htpp://localhost:8000/polls/