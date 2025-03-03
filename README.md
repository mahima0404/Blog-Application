# Blog Application

This is a simple blog application built using Python Django, HTML, and CSS. It allows users to create, edit, and delete blog posts with a clean and responsive UI.

## Features

- User authentication (Login/Logout/Register)
- Create, read, update, and delete (CRUD) blog posts
- User-friendly interface with HTML & CSS
- Django-based backend
- SQLite database (default, can be switched to PostgreSQL or MySQL)

## Tech Stack

- **Backend**: Django
- **Frontend**: HTML, CSS
- **Database**: SQLite (default), can be changed to PostgreSQL/MySQL

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/blog-app.git
cd blog-app
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply Migrations
```bash
python manage.py migrate
```

### 5. Create a Superuser (Admin)
```bash
python manage.py createsuperuser
```
Follow the prompts to create an admin account.

### 6. Run the Development Server
```bash
python manage.py runserver
```

### 7. Open in Browser
Go to `http://127.0.0.1:8000/` in your browser.

## Usage

1. Register a new account or log in.
2. Create and publish blog posts.
3. Edit or delete posts as needed.

## Folder Structure
```
blog-app/
│-- blog/              # Blog application
│-- static/            # Static files (CSS, JS, images)
│-- templates/         # HTML templates
│-- users/             # User authentication
│-- manage.py          # Django project manager
│-- db.sqlite3         # Default database
│-- requirements.txt   # Dependencies
│-- README.md          # Documentation
```

## Contributing
Pull requests are welcome. Please open an issue first to discuss major changes.

## License
This project is open-source and available under the [MIT License](LICENSE).

