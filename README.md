# Music Player - Django

This is a simple music player application built using the Django framework. The application allows users to browse, play, and manage their music library.

## Features
- User authentication (sign up, login, and logout)
- Upload and manage music files
- Browse music by categories or playlists
- Play music with a built-in player
- Responsive design for web and mobile devices

## Technologies Used
- **Backend**: Django, Django REST Framework
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default), but can be configured for other databases
- **Others**: Bootstrap for styling

## Installation

### Prerequisites
- Python 3.x installed on your system
- `pip` (Python package manager)
- Django installed

### Steps
1. Clone the repository:
```sh
   git clone https://github.com/naveeneee48/musicPlayer-django.git
   cd musicPlayer-django
```
2. Create and activate virtual environment
```sh
python3 -m venv env
source env/bin/activate
```
3. Install the required dependencies:
```sh
pip3 install django
pip3 install pillow
```
4.create super user account

```sh
python3 manage.py createsuperuser

Username (leave blank to use 'naveen'): naveen <your username>
Email address: naveeneee48@gmail.com <give your mail id>
Password: 
Password (again): 

Bypass password validation and create user anyway? [y/N]: y
you can check  http://127.0.0.1:8000/admin

Superuser created successfully.
```
5. start the development server:
```sh
python3 manage.py runserver
```
The server will start, and you can access the application at **http://127.0.0.1:8000**.

## Usage
- Register an account or log in with existing credentials.
- Upload your music files and create playlists.
- Browse and play music from your library.
