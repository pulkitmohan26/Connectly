# 🌐 Connectly – Real-Time Language Exchange Platform

![MERN Stack](https://img.shields.io/badge/MERN-Stack-brightgreen?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Bundler-Vite-purple?style=for-the-badge&logo=vite)
![React Router](https://img.shields.io/badge/Routing-React%20Router-orange?style=for-the-badge&logo=reactrouter)
![Tailwind CSS](https://img.shields.io/badge/Styling-TailwindCSS-blue?style=for-the-badge&logo=tailwindcss)
![Socket.io](https://img.shields.io/badge/Realtime-Socket.io-black?style=for-the-badge&logo=socketdotio)
![Git](https://img.shields.io/badge/Version%20Control-Git-orange?style=for-the-badge&logo=git)
![Render](https://img.shields.io/badge/Deployed%20On-Render-3f3f3f?style=for-the-badge&logo=render)
![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

Connectly is a full-stack language learning app that enables users to connect with native speakers via real-time chat and video calls. Built with the MERN stack and deployed on Render, it ensures smooth peer-to-peer communication and responsive design.

The video calling feature is implemented using **WebRTC** along with the **Media Stream API** to allow camera and audio streaming.

---

## 🚀 Features

- 🌍 Match with native speakers for immersive learning
- 🗨️ Real-time messaging using **Socket.io**
- 🎥 One-on-one video calls via **WebRTC** and **Stream API**
- 🎨 Themed UI with **Tailwind CSS** and **DaisyUI**
- 🔄 Optimized data handling with **TanStack Query**
- 🔔 Toast notifications for seamless feedback

---

## 🧱 Tech Stack

| Layer        | Tools & Frameworks                             |
|--------------|------------------------------------------------|
| **Frontend** | React, Vite, React Router, Tailwind CSS, DaisyUI |
| **Backend**  | Node.js, Express.js                            |
| **Database** | MongoDB                                        |
| **Realtime** | WebRTC, Socket.io                              |
| **State/Data** | TanStack Query, React Toaster               |
| **Deployment** | Render                                       |

---

## ⚙️ Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Mozeel-V/connectly-app.git
   cd connectly-app
   ```

2. **Install dependencies**
   - Frontend:
     ```bash
     cd frontend
     npm install
     ```
   - Backend:
     ```bash
     cd backend
     npm install
     ```

3. **Environment Setup**
   - Create `.env` files in both `/frontend` and `/backend` directories with your configuration as per .env.example given

4. **Run locally**
   - Start backend:
     ```bash
     cd backend
     npm run dev
     ```
   - Start frontend:
     ```bash
     cd frontend
     npm run dev
     ```

---

## 🌍 Deployment

The full-stack app is deployed using **Render** for both frontend and backend. WebRTC signaling and Socket communication are optimized for low-latency user interactions.

View the preview [here](https://connectly-app-project.onrender.com)

---

## 📄 License
This project is licensed under the MIT License.

---

## 👤 Author
Pulkit Mohan | IIT Kharagpur CH

Email: [pulkitmohan7@gmail.com]
