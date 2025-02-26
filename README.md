# VibeConnect

**Stay Connected Instantly: Real-Time Chat with Seamless User Experience**

VibeConnect is a cutting-edge real-time chat application designed to keep you connected with your network effortlessly. Built on a robust tech stack, it offers a smooth and secure messaging experience, complete with live user status updates and a dynamic theme-based interface.

![Screenshot 2025-02-17 010613](https://github.com/user-attachments/assets/8376b301-4311-4557-ba46-bb8e46f44f94)

## 🚀 Key Features

- 🔐 **Authentication & Authorization** using **JWT** for secure access.
- 💬 **Real-Time Messaging** powered by **Socket.io** for instant communication.
- 🟢 **Online User Status** to see who's available in real time.
- 🎨 **Customizable UI Themes** with **TailwindCSS** and **DaisyUI** for a modern, user-friendly interface.
- 🖼️ **Image Sharing in Chat** to enhance your conversations.
- 🌐 **Global State Management** with **Zustand** for seamless data flow and performance optimization.

## 🛠️ Tech Stack

- **MERN (MongoDB, Express, React, Node.js)**
- **Socket.io**
- **TailwindCSS + DaisyUI**
- **Zustand**

## 📦 Installation

### Frontend Repository

1. Clone the frontend repository:

   ```bash
   git clone https://github.com/Su1207/Vibeconnect_frontend.git
   cd Vibeconnect_frontend
   ```

2. Install client dependencies:
   ```bash
   npm install
   ```

### Backend Repository

1. Clone the backend repository:

   ```bash
   git clone https://github.com/Su1207/Vibeconnect_backend.git
   cd vibeconnect_backend
   ```

2. Install server dependencies:
   ```bash
   npm install
   ```

### Setup .env file

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

## 🏃‍♀️ Usage

### Start Backend Server

```bash
cd vibeconnect_backend
npm start
```

### Start Frontend Client

```bash
cd vibeconnect_frontend
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.
