# 👁️ Eye Tracking Food Preference System

This project is a web-based eye tracking system that detects user gaze to understand food preferences. It uses **WebGazer.js** to track eye movements through a webcam and predicts which food item the user is interested in based on where they look on the screen.

The system records user interactions and stores relevant data for analysis.

---

## -> Features

*  Real-time eye tracking using webcam
*  Detects food preference based on gaze position
*  Stores data using SQLite database
*  Simple web interface

---

## -> Tech Stack

* Frontend: HTML, CSS, JavaScript
* Backend: Node.js (Express)
* Database: SQLite
* Eye Tracking: WebGazer.js

---

## -> Prerequisites

Before running the project, make sure you have:

* Node.js installed (https://nodejs.org/)
* A working webcam

---

## -> Installation

1. Clone the repository:

   ```
   git clone <your-repo-link>
   cd final_eye_tracker_project
   ```

2. Install required dependencies:

   ```
   npm install express cors sqlite3
   npm install webgazer
   ```

---

## -> Running the Project

Start the server:

```
node server.js
```

Then open your browser and go to:

```
http://localhost:3000
```

---

## -> Project Structure

* `index.html` → Main UI
* `style.css` → Styling
* `tracker.js` → Eye tracking logic
* `server.js` → Backend server
* `records.db` → SQLite database
* `package.json` → Project dependencies

---

## -> Requirements

This project also includes a `requirements.txt` file listing necessary installations:

```
npm install express cors sqlite3
npm install webgazer
```

---

## -> Notes

* Make sure to allow webcam access in your browser
* For best results, use the system in a well-lit environment
* Eye tracking accuracy may vary depending on camera quality

---

## -> Contributing

Feel free to fork this project and improve it!

---

## -> License

This project is for educational purposes.

-> NOTE
-Make sure to just run (node server.js)
-remove database if already present cause it gets created automatically when you run servis.js
