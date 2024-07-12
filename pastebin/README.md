# Django Rest Framework - PasteBin Tutorial

## Pre-Requisites:

### Download and install following:

- Git
- VS Code
- Python
- Create and activate venv `python -m venv venv`
- Install packages `pip install django djangorestframework, pygments`

## Getting started

- Create a django project `django-admin startproject pastebin`
- Goto project directory `cd pastebin`
- Create a django app in project directory `python manage.py startapp snippets`
- Add `rest_framework` and `snippets` to the `INSTALLED_APPS` in `pastebin\settings.py`

### Creating a model to work with

- Create `Snippet` model in `snippets/models.py`
- Make migrations `python manage.py makemigrations snippets`
- Migrate `python manage.py migrate snippets`
- Create a Serializer class in `snippets/serializers.py`
- Work with Serializers using shell
- Use ModelSerializers - to avoid duplication in Model and ModelSerializer classes.
- Writing regular Django views using our Serializer
- 