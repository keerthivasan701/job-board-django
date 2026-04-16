💼 Job Board Web Application

A full-stack Job Board Web Application built with Django, allowing employers to post jobs and job seekers to search and apply for jobs.
Designed with a clean UI, secure authentication, and deployed on Render.

🔗 Live Demo:
http://127.0.0.1:8000/

🚀 Features

User authentication (Login & Register)
Employer & Job Seeker role-based access
Company creation and management
Job posting and job listing
Job search and browsing
Job application workflow
Django Admin dashboard
Secure forms with CSRF protection
Responsive UI with HTML & CSS



🛠️ Tech Stack

Backend
Django (Python Web Framework)
Django ORM
Frontend
HTML5
CSS3
Bootstrap
Database
SQLite (Development)
PostgreSQL (Production – Render)
Authentication
Django Authentication System
Deployment
Render (Web Service Hosting)
Gunicorn (WSGI Server)



📂 Project Structure

django-job-board/
├── accounts/        # User authentication & roles
├── companies/       # Company & job posting logic
├── applications/    # Job application handling
├── templates/       # HTML templates
├── static/          # CSS & static files
├── config/          # Project settings & URLs
├── manage.py
└── requirements.txt




⚙️ Installation & Setup (Local)
1️⃣ Clone the repository
git clone https://github.com/Mathanraj-d12/django-job-board.git
cd django-job-board

2️⃣ Create virtual environment
python -m venv .venv

Activate virtual environment

Windows

.venv\Scripts\activate


Mac / Linux

source .venv/bin/activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run migrations
python manage.py migrate

5️⃣ Start development server
python manage.py runserver

📝 Deployment Note

This project is hosted on Render (Free Tier).
If the application is inactive for some time, it may show “Render application loading” due to cold start.
This is a hosting limitation, not a project issue.

📌 Resume Description

Developed a Job Board Web Application using Django with role-based authentication, job posting, job search, and application management features. Deployed on Render with a production-ready configuration.

👨‍💻 Author

Keerthi Vasan
GitHub: https://github.com/eerthivasan701

Live Demo: http://127.0.0.1:8000/
GitHub: (repo link)
