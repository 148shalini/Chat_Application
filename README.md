CHAT APPLICATION (BY React.Js and Django)

Overview:

This is a simple chat application with a frontend built using React.js and a backend powered by Django. The application allows users to send and receive messages in real-time.

Prerequisites and Dependencies

Backend

Python 3.8+
Django 4.2
Django Channels
daphne
SQLITE (or any other database supported by Django)

Frontend

Node.js 14.x+
React 18.x
React Router
WebSocket library (e.g., stompjs or native WebSocket API)

Installation

FRONT-END

Clone the Repo FRONT-END

git clone https://github.com/148shalini/Chat_Application.git

1.Move to the Frontend Directory

cd my-frontend

2.Install Dependencies

npm install

3.Start the Development Server

npm start

Server run at http://localhost:3000.

BACK-END

1.Move to the Backend Directory

cd chat_backend

cd interest_app_backend

2 Create and Activate a Virtual Environment

python -m venv venv

venv\Scripts\activate

3.Install Dependencies

pip install -r requirements.txt

4.Apply Migrations

python manage.py makemigrations

python manage.py migrate

5.Run Backend Server 

daphne -b 0.0.0.0 -p 8000 interest_app_backend.asgi:application

 Running the Application

 Account Registration and Login

**Register**: Sign up for a new account using your mobile number and password.
**Login**: Access your account with the registered mobile number and password.

 User Interaction

**Browse Users**: After logging in, view a list of users to whom you can send interest messages.
**Send Interest**: Initiate contact by sending an interest message to other users.
**Manage Interests**: Review received interest messages and choose to accept or reject them.

 Chat Functionality

**Start Chatting**: Begin real-time conversations with users once an interest message is accepted. Use the chat interface to send and receive messages.

 Pending Features and Future Enhancements

Pending Features

- Comprehensive user profile management, including profile updates and profile picture uploads.
- Improved WebSocket connection handling and reconnection processes.

 Future Enhancements

- Adding features such as notifications for new messages.
- Refining the UI/UX based on user feedback.
- Deploying the application on cloud platforms like AWS or Heroku.





