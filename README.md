# 🐦 ChirpStack - Tweet Manager with Django

ChirpStack is a simple tweet management app built with **Django**, inspired by the [Chai aur Code](https://github.com/hiteshchoudhary) tutorials on YouTube and GitHub.

This project lets users **create, view, edit, and delete tweets** — a great way to understand Django’s core components like models, views, URL routing, and templates.

---

## 📸 Preview

> 🛠 Live preview not available (development only)

---

## 📦 Features

- 📝 Create and list tweets
- ✏️ Edit tweets
- ❌ Delete tweets
- 📅 Timestamped tweets (with `created_at`)
- 🎨 HTML templates using Django's template engine

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/tryadav1176/chirpstack.git
cd chirpstack

```
### 2. Setup the Environment

```bash
python -m venv .venv
source .venv/Scripts/activate  # Windows
# OR
source .venv/bin/activate      # macOS/Linux
```
### 3. Install dependencies
```bash
pip install -r requirements.txt
```
### 4. Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
### 5. Run the development server
```bash
python manage.py runserver
```
Visit: http://127.0.0.1:8000/tweet/

📚 Credit
This project is heavily inspired by Chai aur Code — check out their content for more Django and Python tutorials!


