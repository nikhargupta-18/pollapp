# Polls Application

A Django web application for creating and voting on polls.

## Setup

1. Install Django:
   ```bash
   pip install django
   ```

2. Run migrations:
   ```bash
   python manage.py migrate
   ```

3. Create a superuser (optional):
   ```bash
   python manage.py createsuperuser
   ```

## Running

Start the development server:
```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/polls/` to view polls.

## Features

- View list of published polls
- View poll details and vote
- View poll results
- Admin interface for managing polls

## Project Structure

- `polls/` - Main application with models, views, and templates
- `mysite/` - Django project settings
- `db.sqlite3` - SQLite database

