# Linkify 🌐💬

Linkify is a **real-time full-stack web application** that lets users connect through instant messaging and media sharing. Built with modern technologies, it offers a sleek and efficient communication experience. 🚀

## 🌟 Deployed Application

👉 Check out the live app here: [Linkify Live Application](https://linkify-front-33uh.onrender.com/)

## 🛠️ Technologies Used

- **Frontend:** React ⚛️, TypeScript 🟦, Material UI 🎨
- **Backend:** Node.js 🟢, Express.js ⚙️, Socket.IO 🔗
- **Database:** MongoDB Atlas 🍃, Mongoose 📄
- **Storage:** Azure Blob Storage ☁️
- **Deployment:** Render (Static Site & Web Services) 🌍

## ✨ Features

- **Real-Time Communication**: Instant messaging powered by Socket.IO ⚡.
- **Media Sharing**: Upload and send media files via Azure Blob Storage 🖼️.
- **User Authentication**:
  - Sign up and log in with email and password 🔑.
  - Manage user profiles for logged-in users 🧑‍💻.
  - View-only profiles for recipients 👤.
- **Messaging Capabilities**:
  - Individual and group chats 👥.
  - Edit and delete messages 📝.
  - Emoji support in chats 😄.
  - Message seen receipts in individual chats 👀.
  - Optimized performance by limiting message history to 20 per message window 📉.
- **Bonus Features**:
  - Video conferencing 🎥.
  - Clear chat and cancel edits using the ESC key ⌨️.

## 📚 What I Learned

- 📂 Used `.env` files to securely manage environment variables.
- 🌐 Integrated Azure Blob Storage with MongoDB and Node.js for seamless media uploads.
- 🚀 Optimized frontend performance by limiting the number of fetched messages to 20 per messaging window.
- 🔧 Debugged CORS issues to ensure smooth frontend-backend communication.
- 💡 Explored React and Socket.IO features, such as `emit()` for targeted messaging.
- 🛠️ Leveraged MongoDB queries to sort messages by timestamps.
- 🔍 Used browser developer tools to debug network requests efficiently.
