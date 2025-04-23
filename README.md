# 💬 ChatApp

A minimal, real-time group chat application built with **Spring Boot**, **React**, and **WebSockets**. Users can simply enter a username and room ID to join or create a chat room — no login or registration needed.

![ChatApp Demo]

![image](https://github.com/user-attachments/assets/ab88c10b-e820-46cb-a238-8aa0af84e15e)
![image](https://github.com/user-attachments/assets/e158e10f-8d48-4d1e-b153-ebd931b80e2e)
![image](https://github.com/user-attachments/assets/e4e39723-ee58-4219-b9b1-54eab1eda405)



---

## 🚀 Features

- 🔑 **Join/Create Rooms** with just a username & room ID
- 💬 **Real-Time Messaging** via WebSocket
- 🧑‍🤝‍🧑 **Multiple Users per Room**
- 📱 **Responsive UI**
- ⏱️ **Timestamps on Messages**
- 🟢 **Live User Join Notifications**
- ✨ Lightweight & fast

---

## ⚙️ Tech Stack

| Layer     | Technology           |
|-----------|----------------------|
| Frontend  | React, Tailwind CSS or CSS3 |
| Backend   | Spring Boot (Java)   |
| Realtime  | WebSocket (Spring STOMP or raw WebSocket) |

---

## 📦 Getting Started

### 🖥️ Backend – Spring Boot

```bash
cd backend
./mvnw clean install
./mvnw spring-boot:run


### 🖥️ Frontend – React (Vite)

```bash
cd frontend
npm install
npm run dev
