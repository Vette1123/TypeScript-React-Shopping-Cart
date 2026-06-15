# 🛒 TypeScript React Shopping Cart

> A small storefront with a sliding cart drawer — built to practice typed React state.

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-4-3178C6?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-2-646CFF?logo=vite&logoColor=white)
![React Bootstrap](https://img.shields.io/badge/React_Bootstrap-2-7952B3?logo=bootstrap&logoColor=white)

A learning project focused on modelling cart state with the React Context API in fully typed TypeScript, plus `localStorage` persistence so the cart survives page reloads.

## ✨ Features

- 🛍️ Browse a product grid with prices and images
- ➕ Add, increment, decrement, and remove items
- 🧾 Slide-out cart drawer (Bootstrap Offcanvas) with running total
- 💾 Cart state persisted to `localStorage` via a typed `useLocalStorage` hook
- 🧭 Multi-page layout (`Home` / `Store` / `About`) with React Router

## 🛠️ Tech Stack

- **Framework** — React 18 + TypeScript
- **Build tool** — Vite
- **State** — React Context (`ShoppingCartContext`) + `useState`
- **Persistence** — Custom `useLocalStorage<T>` hook
- **Routing** — React Router v6
- **UI** — React Bootstrap + Bootstrap 5
- **Data** — Local `items.json` (no backend)

## 📖 Getting Started

```bash
npm install
npm run dev
```

Then open the URL Vite prints (typically `http://localhost:5173`).

Other scripts:

```bash
npm run build     # type-check + production build
npm run preview   # preview the production build
```

## 🙌 Credits

Built by [Mohamed Gado](https://mohamedgado.com).
