# 🕹️ Game Room Booking App

A lightweight, calendar-based web app to manage game room bookings at work — designed for simplicity and speed. Users can select a game from the room (e.g., Foosball, PingPong or PS5), choose a time slot, and book it using only a nickname (no authentication required). Built using **React + Vite**, **Firebase Firestore**, and **FullCalendar** with the Resource Timeline view.

---

## 🚀 Tech Stack

- **Frontend:** React (Vite)
- **Calendar:** FullCalendar with Resource Timeline
- **Backend/Database:** Firebase Firestore

---

## 📁 Project Structure

game-room-booking/

├── public/

│ └── index.html

├── src/

│ ├── components/

│ │ ├── CalendarView.jsx # Calendar with resource-timeline view

│ │ ├── BookingModal.jsx # Form to enter nickname, game, time

│ │ └── BookingList.jsx # Optional: list of daily bookings

│ ├── firebase/

│ │ └── firebaseConfig.js # Firebase initialization

│ ├── utils/

│ │ └── dateUtils.js # Helper functions for time formatting

│ ├── App.jsx # Main application logic

│ ├── main.jsx # Vite entry point

├── .env # Firebase config (excluded from Git)

├── .gitignore

├── vite.config.js

└── README.md
