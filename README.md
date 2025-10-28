# Personal Training App

This project is a fullstack web application built with **React (Vite + TypeScript)** for the frontend and **.NET Minimal API** for the backend.  
The purpose of the app is to allow users to log workouts, set goals, and track their progress over time.

---

## Project structure

The repository contains both frontend and backend parts.  
The backend is provided as a ready-made Minimal API solution, and the frontend is implemented in React with TypeScript.


---

## How to run the application

There are two parts of the project that need to be started separately: the backend API and the React frontend.

### Step 1: Clone the repository
```bash
git clone https://github.com/MSU98/personal-training-app.git
cd personal-training-app
User authentication

User login and access control are handled by the backend.
Different REST routes and permissions depend on the user role stored in the database.

Technologies used

Frontend:

React (Vite)

TypeScript

React Router

React Bootstrap

Axios

Backend:

.NET Minimal API

SQLite database

Features

Log and view workouts

Track progress and goals

Export workout data as JSON

Responsive design for mobile, tablet, and desktop

Protected routes (requires login)

Notes for the examiner

The project contains two separate parts (frontend and backend).

The backend and frontend must be started separately as described above.

The backend has not been modified from the provided solution.

The frontend is located inside the my-fit-app folder and communicates with the backend through REST API requests.
