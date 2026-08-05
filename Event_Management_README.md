# Event Management System

An Event Management System developed using **Python, Flask, SQLite, HTML, CSS, and JavaScript**.

The system allows users to create events, register for events, cancel registrations, while administrators can approve or reject submitted events.

---

## Features

### Authentication

- User Registration
- User Login
- Logout
- Session Management

### Event Management

- Create Events
- View Events
- Event Approval
- Event Rejection
- Capacity Management

### Registration

- Register for Events
- Cancel Registration
- Prevent Duplicate Registrations
- Capacity Validation

### Search

- Filter Events by Date
- Filter Events by Location

### Admin

- Admin Dashboard
- Approve Events
- Reject Events

### UI

- Responsive Design
- Dark / Light Theme
- Modern Dashboard
- Animations

---

## Technologies Used

- Python
- Flask
- SQLite
- HTML5
- CSS3
- JavaScript

---

## Project Structure

```
Event-Management-System/
│
├── app.py
├── database.db
├── requirements.txt
│
├── sql/
│   └── schema.sql
│
├── static/
│   ├── style.css
│   └── script.js
│
└── templates/
    ├── index.html
    ├── login.html
    ├── register.html
    ├── events.html
    ├── registrations.html
    └── admin.html
```

---

## Installation

Install Flask

```bash
pip install flask
```

---

## Running the Project

### Step 1

Open the project folder in VS Code.

### Step 2

Open Terminal.

### Step 3

Run the application.

```bash
python app.py
```

### Step 4

Open your browser and visit

```
http://127.0.0.1:5000
```

---

## Default Login Credentials

### Admin

```
Email:
admin@gmail.com

Password:
admin123
```

### User

```
Email:
user@gmail.com

Password:
user123
```

---

## Project Workflow

1. Register a new user.
2. Login using user credentials.
3. Create an event.
4. Event is stored with **Pending** status.
5. Login as Admin.
6. Approve the event.
7. Login again as User.
8. View approved events.
9. Register for an event.
10. View registered events.
11. Cancel registration if required.

---

## Database

SQLite Database

Tables

- users
- events
- registrations

---

## Functionalities

### User

- Register
- Login
- Create Events
- View Approved Events
- Register for Events
- Cancel Registration

### Admin

- View All Events
- Approve Events
- Reject Events

### Search

- Filter by Date
- Filter by Location
