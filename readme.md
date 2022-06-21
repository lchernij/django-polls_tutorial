# Polls website

Tutorial

- [Part 1](https://docs.djangoproject.com/en/4.0/intro/tutorial01/) - Creating a project
- [Part 2](https://docs.djangoproject.com/en/4.0/intro/tutorial02/) - Set up the database, create your first model, and get a quick introduction to Django’s automatically-generated admin site.
- [Part 3](https://docs.djangoproject.com/en/4.0/intro/tutorial03/) - Focus on creating the public interface – “views.”
- [Part 4](https://docs.djangoproject.com/en/4.0/intro/tutorial04/) - Froms
- [Part 5](https://docs.djangoproject.com/en/4.0/intro/tutorial05/) - Automated testing
- [Part 6](https://docs.djangoproject.com/en/4.0/intro/tutorial06/) - Customize app look
- [Part 7](https://docs.djangoproject.com/en/4.0/intro/tutorial07/) - Customize admin form

## Python

`sudo apt install python3`
`sudo apt install python3-django`

## Postgresql

`sudo apt install libpq-dev`
`pip install psycopg2`

https://www.psycopg.org/install/

## Create projeto

`django-admin startproject _PROJECT_NAME_`

## Create App

`python manage.py startapp _APP_NAME_`

## Run project

`python3 manage.py runserver`

## Run migration

`python3 manage.py migrate`

## Create migrations

`python3 manage.py makemigrations _APP_NAME_`

## "Tinker"

`python3 manage.py shell`

## Run tests

`python3 manage.py test _APP_NAME_`

## Find Django source files

`python3 -c "import django; print(django.__path__)"`

In my case: `\\wsl.localhost\Pessoal\home\lcher\.local\lib\python3.10\site-packages\django\contrib\admin\templates\admin`