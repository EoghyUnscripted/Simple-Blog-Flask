# Simple Blog - Flask

## Overview

This is a project I worked on building during the 100 Days of Code with Python. It is built using Flask, Bootstrap, Python, Jinja, and other modules.

In the next update, I will be implementing RESTful API so that users can pull JSON data from the blog. Though not necessary, it will showcase my ability to create an API.

### Setup

1. Install [Flask](https://pypi.org/project/Flask/)
2. Install [Flask SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/quickstart/)
3. Install [SQLite Browser](https://sqlitebrowser.org/dl/)
4. Install [Flask Login](https://pypi.org/project/Flask-Login/)
5. Install [Flask Gravatar](https://pypi.org/project/Flask-Gravatar/)
6. Install [Flask CKEditor](https://pypi.org/project/Flask-CKEditor/)

### Comments

Please review permanent environment variables using the `decouple` module and how to create them for use in the app.

Additionally, you will need to modify the `SMTPLIB` section in `forms.py` and configure it to your email server settings.

For GMAIL users, you simply need to get your app key. All others will need to update the function to connect to your host.

### Additional Resources

- [Flask Documentation](https://flask.palletsprojects.com/en/2.1.x/) - Documentation for the Flask package
- [Flask SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/quickstart/) - Documentation for Flask SQLAlchemy
- [Flask SQLAlchemy - ORM, One-to-many](https://docs.sqlalchemy.org/en/14/orm/basic_relationships.html#one-to-many)
- [Flask Login](https://flask-login.readthedocs.io/en/latest/#configuring-your-application) - Documentation for the flask_login module
