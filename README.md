# Django Feedback API

A simple Django REST API to collect and manage feedback.

## Features

- Submit feedback (POST)
- List all feedback (GET)
- Retrieve single feedback by ID (GET)
- Delete feedback (DELETE)

## How to Run

```
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

## Endpoints

- `POST /api/feedback/`
- `GET /api/feedback/`
- `GET /api/feedback/<id>/`
- `DELETE /api/feedback/<id>/`