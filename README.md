# 🎓 College Management System

A full-fledged **Django-based web application** designed to manage various operations of a college including student records, faculty data, course management, and more.

---

## 📌 Features

- Student Registration and Management  
- Faculty Information Handling  
- Course and Subject Assignment  
- Admin Login and Dashboard  
- User-Friendly Interface  
- CRUD Operations for all major modules

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Django (Python)  
- **Database**: SQLite (default Django DB)  
- **Hosting/Authentication (optional)**: Firebase  
- **Other Tools**: Git, GitHub

---

## 📁 Folder Structure

CollegeManagement-Django/
│
├── collegeapp/ # Core application (models, views, urls)
├── templates/ # HTML templates
├── static/ # Static files (CSS, JS)
├── db.sqlite3 # Database
├── manage.py # Django management script
└── requirements.txt # Python dependencies (optional)

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x installed
- `pip` for installing packages
- Virtual environment setup (recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/Ramya-SB-05/College-Management-System.git
cd College-Management-System

# Set up virtual environment
python -m venv venv
source venv/bin/activate    # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create superuser (for admin access)
python manage.py createsuperuser

# Run server
python manage.py runserver

Then open your browser and go to:
http://127.0.0.1:8000/


