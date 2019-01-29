# socialnews

A social news discovery project to learn how to implement a GraphQL server for a Django application.

## Installation and Usage

Clone the project.

Create a virtual environment:

```bash
python3.6 -m venv venv
source venv/bin/activate
```

Install everything needed:

```bash
pip install -r requirements.txt
```

Create the database and run the server:

```
python socialnews/manage.py migrate
python socialnews/manage.py runserver
```

You should be able to access the server on [here](http://localhost:8000/graphql).

## Libraries

django-filter==2.0.0
django-graphql-jwt==0.1.5
graphene-django==2.2.0
