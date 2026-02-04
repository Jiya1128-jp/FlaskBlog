# Flask Blog Application

A full-stack blog web application built using Flask. The application supports user authentication, blog post management, and profile image uploads.

## Features
- User authentication (Register/Login/Logout)
- Create, edit, and delete blog posts
- Profile picture upload and resizing
- Form validation using Flask-WTF
- Secure password hashing using Bcrypt
- Database integration using SQLAlchemy

## Tech Stack
- Python
- Flask
- SQLAlchemy
- Flask-Login
- Flask-WTF
- Bootstrap
- SQLite
- Pillow

## Installation

Clone repository:
git clone <repo-link>

Navigate to project:
cd Blogpost

Create virtual environment:
python -m venv blogenv

Activate environment:
blogenv\Scripts\activate

Install dependencies:
pip install -r requirements.txt

## Run Application

python run.py

## Environment Variables

Create .env file and add:
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///site.db
