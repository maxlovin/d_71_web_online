📝 Flask Driven RESTful Blog Web Application

A full-stack, responsive blog application built with Python and Flask. Features full CRUD functionality (Create, Read, Update, Delete) for blog posts, persistent SQLite storage using Flask-SQLAlchemy, rich text editing via CKEditor, and WTF forms styled with Bootstrap 5.


📌 Features

  Full CRUD Functionality: Create new blog posts, display individual post pages, update existing content, and delete unwanted entries.
  Rich Text Editing: Integrated CKEditor field allowing styled blog body creation and formatting.
  Form Validation & Security: Built using Flask-WTF with server-side validation rules (URL validation, required fields, and CSRF protection).
  Database ORM: Modern SQLAlchemy 2.0 implementation using DeclarativeBase and type-annotated mapped columns with SQLite storage.
  Responsive Styling: Powered by `bootstrap-flask` for clean UI components and layout rendering.


🛠️ Prerequisites & Setup

1. Requirements
Python 3.8+ installed.

3. Installation

Clone the repository and set up a virtual environment:

bash
git clone [https://github.com/your-username/flask-blog-app.git](https://github.com/your-username/flask-blog-app.git)
cd flask-blog-app

Create virtual environment
python -m venv venv

Activate environment (Linux/macOS)
source venv/bin/activate
On Windows use: venv\Scripts\activate

Install dependencies
pip install flask bootstrap-flask flask-sqlalchemy flask-wtf flask-ckeditor wtforms
