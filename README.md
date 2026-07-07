# Full Stack Social Media App

## Overview

A modern Full Stack Social Media Application built using **React + Vite** for the frontend and **Django + Django REST Framework** for the backend.

The application enables users to connect, share posts, interact through comments and likes, manage profiles, and securely authenticate using JWT.

---

## Features

### Authentication
- User Registration
- User Login
- JWT Authentication
- Secure Access Control
- Password Reset via Email (SMTP)

### Post Management
- Create Posts
- Update Posts
- Delete Posts
- Upload Images
- View Feed

### Social Interaction
- Like Posts
- Unlike Posts
- Comment on Posts
- Follow Users

### Profile Management
- Edit Profile
- Upload Profile Picture
- View User Profiles

---

## Tech Stack

### Frontend
- React.js
- Vite
- Axios
- Tailwind CSS

### Backend
- Django
- Django REST Framework
- JWT Authentication
- PostgreSQL / SQLite

### Deployment
- Vercel (Frontend)
- Render / Railway / Local Server (Backend)

---

# Project Structure

```bash
FullStack-Social-Media/
│
├── Backend/
│   ├── social/
│   └── api/
│
├── Frontend/
│   ├── src/
│   ├── public/
│   └── components/
│
├── README.md
└── .gitignore
```

---

# Installation Guide

## Backend Setup

### Clone Repository

```bash
git clone https://github.com/ashikabeed650/CodeAlpha-FullStack-Social-Media.git
```

### Navigate to Backend

```bash
cd Backend/social
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file:

```env
EMAIL_HOST_USER=your_email@gmail.com
EMAIL_HOST_PASSWORD=your_password
```

### Apply Migrations

```bash
python manage.py migrate
```

### Create Admin User

```bash
python manage.py createsuperuser
```

### Run Backend Server

```bash
python manage.py runserver
```

Backend URL

```text
http://127.0.0.1:8000/
```

---

# Frontend Setup

Navigate to frontend directory

```bash
cd Frontend
```

Install Packages

```bash
npm install
```

Create `.env`

```env
VITE_API_URL=http://127.0.0.1:8000
```

Start Frontend

```bash
npm run dev
```

Frontend URL

```text
http://localhost:5173/
```

---

# Screenshots

Add your project screenshots here.

Example:

- Login Page
- Home Feed
- Profile Page
- Comment Section

---

# Future Improvements

- Real-time Chat
- Notifications
- Stories Feature
- Dark Mode
- Reels Support
- Search Functionality

---

# Deployment

Frontend Deployment

```bash
npm run build
```

Deploy using:

- Vercel
- Netlify

Backend Deployment

- Render
- Railway
- AWS

---

# Contributors

**AshikAbeed**

GitHub

https://github.com/ashikabeed650

---

# License

This project was developed as part of the **CodeAlpha Internship Program**.

---

## Author

### AshikAbeed

Full Stack Developer

Made with ❤️ using React and Django
