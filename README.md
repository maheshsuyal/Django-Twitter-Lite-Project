# Django Twitter Lite 🐦

A lightweight Twitter-like web application built using **Django** where users can create, edit, delete, and search tweets. The project demonstrates core backend development concepts such as authentication, database management, and media handling.

---

## 🚀 Features

* User Registration and Login
* Create Tweets
* Edit Tweets
* Delete Tweets
* Search Tweets
* Image Upload Support
* User Authentication (Login / Logout)
* Media File Handling
* Clean UI using Django Templates

---

## 🛠 Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, Bootstrap
* **Database:** SQLite
* **Media Handling:** Django Media Files
* **Version Control:** Git & GitHub

---

## 📂 Project Structure

```
twitter_lite/
│
├── manage.py
├── db.sqlite3
├── twitter_lite/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── tweet/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   └── migrations/
│
├── templates/
├── static/
└── media/
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/twitter-lite.git
cd twitter-lite
```

### 2️⃣ Create Virtual Environment

```
python -m venv .venv
```

### 3️⃣ Activate Virtual Environment

Windows

```
.venv\Scripts\activate
```

Linux / Mac

```
source .venv/bin/activate
```

### 4️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 5️⃣ Run Migrations

```
python manage.py migrate
```

### 6️⃣ Start the Server

```
python manage.py runserver
```

Now open:

```
http://127.0.0.1:8000
```

---


---

## 📚 Learning Outcomes

* Django project structure
* CRUD operations
* Authentication system
* Media file handling
* Search functionality
* GitHub project management

---

## 👨‍💻 Author

Mahesh Suyal
Computer Science Engineering Student
MLSU Udaipur
