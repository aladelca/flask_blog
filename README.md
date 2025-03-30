# Flask Blog

A simple blog application built with Flask as part of the API Developer course at Cibertec.

## Overview

This application demonstrates fundamental concepts of web development with Flask, SQLite, and basic HTML templates. It serves as a teaching tool for students learning API development and web application fundamentals.

## Features

- Create, read, update, and delete blog posts
- Responsive design using Bootstrap
- SQLite database for data persistence
- Flash messages for user feedback

## Project Structure

```
flask_blog/
│
├── app.py              # Main application file with all routes and logic
├── database.db         # SQLite database file
├── init_db.py          # Script to initialize the database
├── schema.sql          # SQL schema for database setup
│
├── static/             # Static files
│   └── css/
│       └── style.css   # Custom CSS styles
│
└── templates/          # HTML templates
    ├── base.html       # Base template with common structure
    ├── create.html     # Form for creating new posts
    ├── edit.html       # Form for editing existing posts
    ├── index.html      # Home page listing all posts
    └── post.html       # Individual post view
```

## Installation and Setup

1. Clone this repository
2. Create a virtual environment:
   ```
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
3. Install dependencies:
   ```
   pip install flask
   ```
4. Initialize the database:
   ```
   python init_db.py
   ```
5. Run the application:
   ```
   python app.py
   ```
6. Open your browser and navigate to http://127.0.0.1:5000/

## Learning Objectives

This project is designed to teach:
- Flask application structure and routing
- Database operations with SQLite
- Template inheritance with Jinja2
- CRUD operations in a web application
- RESTful API concepts
- Form handling and validation
- Flash messaging for user feedback

## About This Course

This repository is part of the API Developer course taught at Cibertec. As the instructor of this course, I've designed this application to demonstrate practical web development concepts and serve as a foundation for students to build upon.

## License

This project is open-source and available for educational purposes.

## Contact

For questions related to the course, please contact @aladelca. 