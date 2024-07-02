# Admin Dashboard for CineGeek 2.0 Beta

Welcome to the admin dashboard for CineGeek 2.0 Beta. This dashboard provides control and management features for the movie and series streaming website. It is built using Flask for the backend and includes user authentication, database management, and a responsive frontend design.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Features

- **User Management**: Add, view, edit, and remove user accounts.
- **Content Management**: Manage movie and series data, including adding, editing, and deleting entries.
- **Database Access**: View and manage the SQLite database directly through the admin interface.
- **Authentication and Authorization**: Secure login using Flask-Login and Flask-WTF for managing administrative tasks.
- **Responsive Design**: Ensure usability across different devices with responsive web design.

---

## Tech Stack

- **Backend**: Flask, Flask-SQLAlchemy, Flask-Bcrypt, Flask-WTF, Flask-Login
- **Frontend**: HTML, CSS (with Bootstrap)
- **Database**: SQLite

---

## Installation

### Clone the repository

git clone https://github.com/your-username/CineGeek-Admin-Dashboard.git
cd CineGeek-Admin-Dashboard

## install dependencies

pip install -r requirements.txt

## Set up the database

Initialize the SQLite database:

from app import db
db.create_all()
exit()

## Usage
Running the application

python app.py

Open your web browser and go to http://localhost:5000 to view the admin dashboard.

### Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

### Fork the repository.

Create a new branch (git checkout -b feature/improvement).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/improvement).
Create a new Pull Request.

### License

This project is licensed under the MIT License. See the LICENSE file for details.

### Acknowledgements
This project was developed using Flask, a micro web framework for Python.
Bootstrap was used for styling the frontend.
Flask extensions such as Flask-SQLAlchemy, Flask-Bcrypt, Flask-WTF, and Flask-Login were instrumental in building this application.
