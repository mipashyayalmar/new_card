# Card Generator — Django

This repository contains a Django application with `manage.py` configured to load `CardGenerator.settings`.

## Local setup

Clone the repository and change into its project directory. Create and activate a virtual environment:

```bash
python -m venv .venv
```

Install the dependencies required by the repository, using `pip install -r requirements.txt` where available. Check settings for database and environment configuration, then run:

```bash
python manage.py migrate
python manage.py runserver
```

## Development notes

Inspect the project's URL configuration, views, models, and templates for implemented functionality. These instructions were prepared from the Django entry point and are not a claim that the application has been run or all functionality verified. Do not commit secrets or user data.
