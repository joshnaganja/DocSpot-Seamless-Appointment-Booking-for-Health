# 🏥 DocSpot – Hospital Appointment Booking System
MERN Stack (Without Database)

---

## 📌 Project Overview

DocSpot is a basic Hospital Appointment Booking System built using the MERN Stack (without MongoDB).

This project allows users to:

- View available doctors
- Book appointments
- View booked appointments

⚠️ This version does NOT include:
- User Login
- User Registration
- Database storage

All data is stored temporarily in server memory and will reset when the server restarts.

---

## 🚀 Tech Stack Used

Frontend:
- React.js
- CSS
- Axios
- React Router DOM

Backend:
- Node.js
- Express.js
- CORS

---

## 🏗️ System Architecture

The project follows a simple client-server architecture:

1. React frontend handles UI.
2. Express backend handles API requests.
3. Data is stored in in-memory arrays inside server.js.

---

## 📂 Project Structure

DocSpot-Hospital-Appointment-System/

backend/
- server.js
- package.json

frontend/
- public/
  - index.html
- src/
  - components/
  - pages/
  - App.js
  - index.js
  - App.css
- package.json

README.md

---

## ⚙️ Installation & Setup

### Step 1: Extract the Project

Unzip the project folder.

---

### Step 2: Start Backend

Open terminal:

cd backend  
npm install  
npm start  

Backend runs on:
http://localhost:5000

---

### Step 3: Start Frontend

Open another terminal:

cd frontend  
npm install  
npm start  

Frontend runs on:
http://localhost:3000

---

## 🔎 Features

- Display list of doctors
- Book appointment with doctor
- View booked appointments
- Simple REST API integration
- Clean user interface

---

## 🧠 How It Works

- Doctor data is stored in an array inside server.js.
- When a user books an appointment, it is stored in an appointments array.
- Since there is no database, all data is lost when the server restarts.

---

## 🛠️ Future Improvements

- Add User Login and Registration
- Integrate MongoDB database
- Add appointment validation
- Add Admin panel
- Deploy online

---

## 📘 Purpose of the Project

This project is created for learning and demonstration of:

- MERN stack basics
- API creation using Express
- React frontend integration
- Client-server communication

---
