🚀 Django + MySQL + Nginx (Dockerized)

A minimal production-style Django setup using:

🐍 Django (Gunicorn)

🗄 MySQL

🌐 Nginx (Reverse Proxy)

🐳 Docker & Docker Compose

This project focuses on container orchestration and infrastructure setup, not complex application logic

Browser
   ↓
Nginx (Port 80)
   ↓
Django (Gunicorn :8000)
   ↓
MySQL (Database)


django-basic-app/
│
├── app/                 # Django application
│   ├── Dockerfile
│   ├── manage.py
│   └── project/
│
├── nginx/
│   ├── Dockerfile
│   └── nginx.conf
│
├── docker-compose.yml
└── README.md
