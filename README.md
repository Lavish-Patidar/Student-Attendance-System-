# Student Management System

## Project Overview

This is a full-stack Student Management System application with a React frontend and a Node.js backend. The system allows managing students, teachers, classes, subjects, and administrative tasks through a user-friendly interface.

## Technologies Used

- Frontend: React,Material-UI, Vite, Redux
- Backend: Node.js, Express.js, MongoDB (Mongoose)
- Other: ESLint, Vite plugin for React

## Prerequisites

- Node.js (v14 or higher recommended)
- npm (comes with Node.js)
- MongoDB instance running locally or remotely

## Backend Setup and Running Instructions

1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure your MongoDB connection string in the backend code if needed (check `backend/index.js` or environment variables).
4. Start the backend server:
   ```bash
   npm start
   ```
   The backend server will start, typically on port 5000 (check `index.js` for exact port).

## Frontend Setup and Running Instructions

1. Navigate to the `client` directory:
   ```bash
   cd Frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm run dev
   ```
4. The frontend will be available at `http://localhost:3000` or the port shown in the terminal.

## How to Use the Project

- Open the frontend URL in your browser.
- Use the login page to access the system as an admin, teacher, or student.
- Navigate through the dashboard to manage classes, students, teachers, subjects, attendance, and exam marks.
- The backend API handles data storage and retrieval from the MongoDB database.

Feel free to explore the different user roles and their functionalities.

---

This README provides a basic overview and setup instructions to get the project running locally.
