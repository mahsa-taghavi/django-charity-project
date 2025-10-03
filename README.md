# Django Charity Project

A Django project for managing user accounts, charities, and the "About Us" section.

## 🚀 Features
- User authentication with a Custom User Model
- API built using Django REST Framework
- Charity management (add, edit, delete)
- Static pages (About Us)
- Modular structure with apps: `accounts`, `charities`, `about_us`

## 📦 Installation & Running

### 1. Clone the repository
```bash
git clone https://github.com/your-username/charity-project.git
cd charity-project/django_project
Create a virtual environment:
python -m venv venv
# Linux/Mac
source venv/bin/activate
# Windows
venv\Scripts\activate
Install dependencies:
pip install -r requirements.txt
Set environment variables:
Create a .env file and add the following (you can use .env.example as a template):
DJANGO_SECRET_KEY=your-secret-key
DJANGO_DEBUG=True
DJANGO_ALLOWED_HOSTS=localhost,127.0.0.1
Apply migrations:
python manage.py migrate
Run the development server:
python manage.py runserver
🛠 Project Structure:
django_project/
│── accounts/       # User management
│── charities/      # Charity management
│── about_us/       # About Us page
│── charity/        # Main project settings
│── manage.py
│── requirements.txt
│── .gitignore
│── .env.example
│── README.md
🧪 Running Tests:
python manage.py test
📄 License:
This project is licensed under the MIT License.