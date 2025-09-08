# Backend - Quizzy App

This document outlines the backend components and architecture of the **Quizzy App**, developed as part of **CPSC-491-GROUP-8**.

## Technologies Used

- Node.js – JavaScript runtime
- Express.js – Web framework
- MongoDB – NoSQL database
- Mongoose – ODM for MongoDB
- JWT – Authentication
- bcrypt – Password hashing

## Folder Structure

/server
controllers/       # Request logic
models/            # Mongoose models
routes/            # API routes
middleware/        # Auth middleware
utils/             # Helpers
config/            # DB config
index.js           # Entry point

## Features

- User Authentication (JWT + social login)
- Quiz creation from uploads or text
- User quiz history
- Dashboard data (trending & activity)

## Authentication

- Tokens via JWT
- Middleware for protected routes

## Setup Instructions

1. Navigate to the backend folder:
   ```bash
   cd server
npm installMONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
npm start
