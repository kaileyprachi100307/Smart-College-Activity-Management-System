# Smart College Activity Management System

A web-based student activity management system built using Python, Flask, SQLite and Pandas.

The system helps students maintain and analyze their academic and technical activities such as internships, workshops, certifications, hackathons, technical events and projects.

## Features

- Student profile management
- Add and manage academic/technical activities
- Activity categories:
  - Internship
  - Workshop
  - Certification
  - Technical Event
  - Hackathon
  - Project
  - Competition
- Certificate status and certificate ID tracking
- Activity duration and date tracking
- Activity description
- Dashboard with summary statistics
- Total participation hours
- Total certificates
- Total internships
- Category-wise activity analysis
- Monthly participation analysis
- Certificate completion percentage
- Delete activity functionality
- JSON API for activity data
- SQLite database for data storage
- Input validation and error handling
- Responsive web interface

## Technologies Used

- Python
- Flask
- SQLite
- Pandas
- HTML5
- CSS3

## Project Structure

```text
Smart-College-Activity-Management-System/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── index.html
│   ├── add.html
│   └── report.html
│
└── static/
    └── style.css





## How to Run

### 1. Install the required libraries

```bash
pip install -r requirements.txt

2. Run the Flask application
python app.py

3. Open the application
Open:
http://127.0.0.1:5000

The SQLite database will be created automatically when the application starts.


Main Modules

-Dashboard
-Displays student information, total activities, participation hours, certificates, internships and activity records.
-Activity Management
-Students can add activities by entering the activity name, category, organizer, date, duration, certificate status, certificate ID and description.
-Analytics
-Uses Pandas to calculate category-wise activity statistics, total hours, monthly participation and certificate completion percentage.
-JSON API
-Activity information can be accessed through:
/api/activities

Database
The application uses SQLite to store student and activity information.
Future Scope
Multiple student accounts
Login and authentication
Certificate file upload
PDF report generation
Advanced search and filtering
Graphical charts
Cloud database integration
Admin panel
Cloud deployment
Purpose
This project demonstrates the use of Python, Flask, SQLite and Pandas to develop a practical student activity management system.