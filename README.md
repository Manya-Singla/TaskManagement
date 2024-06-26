# Task Management Application

This is a simple Task Management Application built with Django for the backend and React for the frontend. The application allows users to create, read, update, and delete tasks.

## Features

- **Landing Page**: Displays a list of tasks.
- **Add Task**: Allows users to add a new task with a title, description, and due date.
- **View Task**: Users can view detailed information about each task.
- **Edit Task**: Users can edit existing tasks.
- **Delete Task**: Users can delete tasks.
- **Responsive Design**: The application is usable on both desktop and mobile devices.

## Technologies Used

### Backend

- **Django**: A high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **Django REST Framework**: A powerful and flexible toolkit for building Web APIs.

### Frontend

- **React**: A JavaScript library for building user interfaces.
- **Axios**: A promise-based HTTP client for making requests to the backend API.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- Node.js
- npm (Node Package Manager)
- Git

## Setup Instructions

### Clone the Repository

git clone https://github.com/YOUR_USERNAME/TaskManagement.git
cd TaskManagement

##Backend Setup
Navigate to the backend directory:

cd backend
Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install the required Python packages:
pip install -r requirements.txt

Apply database migrations:
python manage.py migrate

Start the Django development server:
python manage.py runserver

##Frontend Setup

Open a new terminal and navigate to the frontend directory:
cd frontend

Install the required npm packages:
npm install

Start the React development server:
npm start

Running the Application
Django Server: The backend server will be running at http://127.0.0.1:8000/.
React Server: The frontend server will be running at http://localhost:3000/.
