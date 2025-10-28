# Personal Training App

This project is a fullstack web application built with **React (Vite + TypeScript)** for the frontend and **.NET Minimal API** for the backend.  
The purpose of this application is to allow users to log their workouts, set fitness goals, and track progress over time.

---

## Project Structure

The repository contains both the frontend and backend parts of the application.  
The backend is provided as a ready-made Minimal API, and the frontend is implemented using React and TypeScript.


---

## How to Run the Application

The project consists of two separate parts: **backend** and **frontend**.  
These must be installed and started separately.

### Clone the Repository

```bash
git clone https://github.com/MSU98/personal-training-app.git
cd personal-training-app

### Install Dependencies
Backend (.NET)

Open a terminal inside the backend folder:

cd backend
dotnet restore


Start the backend server:

dotnet run


By default, the backend runs on:

https://localhost:5001
http://localhost:5000

Frontend (React + TypeScript)

Open another terminal window and navigate to the my-fit-app folder:

cd my-fit-app
npm install


Start the frontend development server:

npm run dev


By default, the frontend runs on:

http://localhost:5173

Make sure both backend and frontend are running at the same time for the application to work correctly.

## User Authentication

User login and access control are managed by the backend API.
Different REST routes and permissions depend on the user role stored in the database.

Technologies Used

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

Track progress and fitness goals

Export workout data as JSON

Responsive design (mobile, tablet, desktop)

Protected routes (requires login)

Notes for the Examiner

The repository includes both backend and frontend projects.

The backend and frontend must be started separately, as described above.

The backend is unchanged from the provided Minimal API solution.

The frontend, located in the my-fit-app folder, communicates with the backend via REST API requests.

No installation or build steps are required outside these instructions.
