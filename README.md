# LuminaStore 🛍️

A modern, responsive e-commerce storefront web application built with Vanilla JavaScript (ES6+), HTML5, Tailwind CSS, and FontAwesome. LuminaStore dynamically fetches catalog data from [FakeStoreAPI](https://fakestoreapi.com/) and delivers a seamless single-page application (SPA) shopping experience featuring live search, multi-category filtering, persistent wishlist and cart drawers, and a simulated checkout flow.

## 🌟 Key Features

* Single-Page Application (SPA) Routing: Instant client-side navigation between Home, Catalog, About Us, Contact Us, FAQ, Privacy Policy, and Terms of Service without page reloads.
* Live Catalog & API Integration: Real-time data fetching from FakeStoreAPI with custom skeleton loaders and error-handling retry states.
* Search & Multi-Category Filtering: Real-time title search combined with dynamic category pills and sorting capabilities (Price: Low/High, Rating, Featured).
* Persistent Cart & Wishlist Drawers: Cart items, quantities, and favorite items automatically persist using browser `localStorage`.
* Dynamic Checkout Computation: Real-time subtotal, 8% tax calculation, and dynamic shipping thresholds (Free shipping over $50, otherwise flat $5.99).
* Simulated Checkout Workflow: Multi-step modal processing with field validation, payment loading spinner, generated order numbers, and cart clearing logic.
* Product Quick View Modal: Detailed view popups displaying star ratings, full product descriptions, and direct add-to-bag controls.
* Custom Hero Background Support: Modular CSS styling allowing custom hero background photos and overlay adjustments.

## 🛠️ Tech Stack & Dependencies

* Frontend: HTML5, Modern Vanilla JavaScript (ES6+)
* Styling: [Tailwind CSS CDN](https://tailwindcss.com/)
* Typography: [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (Google Fonts)
* Icons: [FontAwesome 6.4.0](https://fontawesome.com/)
* Data Source: [FakeStore API](https://fakestoreapi.com/)

## 📁 Project Structure

luminastore/
├── index.html            # Main single-page application HTML structure

├── assets/
│   ├── logo_bg.png       # Store favicon / branding asset
│   └── heroA.jpg       # Custom background image for Hero section

├── css/
│   └── style.css         # Animations, filter button states, & custom background CSS

└── js/
    └── app.js            # State management, API calls, cart engine, and SPA router
