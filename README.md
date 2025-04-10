# 🌐 Social Media Clone Project (Django)

A feature-rich Social Media Clone Project built using Django.

This project replicates core functionalities of popular social media platforms, including user authentication, posting content, following users, and interacting with posts.



## 🚀 Features

🔑 User Registration & Authentication (Login/Logout)



📝 Create, Edit, Delete posts



🖼️ Upload images with posts



💬 Like and Comment on posts



🧑‍🤝‍🧑 Follow / Unfollow users



🌐 Admin panel for content management



📁 Media file handling (Django media settings)



## 🛠️ Tech Stack

Backend: Django, Python



Database: SQLite (default), can be switched to PostgreSQL



Frontend: Django Templates, Bootstrap



Media Storage: Local (can be upgraded to AWS S3/Cloudinary)



Authentication: Django's built-in auth system



## 📂 Project Structure



/social_media_project

│── manage.py

│── /social_media_app

│     │── models.py

│     │── views.py

│     │── urls.py

│     │── templates/

│     │── static/

│     │── forms.py

│── /social_media_project

│     │── settings.py

│     │── urls.py

│     │── wsgi.py

│── /media

│── requirements.txt

│── README.md

## ⚙️ Installation

### 1️⃣ Clone the repository



git clone https://github.com/abhinav744/Social_Media_CloneProject.git

cd Social_Media_CloneProject

### 2️⃣ Set up virtual environment


python -m venv venv

source venv/bin/activate  # On Windows use `venv\Scripts\activate`

### 3️⃣ Install dependencies



pip install -r requirements.txt

### 4️⃣ Apply migrations



python manage.py makemigrations

python manage.py migrate

### 5️⃣ Create superuser (for admin access)


python manage.py createsuperuser

### 6️⃣ Run the development server



python manage.py runserver

Access the project at: http://127.0.0.1:8000



## 🧩 Features Breakdown

Feature	Description

Authentication	Login, Register, Logout using Django auth

User Profiles	Profile pages with user info and posts

Posting	Create, edit, delete, and view posts

Likes & Comments	Engage with posts

Follow System	Follow and unfollow other users

Admin Panel	Manage users and posts

## 📦 Requirements

Python 3.x

Django 4.x

Pillow (for image handling)

## 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository and submit a pull request.



