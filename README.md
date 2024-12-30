# Real-Time Chat System with Django

This is a real-time chat system built using **Django**, **Django Channels**, and **WebSockets** for asynchronous communication. It allows multiple users to chat in real-time with login/logout functionality and basic chat features.

## Features

- **Real-Time Messaging**: Uses WebSockets for instant message delivery.
- **User Authentication**: Secure login and logout functionality using Django's built-in authentication.
- **Responsive Design**: Optimized for both desktop and mobile browsers.
- **WebSocket Support**: Bidirectional communication between the client and server.

## Tech Stack

- **Django 5.1.4**: The web framework used to build the application.
- **Django Channels**: Extends Django to handle WebSockets and asynchronous communication.
- **WebSockets**: Enables real-time communication between the client and the server.
- **Daphne**: The ASGI server to handle asynchronous protocols like WebSockets.

## Requirements

- Python 3.6+
- Django 5.1.4
- Channels
- Daphne

## Installation

Follow these steps to set up the project locally:

### 1. Clone the repository:

git clone https://github.com/FuaaadNew/real-time-chat.git
cd real-time-chat

2. Set up a Virtual Environment (Recommended):
python3 -m venv venv
source venv/bin/activate  # On Windows use 'venv\Scripts\activate'

3. Install Dependencies:
pip install -r requirements.txt

4. Apply Migrations:
python manage.py makemigrations
python manage.py migrate

5. Create a Superuser (for admin access):
python manage.py createsuperuser

6. Run the Development Server:

python manage.py runserver

Access the application at http://127.0.0.1:8000/.










