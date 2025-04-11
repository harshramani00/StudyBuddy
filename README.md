# 📚 StudyBuddy

*A Discord clone for studying — built with Django.*

StudyBuddy is a real-time web app designed to help students and learners create topic-based rooms where they can chat, collaborate, and share knowledge — just like Discord, but with a focus on productivity and education.

---

## 🚀 Features

- 🧑‍💻 User authentication (Register, Login, Logout)
- 📂 Create, join, and manage **study rooms**
- 📝 Topic-based room organization
- 💬 Real-time conversation threads
- 🔍 Search for rooms and messages
- 🧼 Edit/delete your messages and rooms
- ✨ Clean and modern UI inspired by Discord

---

## 🚰 Tech Stack

- **Backend**: Django, Django REST Framework
- **Frontend**: HTML, CSS (custom styling)
- **Database**: SQLite (can be switched to MySQL/PostgreSQL)
- **Other**: Python 3.11

---

## 🧪 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/StudyBuddy.git
cd StudyBuddy
```

### 2. Create a virtual environment and activate it

```bash
python -m venv env
env\Scripts\activate  # On Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a superuser (optional, for admin access)

```bash
python manage.py createsuperuser
```

### 6. Run the server

```bash
python manage.py runserver
```

Open your browser and go to `http://127.0.0.1:8000/` to start using the app!


---

## 🤝 Contributing

Pull requests are welcome! If you'd like to suggest improvements or new features, feel free to fork the repo and create a PR.

---
👨‍💻 Author

**Harsh Ramani**  
[GitHub](https://github.com/harshramani00)
