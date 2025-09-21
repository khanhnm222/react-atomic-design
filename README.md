# React + TypeScript + Vite + Atomic Design + TailwindCSS v4 Template

🚀 A modern boilerplate for building scalable React applications with **Vite**, **TypeScript**, **Atomic Design principles**, and **TailwindCSS v4**.  
This template provides a clean structure, utility-first styling with the latest Tailwind features, and best practices for reusable UI components.

---

## ✨ Features

- ⚡ **Vite** — Blazing-fast dev server & build  
- 🛡 **TypeScript** — Strong typing for maintainability  
- 🧩 **Atomic Design** — Scalable UI architecture  
- 🎨 **TailwindCSS v4** — Zero-config, utility-first styling  
- ✅ Pre-configured ESLint & Prettier

---

## 📂 Project Structure

```bash
src/
├── assets/         # Static assets (images, fonts, etc.)
├── components/     # Atomic Design layers
│   ├── atoms/      # Smallest building blocks (buttons, inputs, labels)
│   ├── molecules/  # Groups of atoms (form fields, cards)
│   ├── organisms/  # Complex UI sections (headers, navbars, sidebars)
│   ├── templates/  # Page-level layouts
│   └── pages/      # Route-level views
├── hooks/          # Custom React hooks
├── utils/          # Utility functions & helpers
├── models/          # TypeScript model definitions
├── App.tsx         # Root component
└── main.tsx        # Application entry
```

## 🚀 Getting Started
**1. Clone the repository**
```
git clone https://github.com/khanhnm222/react-atomic-design.git
cd react-atomic-design

```

**2. Install dependencies**
```
npm install
# or
yarn install
```
**3. Start development server**
```
npm run dev
# or
yarn dev
```

Your app will be running at: http://localhost:5173

## 📦 Available Scripts

- ```npm run dev``` — Start development server with HMR

- ```npm run build``` — Build the app for production

- ```npm run preview``` — Preview production build locally

- ```npm run lint``` — Run ESLint checks

## 🧩 Atomic Design Overview

- **Atoms** → Small, independent UI components (e.g., Button, Input).

- **Molecules** → Groups of atoms working together (e.g., FormField).

- **Organisms** → Complex UI sections combining molecules (e.g., Header, CardList).

- **Templates** → Page-level layouts with placeholders.

- **Pages** → Final screens composed of templates & organisms.

## 📖 Tech Stack

- **React**
 — UI Library

- **Vite**
 — Next-gen frontend tooling

- **TypeScript**
 — Static typing

- **TailwindCSS v4**
 — Utility-first styling (zero config)

- **ESLint & Prettier**
 — Code quality & formatting

## 📝 License
This project is licensed under the MIT License.
Feel free to use, modify, and share it in your own projects.

## 🙌 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to change.