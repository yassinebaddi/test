# DONE: A To-Do List Web Application

## Video Demo
[Watch the demo here](https://streamable.com/71qga6)

- Video recording date: 10/2/2024
- My project title: ToDo List
- My name: Yassine Baddi 
- My name on GitHub and edX: yassine baddi
- My city and country: Rabat Morocco

## About the Project
Welcome to **DONE**, my final project for CS50x! This web application aims to help users manage their daily tasks and errands efficiently. We all have moments when we forget to complete simple chores—like putting sheets back on the bed or booking a trip. Often, all it takes to stay on track is a simple to-do list.

The primary goal of DONE is to prioritize and organize tasks effectively. By listing everything that needs to be done, even the smallest tasks become manageable. If a task can be completed in just a minute, it deserves a spot on your to-do list.

### Key Features
- **User Registration**: Mandatory for accessing application functionalities.
- **Password Management**: Users can change their passwords by providing the current one.
- **Add Tasks**: Easily append new items to your to-do list.
- **Edit Tasks**: Modify existing items after adding them to the list.
- **Mark as Done**: Remove completed items from your list.

## Prerequisites
To run this project, ensure you have the following installed:

### Installation Instructions
Follow these steps to get the project up and running:

```bash
# Instructions are for Debian/Ubuntu Operating Systems

$ sudo apt update && sudo apt upgrade
# Updates the system packages

$ sudo apt-get install python3 python3-dev
# Installs the latest version of Python 3

$ sudo apt-get install python3-pip
# Installs PIP for Python package management

$ pip3 install Flask
# Installs Flask framework

$ pip3 install Flask-Session
# Installs Flask-Session for server-side session management

$ sudo apt install sqlite3
# Installs SQLite3 database

$ pip3 install cs50
# Installs CS50 library for Python

$ sudo pip3 install style50
# Installs style50 for Python

$ sudo apt-get install astyle
# Installs Artistic Style for code formatting

$ sudo pip install --upgrade style50
# Upgrades style50 to the latest version

<br/>
```

### Recommended Tools
- [Visual Studio Code Download](https://code.visualstudio.com/#alt-downloads)
- [Visual Studio Code Documentation](https://code.visualstudio.com/docs)

<br/>


# Project Structure

Here’s a succinct breakdown of the project files:

    - [style.css](project/static/styles.css) - CSS file defining the look-and-feel of each web page, i.e., each HTML file
- ["templates" directory](templates) - contains only HTML documents
    - [edit.html](templates/edit.html) - web page where users modify their tasks on the To-Do list
    - [error.html](templates/error.html) - displays the image and the text of an error which caused them to be redirected to this page
    - [index.html](templates/index.html) - "homepage"
    - [layout.html](templates/layout.html) - skeletal structure of the web page, in order to keep the code in the DRY principle
    - [login.html](templates/login.html) - users input their username and password
    - [password_change.html](templates/password_change.html) - allows the users to change their password
    - [register.html](templates/register.html) - page containing username field, and two password fields, so that users can confirm their password
    - [todo.html](templates/todo.html) - the web page where most of the web application functionalities happen, e.g. add to the list, remove from it, edit the items on the list
- [app.py](app.py) - Python code making all of the functionalities happen
- [done.db](done.db) - Relational database containing tables of users, and their To-Do lists
- [helpers.py](helper.py) - Ensures that user is logged in and checks for errors


## How to Start the Project

Follow these steps to get the project up and running:

1. **Download the project files.**
2. **Extract the files.**
3. **Open the project in Visual Studio Code (or your preferred IDE).**
4. **Open a terminal and navigate to the project directory:**
    ```bash
    cd project
    ```
5. **Run the application:**
    ```bash
    python app.py
    flask run
    ```
6. **Access the application** at [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your web browser.


