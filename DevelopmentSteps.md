# Django DRF Projects - Development Steps

## Pre-Requisites

- Install Python
- Install VSCode
- Install Git
- Clone git repo: `https://github.com/SinkuKumar/DjangoDRF.git`
- Install requirements.txt

## Getting Started

- Head over to `django-rest-framework.org`

### Notes

- Django REST framework provides a toolit for building web APIs, some features includes:
    - Web browsable APIs.
    - Authentication policies including `OAuth1a` and `OAuth2`.
    - Serialization supports both ORM and non-ORM data sources.
    - Customisable, function and class based views.
    - Extensive documentation and community support.
    - Trusted by Mozilla, Red Hat, Heroku and Eventbrite.

- Funding
- Requirements
- Installation 
    - Install ```pip install djangorestframework markdown django-filter```
    - Add `rest_framework` to `INSTALLED_APPS` in settings.py.
    - Add `path(api-auth/, include('rest_framework.urls'))`
- Project creation
    - Create a django project `django-admin startproject DRF .`
    - Add `rest_framework` to `INSTALLED_APPS` in settings.py.

- Example: using the given example in the homepage.
    - I'm not able to complete given example on homepage, I've got no idea how to run it.
    - Let's go ahead next, we'll figure this out with time.
    - Update I've fixed the issues in example but, I'm able to login but not able to get the users.

- Quickstart: getting started guide
- Development
- Support
- Security
- License

## Quickstart

Simple API to allow admin users to view and edit the users and groups in the system.

### Project setup
- Using given quickstart guide on website

curl -u sinku -H 'Accept: application/json; indent=4' http://127.0.0.1:8000/users/
Enter host password for user 'admin':
{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "url": "http://127.0.0.1:8000/users/1/",
            "username": "sinku",
            "email": "sudosinku@gmail.com",
            "groups": []
        }
    ]
}