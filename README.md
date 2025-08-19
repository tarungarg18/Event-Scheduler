# 🎉 Event Scheduler

**Event Scheduler** is a modern React-based web app for discovering, creating, and managing local or online events like webinars, workshops, and meetups.

Fully responsive, feature-rich, and beginner-friendly — built with React, React Router, Context API, and Framer Motion.

---

## 🚀 Features

### 🗂 Event Discovery
- View a list of upcoming events
- Search and filter by **type**, **category**, or **date**
- Bookmark or attend events

### ✍️ Create Events
- Add title, description, date, location, category
- Choose between **online/offline**
- Form validation included

### 📅 Calendar View
- View all upcoming events in a timeline or calendar layout

### 🌗 Theme Toggle
- Light/Dark mode supported
- Theme is saved in localStorage

### 👤 Mock Login
- Simple username-based login system
- User data saved in localStorage
- Login/logout UI and protected routes

### 📱 Responsive Design
- Optimized for both desktop and mobile
- Responsive navbar with “More” dropdown on small screens

### 🎯 Animations
- Framer Motion scroll + route animations
- Animated dropdown menus for mobile

---

## 🛠 Tech Stack

| Tech               | Description                   |
|--------------------|-------------------------------|
| React              | Core UI framework             |
| React Router DOM   | Client-side routing           |
| Framer Motion      | Animations and transitions    |
| Context API        | State management              |
| LocalStorage       | Persistent user + event data  |
| Vanilla CSS / Inline| Styling (or Tailwind optional)|

---

## 📸 Screenshots

### ✅ Dashboard  
<img width="1882" height="911" alt="image" src="https://github.com/user-attachments/assets/5512ddd2-514f-460f-ab40-43141d838f94" />

### 📝 Create Event  
![Create Event](public/screenshots/create-event.png)

### 👤 Login  
<img width="803" height="501" alt="image" src="https://github.com/user-attachments/assets/054ecf9e-175c-4adf-a6e3-e9634060dcdc" />


### 📅 Calendar View  
<img width="1436" height="494" alt="image" src="https://github.com/user-attachments/assets/dde93a69-3542-4b29-9a68-ea4b86fcb93b" />

---

## 🔧 Installation

```bash
git clone https://github.com/your-username/EventPal.git
cd Event-Scheduler
npm install
npm start

----
📁 Folder Structure
bash
Copy
Edit
src/
├── components/         # Navbar, EventCard, etc.
├── pages/              # Home, CreateEvent, EventDetail, etc.
├── context/            # AuthContext, EventContext, ThemeContext
├── App.js
└── index.js

---
💡 Future Enhancements

✅ Google Calendar Integration

🔐 OAuth login (Google, GitHub)

🔔 Event Reminders

📊 Event analytics dashboard

🧾 Invite RSVP email simulation
