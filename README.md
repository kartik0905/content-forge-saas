<div align="center">

# AI Content Writer SaaS  
### Generate Engaging Posts for LinkedIn, Twitter, and More

</div>

<p align="center">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS"/>
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/>
</p>

---

## 📌 Overview

This project is a **SaaS AI-powered content generator** that helps professionals, creators, and businesses **write optimized posts** for **LinkedIn, Twitter, and other platforms**.  

With a sleek interface and an AI backend, users can:  
- ✍️ Generate high-quality content ideas  
- 🚀 Optimize posts for engagement  
- 🌍 Use cross-platform writing prompts  
- 🔐 Access content with authentication-based flow  

---

## ✨ Features

- 🧠 **AI-Powered Writing** — Generate tailored posts for LinkedIn & more  
- 💡 **Smart Prompts** — Pre-defined prompts for marketing, professional, and casual tones  
- 🖥️ **Modern UI** — Built with React + TailwindCSS + shadcn/ui  
- 🔒 **Authentication Ready** — Secure login system for users  
- 📱 **Responsive Design** — Works on desktop & mobile  

---

## 🛠️ Tech Stack

| Layer | Technologies | Purpose |
|-------|--------------|---------|
| **Frontend** | React, TypeScript, Vite, TailwindCSS, shadcn/ui | Modern UI/UX |
| **Backend** | Node.js, Express, TypeScript | API & AI orchestration |
| **AI** | OpenAI API | Content generation |
| **State Management** | React Context & Hooks | Manage app state |
| **Dev Tools** | Nodemon, Prettier, ESLint | DX & Code Quality |

---

## 📁 Folder Structure

```
project-root/
├── package.json
├── react-stream-ai-assistant   # Frontend (React + TS + Tailwind)
│   ├── src
│   │   ├── components          # UI + AI interaction components
│   │   ├── contexts            # Theme & app contexts
│   │   ├── hooks               # Custom hooks
│   │   ├── providers           # Chat & Theme providers
│   │   └── main.tsx            # Entry point
│   └── tailwind.config.ts
└── streamchatbackend           # Backend (Express + TypeScript)
    ├── src
    │   ├── agents              # AI Agents (OpenAI)
    │   ├── serverClient.ts     # Server setup
    │   └── index.ts            # Entry point
    └── tsconfig.json
```

---

## 🧪 Local Development

### 🔧 Requirements

- Node.js **v18+**
- npm or yarn
- OpenAI API Key

---

## 🏁 Getting Started

### 1. Clone & Setup

```bash
git clone https://github.com/your-username/ai-content-writer-saas.git
cd ai-content-writer-saas
```

### 2. Install Dependencies

```bash
cd streamchatbackend
npm install

cd ../react-stream-ai-assistant
npm install
```

### 3. Add Environment Variables

Create a `.env` file in `streamchatbackend`:

```bash
OPENAI_API_KEY=your_openai_api_key
PORT=5000
```

---

## 🚦 Run the App

### Start Backend

```bash
cd streamchatbackend
npm run dev
```

### Start Frontend

```bash
cd react-stream-ai-assistant
npm run dev
```

The app will run locally at 👉 **http://localhost:5173** (frontend) and **http://localhost:5000** (backend).

---

## 📦 Dependencies

- `@types/cors`  
- `@types/express`  
- `nodemon`  
- `prettier`  
- `typescript`  

---

## 🙌 Acknowledgments

- [React](https://react.dev/)  
- [TailwindCSS](https://tailwindcss.com/)  
- [shadcn/ui](https://ui.shadcn.com/)  
- [OpenAI](https://openai.com/)  
- [Node.js](https://nodejs.org/)  
- [Express](https://expressjs.com/)  

---

<div align="center">
  Built with ❤️ by <a href="https://github.com/kartik0905">Kartik Garg</a>
</div>
