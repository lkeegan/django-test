# django-test

Playground for trying out django.

django-test is the "django project", polls is a "django app".

## quickstart

- clone: `gh repo clone django-test`
- create conda env: `micromambda create -f env.yml`
- activate: `micromamba activate django-test`
- run migrations (update database): `python manage.py migrate`
- create a superuser: `python manage.py createsuperuser`
- start dev server: `python manage.py runserver`

## notes

To update the database schema
- modify the models in `polls/models.py`
- run `python manage.py makemigrations polls` to create migrations for those changes
- run `python manage.py migrate` to apply those changes to the database