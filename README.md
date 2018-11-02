# FlaskApp

Simple application with authentication and CRUD functionality using the Python Flask micro-framework

## Installation

To use this template, your computer needs:

- [Python 2 or 3](https://python.org)
- [Pip Package Manager](https://pypi.python.org/pypi)

### Setting up MySql DB

1. ### creat a Database 'myflaskapp':
   CREATE DATABASE `myflaskapp`;

2. ### create a users table:
   use myflaskapp;
   CREATE TABLE users(id INT(11) AUTO_INCREMENT PRIMARY KEY, name VARCHAR(100), email VARCHAR(100), username VARCHAR(30) ,password VARCHAR(100), register_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP);

3. ### create an article table:
   use myflaskapp;
   CREATE TABLE articles (id INT(11) AUTO_INCREMENT PRIMARY KEY, title VARCHAR(255), author VARCHAR(100), body TEXT, create_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP);

### Running the app

```bash
python app.py
```

