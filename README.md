# ⚛️ React + Vite + TailwindCSS Template

A **modern frontend starter template** built with **React**, **Vite**, and **Tailwind CSS** — featuring Hot Module Replacement (HMR), ESLint for code linting, and optional integrations like **Redux Toolkit**, **React Router**, and **React Hot Toast** for state management, routing, and notifications.

[![Vite](https://img.shields.io/badge/Vite-4.0-blueviolet?style=flat-square&logo=vite)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-18.0-blue?style=flat-square&logo=react)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3.0-06B6D4?style=flat-square&logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](./LICENSE)

---

## 🚀 Features

✅ **Vite** — Ultra-fast build tool and development server  
✅ **React** — Latest version for modern UI development  
✅ **Tailwind CSS** — Utility-first CSS framework for rapid design  
✅ **ESLint** — Code quality and consistency enforcement  
✅ **Redux Toolkit** — Simplified global state management  
✅ **React Hot Toast** — Elegant toast notifications  
✅ **React Router DOM** — Easy and declarative routing  

---

## ⚙️ Installation & Setup

### 🧩 Step 1: Create a Vite Project
Install Vite globally (if not installed):
```bash
npm create vite@latest
When prompted:

Project name: paste

Framework: React

Variant: JavaScript or TypeScript (as preferred)

Then navigate into the project:

bash
Copy code
cd paste
🎨 Step 2: Install Tailwind CSS
Install Tailwind and its dependencies:

bash
Copy code
npm install -D tailwindcss postcss autoprefixer
Initialize Tailwind config:

bash
Copy code
npx tailwindcss init
This creates a tailwind.config.js file.
Replace its content with:

js
Copy code
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    './index.html',
    './src/**/*.{js,ts,jsx,tsx}',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
Add these lines to your main CSS file (src/index.css or src/main.css):

css
Copy code
@tailwind base;
@tailwind components;
@tailwind utilities;
🧱 Step 3: Install Project Dependencies
bash
Copy code
npm install
🚀 Step 4: Run the Development Server
bash
Copy code
npm run dev
Your app will be live at 👉 https://quick-note-plum.vercel.app/

🧩 Available Scripts
Command	Description
npm run dev	Starts the Vite development server with HMR
npm run build	Builds the project for production
npm run preview	Serves the production build locally
npm run lint	Lints the code using ESLint

📦 Packages Used
Dependencies
@reduxjs/toolkit — State management with slices & reducers

lucide-react — Icon set for React

react — Core library for UI building

react-dom — DOM bindings for React

react-hot-toast — Toast notifications

react-redux — Official React bindings for Redux

react-router-dom — Routing for React apps

Dev Dependencies
@eslint/js — ESLint base configuration

@types/react, @types/react-dom — Type definitions (for TypeScript users)

@vitejs/plugin-react — Enables Fast Refresh

autoprefixer — Adds vendor prefixes to CSS

eslint, eslint-plugin-react, eslint-plugin-react-hooks, eslint-plugin-react-refresh — ESLint plugins

globals — ESLint global variables config

postcss — CSS transformation tool

tailwindcss — Utility-first CSS framework

vite — Build tool and dev server

🗂️ Project Structure
arduino
Copy code
paste/
│
├── node_modules/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── .eslintrc.js
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
└── package.json
🎨 Tailwind CSS Configuration
js
Copy code
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    './index.html',
    './src/**/*.{js,ts,jsx,tsx}',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
