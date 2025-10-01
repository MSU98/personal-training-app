# Personal Training Diary

A mobile-friendly fullstack web application to track workouts, set goals, view statistics, and export training data.

This project uses a **React + TypeScript frontend** (Vite) and connects to a **.NET Minimal API backend** with a SQLite database. User authentication is handled via JWT and certain routes are protected based on login status.

---

## Features

- **User Authentication**
  - Login and logout
  - Protected routes for logged-in users
- **Workout Management**
  - Create, read, update, delete workouts
  - Add notes, date, and exercises
- **Goals**
  - Set, view, update, and remove training goals
- **Statistics**
  - Track weekly workout counts
  - View progress over time
- **Export**
  - Export workouts as JSON or CSV
- **Responsive Design**
  - Works on mobile, tablet, and desktop
- **Custom React Hook**
  - `useFetch` for fetching data from the API

---

## Tech Stack

- **Frontend:** React 18, TypeScript, Vite, React Router, React Bootstrap
- **Backend:** .NET Minimal API (provided)
- **Database:** SQLite (at least 3 tables)
- **Version Control:** Git with frequent commits

---
