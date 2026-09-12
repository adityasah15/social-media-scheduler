# 📱 Social Media Scheduler

[![Python](https://img.shields.io/badge/python-3.11.9-blue)]()
[![Status](https://img.shields.io/badge/status-Archived-red)]()
[![License](https://img.shields.io/badge/license-MIT-orange)]()

> **📢 Public Archive:** This project has been archived and is no longer actively maintained.

A Python-based web application designed to help draft, edit, and schedule posts across multiple social media platforms. Building this project helped develop practical skills in backend web development, template routing, and cloud deployment configurations.

---

## 📁 Features & Structure

### 1️⃣ 📅 Dashboard & Scheduling
A central interface to manage social media workflows.
- View all queued posts (`index.html`).
- Dedicated interface for creating new scheduled content (`schedule.html`).

### 2️⃣ ✏️ Content Management
- Edit existing drafts or modify scheduled posts before they go live (`edit.html`).
- Dynamic frontend built on a reusable layout (`base.html`).

### 3️⃣ 🌍 Multi-Platform Assets
Built-in visual support and preparation for major networks:
- Facebook
- Instagram
- LinkedIn
- Twitter

### 4️⃣ 🚀 Production-Ready Configuration
Configured for seamless cloud deployment.
- Includes a `Procfile` utilizing Gunicorn as the WSGI server.
- Automated static workflows via GitHub Actions (`.github/workflows/static.yml`).

---

## 📚 Technologies & Skills Used

### 💡 Backend Development
- **Python 3.11.9**: Core application logic defined in `app.py`.
- **Web Routing**: Serving dynamic HTML templates and handling HTTP requests.
- **Gunicorn**: Production WSGI server setup.

### 🎨 Frontend
- **HTML5 / CSS3**: Custom styling (`static/style.css`) and structured views.
- **Templating**: Modular frontend design using base templates to avoid code repetition.

### ⚙️ DevOps & Environment
- **GitHub Actions**: Automated workflows.
- **Environment Management**: Dependency tracking via `requirements.txt` and explicit runtime targeting (`runtime.txt`).

---

## ▶️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd social-media-scheduler-main
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python app.py
   ```
   *(Alternatively, test the production server setup: `gunicorn app:app`)*

---

## 👤 Author

**Aditya Sah**
💻 GitHub | 📫 LinkedIn 

---

📜 **License**: MIT — free to use, modify, and share.
