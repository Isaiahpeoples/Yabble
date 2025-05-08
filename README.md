<div align="center" id="toc">
  <ul style="list-style: none">
	<summary>
  	<h1>💬 Yabble</h1>
	</summary>
  </ul>
</div>

<div align="center">

[![Version](https://img.shields.io/badge/version-4.0.0-white.svg)](https://github.com/Isaiahpeoples/Yabble)
[![Built With](https://img.shields.io/badge/Built_with-MERN_Stack-white)](https://www.mongodb.com/mern-stack)
[![Socket.io](https://img.shields.io/badge/Realtime-Socket.io-white)](https://socket.io/)
[![Tailwind CSS](https://img.shields.io/badge/Styled_with-TailwindCSS-white)](https://tailwindcss.com/)
[![DaisyUI](https://img.shields.io/badge/UI-DaisyUI-white)](https://daisyui.com/)
[![JWT](https://img.shields.io/badge/Auth-JWT-white)](https://jwt.io/)
[![State](https://img.shields.io/badge/State-Zustand-white)](https://github.com/pmndrs/zustand)

[![Maintenance](https://img.shields.io/badge/Maintained-yes-brightgreen.svg)](https://github.com/Isaiahpeoples/Yabble/graphs/commit-activity)
[![Live](https://img.shields.io/badge/Live-Demo-brightgreen)](https://yabble-production.up.railway.app/)

</div>
<br/>

## 🗨️ Project Overview

**Yabble** is a modern full-stack chat application featuring real-time messaging, online user indicators, token-based authentication, and reactive UI components. Built with the **MERN stack**, **Socket.io**, **TailwindCSS**, and **DaisyUI**, it delivers a fast, scalable, and elegant communication platform. It is ideal for dynamic conversation or team collaboration tool.

<br/>

## 🚀 Technologies Used

| Technology     	| Purpose                                                                  	|
|--------------------|------------------------------------------------------------------------------|
| **MongoDB**    	| 🗃️ Database for storing messages, users, and sessions.                  	|
| **Express.js** 	| ⚙️ Backend framework for REST APIs and middleware.                      	|
| **React**      	| ⚛️ Frontend library for building interactive interfaces.                	|
| **Node.js**    	| 🔧 Backend runtime for scalable server logic.                            	|
| **Socket.io**  	| 🔄 Enables real-time, bidirectional communication.                      	|
| **TailwindCSS**	| 🎨 Utility-first styling for fast, responsive UI.                       	|
| **DaisyUI**    	| 🧩 UI component library extending Tailwind.                             	|
| **JWT**        	| 🔐 JSON Web Tokens for secure user authentication.                      	|
| **Zustand**    	| 🧠 Lightweight state management for global state handling.              	|

<br/>

## 📑 Key Features

- 🔐 **Authentication & Authorization** — Secure login via JWT tokens.
- 💬 **Real-time Messaging** — Live message exchange with instant updates.
- 👥 **Online Status** — See who's online in real-time.
- 🧠 **State Management** — Efficient client state with Zustand.
- 🛠️ **Robust Error Handling** — Handles and logs API/client-side errors gracefully.

<br/>

## 📸 Screenshot

![Yabble  Screenshot](https://online-project-images.s3.us-east-2.amazonaws.com/yabble/Yabble-1.png)

<br/>

## 🔧 Installation & Setup 🔧

1. **Clone the repository**:
```bash
git clone https://github.com/Isaiahpeoples/Yabble.git
cd nextjs-store
```

2. **Install dependencies**:
```bash
npm install
```

3. **Environment variables: Configure the .env file with the following keys**:
```bash
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

4. **Start the development server**:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

<br/>

## 📂 Project Structure 📂

- **/backend: Node.js + Express API for user, message, and auth handling**

- **/frontend: React client with Zustand state and Socket.io integration**

- **/components: UI elements, forms, and shared modules**

- **/public: Static assets (e.g. icons, fonts, logos)**

<br/>

## 🌐 Live Demo

Check out the live version:  
👉 [Yabble Live Demo](https://yabble-production.up.railway.app/)

<br/>

## ⭐️ Support

If you found this project helpful or interesting, please consider giving it a **⭐️ Star**!  
Your support boosts the project’s visibility and helps it grow.
**Thank You! 🙏**
