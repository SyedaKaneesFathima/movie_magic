Movie-Magic – Smart Movie Ticket Booking System

MovieMagic is an intelligent and user-friendly web application that enables users to conveniently browse movies, choose showtimes, and book tickets online. Built with an interactive frontend and a reliable backend, the platform provides a smooth and efficient movie ticket booking experience for both users and administrators.

Tech Stack
Frontend: HTML, CSS, JavaScript, Bootstrap, Jinja2 (Flask templating engine)
Backend: Python (Flask framework)
Database: AWS DynamoDB (NoSQL database)
Notifications: AWS SNS (Simple Notification Service)
Authentication: Secure login and signup with password hashing using werkzeug.security
Deployment: Tested locally with the capability to be deployed on AWS EC2 or any cloud/server environment
Features
User Authentication
Secure signup and login functionality with session management and encrypted password storage.

Smart Ticket Booking
Users can easily select a movie, choose the preferred date and showtime, and book available seats.

Dynamic Scheduling
Movies can be filtered by title and date, allowing users to check real-time show availability.

Automatic Price Calculation
Ticket prices are dynamically updated based on the number of seats selected.

Email Notifications
Users receive booking confirmation notifications through AWS SNS after successful ticket booking.

Admin Panel (Extendable)
Administrators can manage the platform by adding or removing movies and viewing booking details.
