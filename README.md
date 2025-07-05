# 🚗 TorqueHub – Car Marketplace Platform

Welcome to **TorqueHub**, a modern, multi-page car marketplace web application built using **React**, **Vite**, and **Tailwind CSS**.

> 🔧 Fully client-side rendered with separate HTML entry points for each page.  
> 🎯 Hosted on [Vercel](https://vercel.com) with clean URLs and blazing-fast performance.

---

## 🧩 Tech Stack

- ⚛️ **React** – UI Components
- ⚡ **Vite** – Lightning-fast bundler and dev server
- 🎨 **Tailwind CSS** – Utility-first styling
- 💅 **PostCSS** – Extended styling capabilities
- 🧠 **TypeScript** – Type-safe development
- 🌐 **Vercel** – Deployment platform
- 🗂️ **Multi-Page Application (MPA)** – Individual HTML + JS for each route

---

## 📁 Folder Structure (Simplified)

```
project/
├── src/
│   ├── assets/          # Static images, SVGs
│   ├── components/      # Shared React components
│   ├── pages/           # JS logic for each page (about.js, login.js, etc.)
│   ├── styles/          # CSS styles
│   ├── *.html           # Each page has its own HTML file
│   ├── App.tsx, main.tsx, main.js, index.css
│   └── vite-env.d.ts
├── vite.config.ts       # Vite configuration
├── tailwind.config.js   # Tailwind CSS setup
├── tsconfig*.json       # TypeScript configurations
├── vercel.json          # Vercel routing + headers config
└── package.json
```

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/PrapullaKumar569/Torque-Hub.git
cd Torque-Hub
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) to see the app.

---

## 🧠 Pages Available

- `/` – Home
- `/about` – About Us
- `/buy` – Browse Cars
- `/sell` – Sell Your Car
- `/login` – User Login
- `/signup` – Register New User
- `/profile` – User Dashboard
- `/car-details` – Car Listing Details
- `/contact` – Contact Page
- `/help` – FAQ / Support
- `/dark-mode-test` – Dark mode preview
- `/404` – Custom Not Found Page

---

## 🧾 Deployment (Vercel)

> Deployed using [Vercel](https://vercel.com)

### 🔁 Clean Routing

- Custom `vercel.json` handles rewrites:
  ```json
  {
    "rewrites": [
      { "source": "/about", "destination": "/about.html" },
      ...
    ],
    "headers": [
      ...
    ]
  }
  ```

### 🌍 Production Build

```bash
npm run build
```

### ⚡ Deploy to Vercel

```bash
vercel --prod
```

---

## 🛡️ License

MIT © 2025 TorqueHub

---

## 🙌 Authors

Built with ❤️ by [Kumar](https://github.com/PrapullaKumar569).
