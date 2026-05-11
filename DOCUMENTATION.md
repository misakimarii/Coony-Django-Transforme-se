# Coony — Technical Documentation

## Overview

Coony is a social-sports platform built with Django, focused on community interaction, events, private chat, social engagement and personalized profiles.

The project was developed collaboratively during the Transforme-se/Senac program.

---

# Technologies

## Backend
- Python
- Django 5
- SQLite

## Frontend
- HTML5
- CSS3
- JavaScript

## Libraries & Tools
- django-user-agents
- Pillow
- CropperJS
- Google Fonts
- Material Symbols
- Boxicons

---

# Project Structure

```txt
coony/
│
├── coony/                 # Main Django settings
├── usuarios/              # Main application
│   ├── templates/         # HTML templates
│   ├── static/            # CSS, JS and assets
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   └── urls.py
│
├── media/                 # Uploaded files
├── requirements.txt
├── manage.py
└── README.md
```

---

# Main Features

## Authentication System
- Registration
- Login
- Session management
- Custom usernames

## Social Feed
- Create posts
- Like posts
- Comments
- Image uploads

## Events System
- Create events
- Favorite events
- Responsive dashboard
- Event cards

## User Profile
- Profile customization
- Avatar upload
- Bio and location
- Sports categories

## Real-time Chat
- Private conversations
- Message management
- User search
- Notifications

---

# Static Assets

Static files are located in:

```txt
usuarios/static/
```

Including:
- CSS stylesheets
- JavaScript files
- Fonts
- Icons
- Images

---

# Media Uploads

Uploaded files are stored in:

```txt
media/
```

Examples:
- User profile photos
- Post images
- Event covers

---

# Running Locally

## Install dependencies

```bash
py -m pip install -r requirements.txt
```

## Run server

```bash
py manage.py runserver
```

Server:

```txt
http://127.0.0.1:8000/
```

---

# Environment Variables

Supported environment variables:

```env
DJANGO_SECRET_KEY=
DJANGO_DEBUG=
DJANGO_ALLOWED_HOSTS=
DATABASE_URL=
```

---

# Responsive Interface

The platform includes:
- Desktop layout
- Mobile layout
- Dynamic navigation
- Adaptive dashboards

---

# Team Collaboration

Project developed collaboratively during the Transforme-se/Senac program.

## My participation
- Front-end development
- UI prototyping
- Interface creation
- Back-end support with Django

---

# Future Improvements

- REST API
- PostgreSQL support
- Real-time WebSockets
- Better notification system
- Advanced event filters
- Deployment optimization

---

# License

MIT License