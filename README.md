# statusapplication
Create a simplified version of a status page application similar to services like StatusPage, Cachet, Betterstack, or Openstatus. The application should allow administrators to manage services and their statuses and provide a public facing page for users to view the current status of all services.
# Status Page Application

## Overview

The Status Page Application is a web-based tool built with Django and SQLite to monitor and display the status of various services. It provides an intuitive interface for tracking uptime, downtime, and maintenance periods.

## Features

- User authentication and authorization
- Service status monitoring
- Uptime and downtime tracking
- Dashboard for real-time updates
- SQLite database integration

## Technologies Used

- **Backend:** Django
- **Database:** SQLite
- **Frontend:** HTML, CSS, JavaScript

## Installation

1. **Clone the repository:**

   ```sh
   git clone <repository-url>
   cd status_page
   ```

2. **Create a virtual environment and activate it:**

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**

   ```sh
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**

   ```sh
   python manage.py migrate
   ```

5. **Create a superuser (optional, for admin access):**

   ```sh
   python manage.py createsuperuser
   ```

6. **Run the development server:**

   ```sh
   python manage.py runserver
   ```

## Usage

- Open a web browser and go to `http://127.0.0.1:8000/`
- Log in with your credentials
- View and manage service statuses

##

