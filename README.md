# testing-crud-login-drf
Creation of an application in django on music albums

## Before
Before you must verify that you have the latest python version downloaded

# Start
In your terminal
first create a virtual environment
```sh
python -m venv env
```
In windows
```sh
env\Scripts\activate.bat
```
In Unix o MacOS run
```sh
source env\Scripts\activate.bat
```
Run the command
```sh
pip install -r requirements.txt
```

Create an .env file in the same location as the manage.py file

### inside the .env file
```sh
  - DJANGO_SETTINGS_MODULE = 'app.settings'
  - DB_ENGINE = 'django.db.backends.postgresql'
  - DB_NAME = DATABASE NAME
  - DB_USER = NAME USER IN THE DATABASE
  - DB_PASSWORD = DATABASE PASSWORD
  - DB_HOST = '127.0.0.1'
  - DB_PORT = '5432'
```

## After
Run the command to perform the migrations to the database
```sh
  python manage.py makemigrations core
```
then run the command

```sh
  python manage.py migrate
```
and then run the command
```sh
  python manage.py runserver
```


### this is tha page
[![Captura.png](https://i.postimg.cc/MK9XvdKH/Captura.png)](https://postimg.cc/dLTJfRCc)
