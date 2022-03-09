# Overview
### Hotel Management System (HOTELMS)
Hotel Management System is a Django application that users can use to register, login and book rooms in a hotel.
It also has an admin dashboard for management of the users as well as a payment gateway and a messaging system for customers

### Technologies Used
Python - Codes were written in python to enhance HTML pages.
Django - Django is a high-level Python web framework  that provides a robust set of features for web applications. 
PostgreSQL - Postgres is an object-relational database management system (ORDBMS) with an emphasis on extensibility and standards compliance.

### How to Install and run the application
Clone the repository
Create a .env file from the example file .env.example
Ensure you have postgres installed on your local machine. You can check this by running postgres --version
Create a hotelms database on your local computer.
Create a virtual environment by running `virtualenv venv`
Run source venv/bin/activate to activate virtual environment for mac or venv\Scripts\activate.bat for windows
Run pip3 install -r requirements.txt
Run python3 manage.py runserver --settings=hotelms.settings.dev
