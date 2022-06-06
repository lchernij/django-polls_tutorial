# Polls website

Tutorial

- [Part 1](https://docs.djangoproject.com/en/4.0/intro/tutorial01/) - Creating a project
- [Part 2](https://docs.djangoproject.com/en/4.0/intro/tutorial02/) - Set up the database, create your first model, and get a quick introduction to Django’s automatically-generated admin site.
- [Part 3](https://docs.djangoproject.com/en/4.0/intro/tutorial03/) - Focus on creating the public interface – “views.”


## Python

`sudo apt install python3`
`sudo apt install python3-django`

## Postgresql

`sudo apt install libpq-dev`
`pip install psycopg2`

https://www.psycopg.org/install/

## Create projeto

`django-admin startproject _NOME_PROJETO_`

## Create App

`python manage.py startapp _NOME_APP_`

## Run project

`python3 manage.py runserver`

## Run migration

`python3 manage.py migrate`

## Create migrations

`python3 manage.py makemigrations _NOME_APP_`

## "Tinker"

`python3 manage.py shell`