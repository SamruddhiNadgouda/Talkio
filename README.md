
# 💬 Talkio — Real-Time Chat & Video Communication Platform

> *A seamless real-time communication platform for instant messaging and live video/audio interaction.*

**Talkio** is a full-stack web application built with React.js, Node.js, Express.js, MongoDB, and Socket.IO/WebRTC that enables users to communicate instantly through chat and video calls. It follows a scalable architecture for real-time data exchange and smooth user experience.
---

## 📌 Project Overview

Talkio is a real-time communication platform where users can send and receive messages instantly and connect via live video/audio calls. It leverages WebSockets (Socket.IO) and WebRTC for peer-to-peer communication.

Built using a modern full-stack approach, it ensures low-latency messaging and seamless interaction between users.

---

## ✨ Features

- 💬 Real-Time Messaging — Instant chat using Socket.IO
- 📞 Video & Audio Calls — Peer-to-peer communication using WebRTC
- 🟢 Online Status — Track active users in real-time
- 🔔 Instant Notifications — Receive updates for new messages
- 📁 Media Sharing — Send images/files in chat
- 🔐 Authentication — Secure user login and signup
- ⚡ Low Latency — Fast and efficient real-time communication

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| React.js | Frontend UI |
| Node.js | Backend runtime |
| Express.js | Server framework |
| MongoDB | Database |
| Socket.IO | Real-time communication |
| WebRTC | Video/audio streaming |
| Tailwind CSS | Frontend styling |

---

## 📁 File Structure

```
Nexus/
│
├── frontend/            # React frontend
├── backend/             # Node.js + Express backend
├── public/              # Static assets
├── controllers/         # Business logic
├── models/              # Database schemas
├── routes/              # API routes
├── socket/              # Socket.IO configuration
├── package.json         # Dependencies
└── README.md            # Documentation
```

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or above)
- [MongoDB](https://www.mongodb.com/) (local or Atlas cloud)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/SamruddhiNadgouda/Nexus.git
   cd Nexus
   ```
   
2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start MongoDB** (if running locally)
   ```bash
   mongod
   ```

4. **Run the Backend**
   ```bash
   npm run server
   ```

5. **Run the Frontend**
   ```bash
   npm start
   ```

6. **Open in browser**
   ```
   http://localhost:3000
   ```

---

## 📦 Dependencies

```json
{
  "react": "^18.x",
  "express": "^4.x",
  "socket.io": "^4.x",
  "mongoose": "^8.x",
  "webrtc": "latest"
}
```

---

## 🙋‍♀️ Author

**Samruddhi Nadgouda**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/samruddhi-nadgouda/)
[![GitHub](https://img.shields.io/badge/GitHub-black?logo=github)](https://github.com/SamruddhiNadgouda)
