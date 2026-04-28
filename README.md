# MENSTORE Frontend

Modern e-commerce frontend for a men's clothing store.
Built with **Next.js**, **TypeScript**, and **Tailwind CSS**.

---

## 🚀 Overview

This project is a fully functional **frontend UI for an online clothing store**, including:

* Home page with hero section and featured products
* Product catalog with grid layout
* Dynamic product pages
* Shopping cart UI
* Checkout page
* Responsive mobile-first design

> Backend (FastAPI) is developed separately and will be integrated via API.

---

## 🧱 Tech Stack

* **Next.js (App Router)**
* **TypeScript**
* **Tailwind CSS**
* **React**

---

## 📁 Project Structure

```
app/
├── page.tsx                # Home
├── layout.tsx              # Global layout
├── globals.css             # Global styles
├── catalog/                # Catalog page
├── product/[id]/           # Dynamic product page
├── cart/                   # Cart page
├── checkout/               # Checkout page

components/
├── Header.tsx
├── Footer.tsx
```

---

## ✨ Features

* Clean, minimal fashion-style UI
* Fully responsive (mobile-first)
* Reusable layout and components
* Dynamic routing (`/product/[id]`)
* Ready for backend integration

---

## ⚙️ Getting Started

### 1. Clone the repository

```
git clone https://github.com/aslan8980/erkinsouls.git
cd erkinsouls
```

### 2. Install dependencies

```
npm install
```

### 3. Run the development server

```
npm run dev
```

Open:

```
http://localhost:3000
```

---

## 🔌 Backend Integration (Coming Next)

This frontend is designed to connect with a **FastAPI backend**, providing:

* Product data
* Cart management
* Order processing

---

## 🧠 Future Improvements

* Backend integration (FastAPI)
* Authentication (login/account)
* Payment integration
* AI features (virtual try-on, recommendations)
* Animations & UI polish


