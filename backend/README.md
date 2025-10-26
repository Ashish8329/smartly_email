# Backend - Django REST API

This is the backend server for the Smartly Email project.

## Setup Instructions

### 1. Activate Virtual Environment
```bash
source venv/bin/activate
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Migrations
```bash
python manage.py migrate
```

### 4. Create Superuser (Optional)
```bash
python manage.py createsuperuser
```

### 5. Run Server
```bash
python manage.py runserver
```

The server will start at `http://127.0.0.1:8000/`

## Project Structure

- `core/` - Main Django project settings
- `media/` - User uploaded files (images, documents, etc.)
- `staticfiles/` - Collected static files
- `venv/` - Virtual environment
- `requirements.txt` - Python dependencies

## APIs

- Admin Panel: http://127.0.0.1:8000/admin/
- Media Files: http://127.0.0.1:8000/media/

## Installed Packages

- **Django** - Web framework
- **Django REST Framework** - For building REST APIs
- **django-cors-headers** - CORS support for frontend

