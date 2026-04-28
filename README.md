[README.md](https://github.com/user-attachments/files/27183786/README.md)
# Pharmacy Management System

A full-stack Pharmacy Management System built with React, Node.js, Express, and MySQL.

## Prerequisites

Before running the project, ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MySQL](https://www.mysql.com/downloads/)

## Database Setup

1. Open your MySQL client (e.g., phpMyAdmin, MySQL Workbench).
2. Create a new database named `pharmacy_db` (or check your `.env` configuration).
3. Import the `pharmacy_db.sql` file provided in the root of this project to set up the tables and schema.

## Backend Setup

1. Open a terminal and navigate to the `backend` folder:
   ```bash
   cd backend
   ```
2. Install the required dependencies:
   ```bash
   npm install
   ```
3. Set up the `.env` file in the `backend` folder with your database credentials (e.g., DB_HOST, DB_USER, DB_PASSWORD, DB_NAME, JWT_SECRET).
4. Start the backend server:
   ```bash
   npm start
   ```
   *(The backend usually runs on `http://localhost:5000`)*

## Frontend Setup

1. Open a new terminal and navigate to the `frontend` folder:
   ```bash
   cd frontend
   ```
2. Install the required dependencies:
   ```bash
   npm install
   ```
3. Start the Vite development server:
   ```bash
   npm run dev
   ```
4. Open the provided localhost URL in your browser to view the application.
