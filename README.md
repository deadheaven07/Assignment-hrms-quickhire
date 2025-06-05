# Assignment-hrms-sniperthink

A full-stack HRMS assignment project with Django (PostgreSQL) backend and Vite + React frontend. Backend is connected to AWS RDS PostgreSQL and deployed on an EC2 instance.

---

## 🛠️ Tech Stack

### Backend
- Python 3.x
- Django
- PostgreSQL (migrated from SQLite)
- AWS RDS PostgreSQL

### Frontend
- React + Vite
- Tailwind CSS

### Deployment
- EC2 (Amazon Linux 2023)
- AWS RDS (PostgreSQL)
- GitHub for source control

---

## 🚀 Features

- Employee management (Excel upload)
- Salary, Attendance, and Revenue tracking
- RESTful backend API
- Frontend UI dashboard
- Connected to AWS-hosted PostgreSQL database

---

## ⚙️ Backend Setup

```bash
# 1. Clone the repo
git clone https://github.com/deadheaven07/Assignment-hrms-quickhire.git
cd Assignment-hrms-quickhire/backend

# 2. Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Update settings.py with AWS RDS PostgreSQL credentials

# 5. Run migrations
python manage.py migrate

# 6. Start server
python manage.py runserver 0.0.0.0:8000
