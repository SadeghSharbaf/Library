# Library Management System

A Django-based library/book-store web application. The repository includes the Django project, application code, templates, and asynchronous-task scheduling artifacts.

## Tech Stack
- Python and Django
- Celery (scheduled/background tasks)

## Getting Started
1. Create and activate a virtual environment.
2. Install the project dependencies from the repository's dependency file, if present.
3. Configure environment variables and database settings for your local environment.
4. Apply migrations and create an admin user:
   ```bash
   python manage.py migrate
   python manage.py createsuperuser
   python manage.py runserver
   ```

## Database
The local SQLite database is intentionally not committed. Run migrations to create a fresh local database.

## Notes
Do not commit secrets, local databases, virtual environments, editor settings, or generated Celery schedule files.
