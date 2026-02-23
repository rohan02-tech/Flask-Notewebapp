📝 Note Web App (Flask)

A simple and secure note-taking web application built using Flask.
Users can register, log in, and manage their personal notes with database support and session authentication.

🚀 Features

User Registration & Login

Secure Authentication (Session-based)

Create and Delete Notes

Database Integration using SQLAlchemy

Modular Flask Project Structure

Clean UI with Bootstrap

🏗 Project Structure
notewebapptutorial/
│
├── main.py
├── requirements.txt
├── website/
│   ├── __init__.py
│   ├── models.py
│   ├── auth.py
│   ├── views.py
│   ├── templates/
│   └── static/

🛠 Tech Stack

•Python
•Flask
•Flask-SQLAlchemy
•Flask-Login
•SQLite
•HTML / Bootstrap

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/notewebapptutorial.git
cd notewebapptutorial
2️⃣ Create Virtual Environment
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Application
python main.py

The app will run on:

http://127.0.0.1:5000/
🎯 Purpose of This Project

This project demonstrates:

Backend development with Flask

Authentication & session management

ORM-based database modeling

Clean and scalable project architecture

Deployment-ready configuration
