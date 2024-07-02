# CineGeek 2.0 Beta

CineGeek 2.0 Beta is a movie and series streaming website that allows users to explore a vast collection of movies, search for specific titles, and get personalized recommendations based on their viewing preferences. This project is built using Flask for the backend and includes user authentication, database management, and a responsive frontend design.

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

- **Browse Movies**: Explore a vast collection of movies sorted by genre, release date, or popularity.
- **Search Functionality**: Easily find movies by title, director, or cast.
- **User Authentication**: Secure login and registration using Flask-Login and Flask-WTF.
- **Database Management**: Integration with SQLite via Flask-SQLAlchemy for storing user information securely.
- **Responsive Design**: Enjoy a seamless experience across devices with our responsive web design.

---

## Tech Stack

- **Backend**: Flask, Flask-SQLAlchemy, Flask-Bcrypt, Flask-WTF, Flask-Login
- **Frontend**: HTML, CSS (with Bootstrap)
- **Database**: SQLite

---

## Installation

### Clone the repository


git clone https://github.com/your-username/CineGeek-2.0-beta.git
cd CineGeek-2.0-beta
nstall dependencies
bash
Copy code
pip install -r requirements.txt
Set up the database
Initialize the SQLite database:
bash
Copy code
python
from app import db
db.create_all()
exit()
Usage
Running the application
bash
Copy code
python app.py
Open your web browser and go to http://localhost:5000 to view the application.

Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/improvement).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/improvement).
Create a new Pull Request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
This project was developed using Flask, a micro web framework for Python.
Bootstrap was used for styling the frontend.
Flask extensions such as Flask-SQLAlchemy, Flask-Bcrypt, Flask-WTF, and Flask-Login were instrumental in building this application.
