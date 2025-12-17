🔗 URL Shortener Web Application (MERN Stack)

A full-stack URL Shortener web application built using the MERN stack, featuring JWT authentication, role-based authorization, URL analytics, and server-side rendering with EJS.

🚀 Features

User Signup & Login with JWT authentication

Short URL generation using nanoid

Automatic redirection to original URLs

Click analytics with timestamp tracking

Role-based access control

NORMAL users → View only their own URLs

ADMIN users → View URLs created by all users

Persistent login sessions using JWT stored in cookies

Server-side rendered UI using EJS templates

🛠️ Tech Stack
Frontend

EJS (Server-Side Rendering)

HTML

CSS

Backend

Node.js

Express.js

Database

MongoDB

Mongoose

Authentication & Authorization

JWT (JSON Web Token)

Cookies (cookie-parser)

Utilities

nanoid – for generating unique short URLs

Architecture

MVC Pattern

Models

Views

Controllers

Routes

Middlewares

🔄 Project Flow

User signs up or logs in

Backend validates credentials and generates a JWT token

JWT token is stored securely in browser cookies

Authentication middleware verifies token on every request

User submits a long URL

Backend generates a short ID using nanoid

URL mapping is stored in MongoDB with user reference

When short URL is accessed:

Click timestamp is recorded

User is redirected to the original URL

Dashboard displays all URLs with click analytics

Admin users can view URLs created by all users

🔐 Authentication & Authorization

Implemented JWT-based authentication

Token stored in cookies for session persistence

Authentication middleware attaches decoded user data to req.user

Role-based authorization using custom middleware:

NORMAL

ADMIN

📊 Analytics

Each visit to a short URL is logged with a timestamp

Total clicks are calculated using visitHistory.length

Analytics API available for each short URL

▶️ Getting Started
Prerequisites

Node.js

MongoDB

Installation
git clone https://github.com/saijal-02/URL-Shortener-Web-Application.git
cd URL-Shortener-Web-Application
npm install

Start MongoDB
mongod

Run the Application
npm start


Server runs on:

http://localhost:8001

📌 Future Enhancements

Password hashing using bcrypt

Token expiration & refresh tokens

Improved UI/UX

Public analytics dashboard

Rate limiting & security improvements

👨‍💻 Author

Saijal Gupta
MERN Stack Developer
