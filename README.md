# 💬 Talkify - Realtime Chat App

A modern, full-stack chat application built with the **MERN** stack, **Socket.io**, **TailwindCSS**, and **DaisyUI**. Enjoy real-time messaging, beautiful themes, and seamless user experience!

---

## 🚀 Features

- 🌟 **Tech Stack:** MERN (MongoDB, Express, React, Node.js) + Socket.io
- 🎨 **UI:** TailwindCSS + DaisyUI for stunning, responsive design
- 🔒 **Authentication & Authorization:** Secure JWT-based auth
- 👾 **Real-time Messaging:** Powered by Socket.io
- 🟢 **Online User Status:** Instantly see who's online
- 🗂️ **Global State Management:** Powered by Zustand
- 🐞 **Robust Error Handling:** Both server & client side
- 🎭 **Theme Switcher:** Personalize your chat with 30+ themes


## 🛠️ Tech Stack

- **Frontend:** React, Vite, Zustand, TailwindCSS, DaisyUI, React Router, Lucide Icons
- **Backend:** Node.js, Express, MongoDB, Mongoose, Socket.io, Cloudinary (for image uploads)
- **Authentication:** JWT, bcryptjs
- **Real-time:** Socket.io
- **State Management:** Zustand

---

## ⚡ Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/your-username/talkify-chat-app.git
cd talkify-chat-app
```

### 2. Setup Environment Variables

Create `.env` files in both `backend/` and `frontend/` directories.  
See `.env.example` or below for required variables.

### 3. Install Dependencies

```sh
cd backend
npm install

cd ../frontend
npm install
```

### 4. Seed the Database (Optional)

```sh
cd backend
node src/seeds/user.seed.js
```

### 5. Start the App

**Backend:**

```sh
cd backend
npm run dev
```

**Frontend:**

```sh
cd frontend
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser.

---

## 🧑‍💻 Folder Structure

```
backend/
  src/
    controllers/
    lib/
    middleware/
    models/
    routes/
    seeds/
frontend/
  src/
    components/
    constants/
    lib/
    pages/
    store/
```

---

## 📝 Environment Variables

### Backend (`backend/.env`)

```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### Frontend (`frontend/.env`)

```
# Usually not required unless you have custom config
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

[MIT](LICENSE)

---

## 🙏 Acknowledgements

- [Vite](https://vitejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)
- [Socket.io](https://socket.io/)
- [Zustand](https://zustand-demo.pmnd.rs/)
- [MongoDB](https://www.mongodb.com/)
- [Cloudinary](https://cloudinary.com/)

---

> Made with ❤️ by [Aryan]