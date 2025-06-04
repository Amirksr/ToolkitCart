# 🛒 ToolkitCart

A modern shopping cart application built with **React** and **Redux Toolkit**. This project aims to simplify global state management and improve code maintainability and readability.

## 🎯 Project Goal

This project explores how using **Redux Toolkit** enhances React applications by:
- Eliminating the need to manually enforce **immutability** in state updates, thanks to `Immer` under the hood.
- Combining **action types**, **action creators**, and **reducers** in a single `slice.js` file for better organization.
- Simplifying state logic and reducing boilerplate code.
- Making the store setup more concise and intuitive.

## 🚀 Live Demo

👉 [Live Vercel Demo](https://toolkit-cart.vercel.app)

## 📁 Folder Structure

```
ToolkitCart/
├── .gitignore
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── vite.config.js
├── public/
│ └── vite.svg
├── src/
│ ├── App.css
│ ├── App.jsx
│ ├── db.js
│ ├── index.css
│ ├── main.jsx
│ ├── Redux/
│ │ ├── slice.js
│ │ └── store.js
│ ├── assets/
│ │ └── react.svg
│ ├── components/
│ │ ├── cart/
│ │ │ ├── Cart.css
│ │ │ ├── Cart.jsx
│ │ │ ├── ProductItemInCart.css
│ │ │ └── ProductItemInCart.jsx
│ │ ├── footer/
│ │ │ ├── Footer.css
│ │ │ └── Footer.jsx
│ │ ├── navbar/
│ │ │ ├── Navbar.css
│ │ │ └── Navbar.jsx
│ │ ├── products/
│ │ │ ├── ProductItem.css
│ │ │ ├── ProductItem.jsx
│ │ │ ├── ProductsList.css
│ │ │ └── ProductsList.jsx
│ ├── pages/
│ │ ├── cart/
│ │ │ ├── CartPage.css
│ │ │ └── CartPage.jsx
│ │ └── home/
│ │ ├── HomePage.css
│ │ └── HomePage.js
```

## 🛠️ Tech Stack

- React
- Redux Toolkit
- Vite
- CSS Modules

## ▶️ Getting Started

1. Clone the repo
```bash
git clone https://github.com/Amirksr/ToolkitCart.git
```

2. Navigate to the project folder
```bash
cd ToolkitCart
```

3. Install dependencies
```bash
npm install
```

4. Start the development server
```bash
npm run dev
```

## 📂 Key Files

- `src/Redux/slice.js` – Contains actions and reducers bundled into a slice.
- `src/Redux/store.js` – Configures the Redux store using `configureStore`.
- `src/components/` – Reusable UI components like cart, products, navbar, and footer.
- `src/pages/` – Main application views (HomePage and CartPage).

## 📄 License

This project is open-source and available for free use.
