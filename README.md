# EMSforOLLYO
For Completion of task given by ollyo, made an EMS website
# For User Part
Register as a user or use username: abc
password: abc
# For Admin Panel
http://emsforollyo.infinityfreeapp.com/Admin/index.php
username: Rashed
Password: ollyo

# Event Management System

A simple web-based event management system that allows users to create, manage, and view events, as well as register attendees and generate event reports.

## Features

- User Authentication (Login/Register)
- Event Management (Create, Read, Update, Delete)
- Attendee Registration
- Event Dashboard with sorting and filtering
- JSON API endpoints

## Requirements

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (Apache/Nginx)

## Installation

1. Clone the repository to your web server directory
2. Import the database schema from `classic_events.sql`
3. Configure the database connection in `Database/connect.php`:
   - Update DB_HOST
   - Update DB_USER
   - Update DB_PASS
   - Update DB_NAME
4. Ensure the web server has write permissions for the uploads directory
5. Access the application through your web browser
