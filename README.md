# ✨ Full Stack Realtime Chat App ✨


A modern **full-stack realtime chat application** built with the MERN stack, featuring secure authentication, image sharing, and online status indicators. Designed with a clean, responsive UI and optimized for smooth real-time communication.

---

## 🚀 Highlights

- 🌟 **Tech Stack:** MERN + Socket.io + TailwindCSS + DaisyUI
- 🔐 **Authentication & Authorization** — Secure user login/signup with JWT
- 💬 **Real-Time Messaging** — Instant communication via Socket.io
- 🟢 **Online User Status** — See who’s currently active
- 🌍 **Global State Management** — Managed with Zustand
- 📷 **Image Uploads** — Integrated with Cloudinary for media storage
- 🛡 **Error Handling** — Robust error handling on both server and client
- 📱 **Responsive UI** — Works seamlessly across devices
- ☁️ **Free Deployment** — Optimized for cloud hosting

---

## ⚙️ Setup Environment Variables

Create a `.env` file in the root directory and add:

```env
MONGODB_URI=your_mongodb_uri
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
