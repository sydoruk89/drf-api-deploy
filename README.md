# API Deployment

**Author:** Roman Sydoruk **Version:** 1.0.0

## Description

Django REST Framework to create an API, then “containerize” it with Docker and adding Permissions, Postgresql Database and  Authentication and switching to a Production Server. Finally deployed to Heroku.

## Architecture

* Python 3.8.3
* Poetry
* Django
* Docker
* Postgres 11
* Gunicorn
* Whitenoise

## Feature Tasks
- Modified thr application to store SECRET_KEY, ALLOWED_HOSTS, DEBUG and DATABASE information in .env file.
- Added CORS capabilities to the app and whitelist allowed origins.