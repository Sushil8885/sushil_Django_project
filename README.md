### To create django project

```shell
# windows command
django-admin.exe startproject sushil
```

### project structure

```markdown

mini_Django_v1
    - venv
    - README.md
    - requirements.txt
    - sushil (project)
        - manage.py
        - sushil (project-settings)
            - __init__.py
            - asgi.py
            - settings.py
            - urls.py
            - wsgi.py


```

### django files

- `manage.py`:: this script helps us with management of site.It helps us
to start web server.

- `settings.py`:: contains configuration for the website
- `urls.py`:: this is a file for URL management
- `wsgi.py`:: deployment purpose
- `asgi.py`:: deployment purpose


## default database with django

- sqlite


## how to create tables associated with sub-applications?

- Django has pre-built sub-applications available in itself.
- We can create database tables using those apps by using following command.

```shell
cd <project-directory> # cd sushil
python manage.py migrate
```

- To run the application

```shell
python manage.py runserver
```