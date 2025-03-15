# 🔔 QuickBuzz

**A fully web-based real-time buzzer system designed for quiz events—no hardware required!**

## 🧐 Overview

QuickBuzz is a real-time buzzer system that accurately identifies which team presses the buzzer first with millisecond precision. Built using **FEVNS** (*Firebase, Express.js, Vanilla JS, Node.js, and Socket.io*), it provides seamless team registration, live updates, and an admin dashboard for managing the quiz.

✅ **Features**:
- Instant buzzer response with real-time accuracy  
- Live leaderboard powered by Socket.io  
- Seamless team registration and admin controls  
- Firebase for secure data storage  
- 100% web-based—no hardware required!  

---

## 🚀 Live Demo

👉 [QuickBuzz Live](https://quickbuzz-dtle.onrender.com)

---

## 📌 Tech Stack

- **Firebase** – Authentication & Firestore for team data storage  
- **Express.js** – Backend server and API handling  
- **Vanilla JavaScript** – Frontend logic and UI  
- **Node.js** – Core backend runtime environment  
- **Socket.io** – Real-time communication for instant buzzer detection  

---

## 📊 System Flow

1. **Team Registration**:  
   - Teams enter their name, members, and password.  
   - Admin access is granted with specific credentials (`Admin`, `Admin@123`).  

2. **Team Dashboard**:  
   - Displays the team name and a **buzzer button**.  
   - Once pressed, the buzzer is disabled and the timestamp is sent to the admin in real-time.  
   - Shows the team's position on the leaderboard after buzzer press.  

3. **Admin Dashboard**:  
   - Displays a live leaderboard with team names and timestamps.  
   - Indicates active team connections with a ✅ tick icon.  
   - Reset button to clear buzzer data and restart the round.  

---

## 📂 Project Structure

📦 QuickBuzz ├── 📁 public │    ├── 📄 index.html         # Main landing page │    ├── 📄 register.html      # Team registration page │    ├── 📄 dashboard.html     # Team dashboard │    ├── 📄 admin.html         # Admin dashboard │    └── 📁 css                # Stylesheets ├── 📁 server │    ├── 📄 app.js             # Express & Socket.io setup │    └── 📄 routes.js          # Routes for handling requests └── 📄 README.md               # Project documentation

---

## 🛠️ Setup Instructions

1. **Clone the Repository**  
```bash
git clone https://github.com/your-username/quickbuzz.git
cd quickbuzz

2. Install Dependencies



npm install

3. Set Up Firebase



Create a Firebase project and enable Firestore and Authentication.

Add your Firebase config in /server/app.js.


4. Run the Application



node server/app.js

5. Access the System



Team Dashboard: http://localhost:3000

Admin Dashboard (Use Admin / Admin@123): http://localhost:3000/admin



---

📄 License

This project is licensed under the MIT License. Feel free to use and modify it as needed.


---

📧 Contact

For any questions or suggestions, reach out via kunal.r.0223@inspiria.edu.in.


---

⭐ If you found this useful, don't forget to give us a star!


