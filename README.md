# ☕ Django Cafe Management System (CMS)

**My First Django Project**

The Cafe Management System (CMS) is a  web-based application designed to simplify café operations. It allows customers to browse the menu, place orders, and pay online, while the staff and manager can handle the backend operations efficiently through an admin dashboard. This system offers a modern, responsive design compatible with mobile, tablet, and desktop devices.

## 🖥️ Website Overview
The website includes the following pages:
- 🏠 **Home**
  
  Welcome page with café introduction and highlights
  
- ℹ️ **About**
  
  Information about the café and services
  
- 👩‍🍳 **Our Team**
  
  Meet the staff and management team
- 🍽️ **Menu**
  
  Browse the café’s menu with item descriptions and prices
- 📞 **Contact**
  
  Contact form and café location details
- 🔐 **Login / Register**
  
  For customers and staff authentication
- 💳 **Customers can order and pay online directly from the website.**
- 🧾 **Managers and staff can view, manage, and orders created during the day.**


## ✨ Features
- 🧾 Take and manage customer orders
- 💳 Online ordering and payment support
- 💾 Save orders directly to the database
- 📅 View daily order reports
- 📱 Fully responsive layout for all screen sizes


## 🧰 Technologies Used
- Frontend:	HTML5, CSS3, JavaScript, Bootstrap 5
- Backend:	Django (Python), Django PayPal
- Database:	SQLite (default)
- Version Control:	Git & GitHub


## ⚙️ Project Setup

1. Clone the Repository
- git clone https://github.com/shwetaravnak/Cafe-Management-System.git
  
  cd Cafe-Management-System

2. Create and Activate a Virtual Environment
- Using venv:

  python -m venv venv
  
  venv\Scripts\activate     

3. Install Dependencies
- pip install -r requirements.txt

4. Database Setup
- Run the following commands to apply migrations:
  
  python manage.py makemigrations
  
  python manage.py migrate

5. Create a Superuser
- python manage.py createsuperuser

6. Run the Server
- python manage.py runserver

Then visit: 👉 http://127.0.0.1:8000/

🔐 For Admin Panel:
Visit: http://127.0.0.1:8000/admin/
Login with your superuser credentials.

