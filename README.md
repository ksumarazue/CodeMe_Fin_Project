This is a simple online ordering platform built using Flask, a lightweight web framework in Python, along with SQLite for the database.


Features
User registration and authentication
Different user roles: admin, client, and employee
Creating, viewing, updating, and deleting orders
Order status tracking

Installation
Clone the repository:

git clone https://github.com/ksumarazue/CodeMe_Fin_Project.git
Navigate to the project directory:

cd online-ordering-platform
Install dependencies:

pip install -r requirements.txt

Before starting the application for the first time, you must create an admin account. To do this, first run:
python create_admin.py

This operation will create the user 'admin' with the password 'admin_password'

Run the application:
python run.py
