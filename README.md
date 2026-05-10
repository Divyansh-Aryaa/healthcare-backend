# Healthcare Backend API
![Django](https://img.shields.io/badge/Django-5.2-green?logo=django)
![DRF](https://img.shields.io/badge/DRF-3.x-red)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql)
![JWT](https://img.shields.io/badge/Auth-JWT-black)
![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Tech Stack
- Django
- Django REST Framework
- PostgreSQL
- JWT Authentication

## Features
- User Registration & Login (JWT)
- Patient Management (CRUD)
- Doctor Management (CRUD)
- Patient-Doctor Mapping

## Setup Instructions

```bash
git clone <repo>
cd healthcare_backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
## Create .env file:

```bash
SECRET_KEY=your_secret
DEBUG=True

DB_NAME=healthcare_db
DB_USER=healthcare_user
DB_PASSWORD=password123
DB_HOST=localhost
DB_PORT=5432
```

## Run commands

```bash
python manage.py migrate
python manage.py runserver
```
## API Endpoints

- /api/auth/register/
- /api/auth/login/
- /api/patients/
- /api/doctors/
- /api/mappings/

## Add requirements.txt

```bash
pip freeze > requirements.txt
```
