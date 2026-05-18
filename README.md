# Django Portfolio Website

This is a personal **Portfolio Website** built with **Python Django**.

It includes:

- Home Page
- About Page
- Projects Page (Projects stored in Database)
- Project Details Page
- Contact Page (Messages stored in Database)
- Django Admin Panel (Add/Edit/Delete Projects)

---

## Requirements

Before starting, make sure you have installed:

- Python 3.10+ (Recommended: Python 3.12)
- pip (Python package manager)

---

## Project Setup Commands

### Step 1: Create Project Folder
```bash
# Create a new folder for the project
mkdir portfolio_project

# Go inside the project folder
cd portfolio_project
```

### Step 2: Create Virtual Environment
```bash
# Create virtual environment (venv)
python -m venv venv
```

### Step 3: Activate Virtual Environment
```bash
# Activate virtual environment (Windows)
venv\Scripts\activate
```

### Step 4: Install Django
```bash
# Install Django framework
pip install django
```

### Step 5: Create Django Project
```bash
# Create Django project named "portfolio"
django-admin startproject portfolio .
```

### Step 6: Create Main App
```bash
# Create Django app named "main"
python manage.py startapp main
```