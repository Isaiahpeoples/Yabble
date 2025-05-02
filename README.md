<div align="center" id="toc">
<ul style="list-style: none">
<summary>
 <h1>Yabble</h1>
</summary>
</ul>
</div>

<br>

A Full Stack Real-time Chat App built with MERN, Socket.io, TailwindCSS, and DaisyUI. Features JWT-based auth, real-time messaging, online status, global state with Zustand, and robust client/server error handling using Node.js, Express, and MongoDB.


## 🚀 Technologies Used 🚀

- **MongoDB**: NoSQL database for storing users, messages, and metadata.
- **Express.js**: Node.js web framework for building server-side APIs.
- **React**: Frontend library for building interactive user interfaces.
- **Node.js**: JavaScript runtime for building scalable server-side applications.
- **Socket.io**: Enables real-time, bidirectional communication between client and server.
- **TailwindCSS**: Utility-first CSS framework for rapid UI styling.
- **DaisyUI**: Tailwind plugin offering styled UI components.
- **JSON Web Token**: Secure user authentication and authorization.
- **Zustand**: Lightweight state management library for React.

## 📑 Key Features 📑

- **Authentication & Authorization**: Secures routes with token-based user identity.
- **Real-time Messaging**: Instantly sends and receives messages live.
- **Online User Status**: Displays active users in real-time.
- **Global State Management**: Manages app-wide state efficiently.
- **Error Handling**: Catches and manages application errors gracefully.

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

## 📂 Project Structure 📂

- **/backend: Node.js/Express API for handling user data and requests**

- **/frontend: React.js app with UI components and client-side logic**

- **/components: UI components and forms**

- **/public: Static assets and images**