Perfect — we’ll now generate a **professional README.md** for your project based on the assignment requirements in *Video Calling Web Application.pdf*and the implementation in your app (`React + WebRTC + Socket.IO + Node.js + Vite + Tailwind + Render + Vercel`).

---

# 📹 Video Calling Web Application

A full-stack **real-time video conferencing app** built using **WebRTC**, **Socket.IO**, and **React (Vite)**.
It enables users to create and join meetings, toggle audio/video, chat live, and share their screen — all in the browser.

---

## 🚀 Features

### ✅ Core Functionality

* **Create Meeting:** Generate a unique room ID or shareable link.
* **Join Meeting:** Enter a valid room link to connect with others instantly.
* **Live Chat:** Real-time messaging powered by Socket.IO.
* **Audio/Video Control:** Mute/unmute mic and toggle camera visibility.
* **Screen Sharing:** Share your screen during the call.

### 💡 Additional

* Responsive dark-mode UI (built with Tailwind CSS).
* Peer-to-peer streaming using **WebRTC**.
* Socket-based signaling server for fast, reliable connections.
* Deployed backend on **Render** and frontend on **Vercel**.

---

## 🧠 Tech Stack

| Layer                       | Technology                               |
| :-------------------------- | :--------------------------------------- |
| **Frontend**                | React (Vite) + Tailwind CSS + TypeScript |
| **Backend**                 | Node.js + Express + Socket.IO            |
| **Real-Time Communication** | WebRTC                                   |
| **Deployment**              | Vercel (client) + Render (server)        |

---

## 🧩 Project Structure

```
video-call-app/
│
├── server/                # Express + Socket.IO backend
│   └── index.js
│
├── src/
│   ├── components/        # UI components (Chat, Controls, Sidebar, etc.)
│   ├── pages/             # Home.tsx, Room.tsx
│   ├── App.tsx            # Routing (React Router)
│   └── main.tsx           # Vite entrypoint
│
├── public/
│   └── assets/
│
├── package.json
├── vite.config.ts
└── tailwind.config.js
```

---

## ⚙️ How It Works

1. **Frontend (Vercel)**

   * User clicks **Create Meeting** → generates a UUID and navigates to `/room/:id`.
   * The browser requests camera/mic access and connects via WebRTC.

2. **Backend (Render)**

   * The server listens for `join-room`, `offer`, `answer`, and `ice-candidate` events via Socket.IO.
   * It relays session descriptions (SDP) and ICE candidates to peers to establish a direct WebRTC connection.

3. **Data Flow**

   * Media (video/audio) flows directly **peer-to-peer**.
   * Chat messages and room events travel via the signaling server.

---

## 🧭 Deployment Links

* **Frontend (Vercel):**
  🔗 [https://video-call-app-kohl.vercel.app](https://video-call-app-kohl.vercel.app)

* **Backend (Render):**
  🔗 [https://video-call-app-5trb.onrender.com](https://video-call-app-5trb.onrender.com)

*(Ensure CORS allows your frontend URL in Render settings.)*

---

## 🧑‍💻 Run Locally

### 1️⃣ Clone Repository

```bash
git clone https://github.com/<your-username>/video-call-app.git
cd video-call-app
```

### 2️⃣ Install Dependencies

```bash
npm install
cd server && npm install
```

### 3️⃣ Run Backend

```bash
cd server
node index.js
```

Server runs on:
`http://localhost:5000`

### 4️⃣ Run Frontend

```bash
npm run dev
```

App runs on:
`http://localhost:5173`

---

## 📷 Demonstration

| Feature                 | Screenshot |
| :---------------------- | :--------- |
| Meeting Creation & Join | ✅          |
| Real-Time Video/Audio   | ✅          |
| Chat Functionality      | ✅          |
| Screen Sharing          | ✅          |

---

## 📜 Deliverables

* ✅ Source Code (GitHub)
* ✅ Deployed Link (Vercel + Render)
* ✅ Instructions to Run Locally
* ✅ Screenshots / Demo Video

---

## 🧩 Evaluation Criteria

| Criteria                       | Status |
| :----------------------------- | :----- |
| WebRTC-based video/audio       | ✅      |
| Real-time chat (Socket.IO)     | ✅      |
| Screen sharing                 | ✅      |
| Responsive modern UI           | ✅      |
| Working deployment             | ✅      |
| Code structure & documentation | ✅      |

---

Would you like me to:

1. Format this README for **GitHub styling** (with badges, emojis, and live links)?
2. Or keep it **minimal and formal** (for assignment PDF submission)?
