# Admin Dashboard for CineGeek 2.0 Beta

![Python](https://img.shields.io/badge/Language-Python-blue)
![Flask](https://img.shields.io/badge/Framework-Flask-lightgrey)
![Flask-SQLAlchemy](https://img.shields.io/badge/ORM-Flask--SQLAlchemy-4B8BBE)
![Flask-Bcrypt](https://img.shields.io/badge/Security-Flask--Bcrypt-green)
![Flask-WTF](https://img.shields.io/badge/Forms-Flask--WTF-FF69B4)
![Flask-Login](https://img.shields.io/badge/Auth-Flask--Login-yellow)
![Bootstrap](https://img.shields.io/badge/Frontend-Bootstrap-purple)
![SQLite](https://img.shields.io/badge/Database-SQLite-blueviolet)

> **Developed by Alan Cyril Sunny**  
> If you find this project helpful, please consider ⭐ [starring the repository](https://github.com/dragonpilee/CineGeek-Admin-Dashboard)!

---

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## 🚀 Features

- 👤 **User Management**: Add, view, edit, and remove user accounts.
- 🎬 **Content Management**: Manage movie and series data, including adding, editing, and deleting entries.
- 🗄️ **Database Access**: View and manage the SQLite database directly through the admin interface.
- 🔒 **Authentication and Authorization**: Secure login using Flask-Login and Flask-WTF for managing administrative tasks.
- 📱 **Responsive Design**: Ensure usability across different devices with responsive web design.

---

## 🧰 Tech Stack

- **Backend**: Flask, Flask-SQLAlchemy, Flask-Bcrypt, Flask-WTF, Flask-Login
- **Frontend**: HTML, CSS (with Bootstrap)
- **Database**: SQLite

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/dragonpilee/CineGeek-Admin-Dashboard.git
   cd CineGeek-Admin-Dashboard
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up the database**
   ```python
   # In Python shell
   from app import db
   db.create_all()
   exit()
   ```

---

## 🕹️ Usage

1. **Run the application**
   ```bash
   python app.py
   ```
2. Open your web browser and go to [http://localhost:5000](http://localhost:5000) to view the admin dashboard.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. **Fork the repository**
2. Create a new branch  
   ```bash
   git checkout -b feature/improvement
   ```
3. Make your changes.
4. Commit your changes  
   ```bash
   git commit -am 'Add new feature'
   ```
5. Push to the branch  
   ```bash
   git push origin feature/improvement
   ```
6. Create a new Pull Request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- Flask, a micro web framework for Python
- Bootstrap for frontend styling
- Flask extensions: Flask-SQLAlchemy, Flask-Bcrypt, Flask-WTF, Flask-Login

---

For more information, updates, and documentation, visit the  
👉 [GitHub Repository](https://github.com/dragonpilee/CineGeek-Admin-Dashboard)

Feel free to fork, star ⭐, and contribute!
