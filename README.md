# Blogicum: A Simple Django Blogging App

## Description

Blogicum is a simple blogging application built with Django. It allows users to view a list of blog posts, view individual posts, and filter posts by category.

## Installation

1. **Clone the repository:**
   ```bash
   https://github.com/srv328/django-sprint.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd blogicum
   ```

3. **Create a virtual environment:**
   ```bash
   python3 -m venv venv
   ```

4. **Activate the virtual environment:**
   ```bash
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```

5. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

6. **Apply database migrations:**
   ```bash
   python manage.py migrate
   ```

## Running the Development Server

1. **Start the development server:**
   ```bash
   python manage.py runserver
   ```

2. **Open your browser and visit `http://127.0.0.1:8000/` to access the application.**
