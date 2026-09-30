# Paradise Nursery Shopping Application

Paradise Nursery is an intuitive e-commerce web application designed for plant enthusiasts. The application allows users to browse categorized houseplants, view descriptions and prices, interactively add items to a shopping cart, update quantities, and calculate real-time total costs.

---

## 🌿 Features

- **Landing Page:** Welcoming interface featuring company details, mission statement, and a "Get Started" call-to-action button.
- **Product Listing:**
  - Displays over 6 unique houseplant species per category across multiple categories (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, and Low Maintenance).
  - Shows high-quality thumbnail images, plant names, descriptions, and unit prices.
  - Interactive "Add to Cart" buttons that disable automatically when an item is in the cart.
- **Dynamic Navigation Bar:** Shows total item counts live on the cart icon badge across both product browsing and shopping cart views.
- **Shopping Cart Management:**
  - Displays individual plant subtotals and overall total cart amount.
  - Supports quantity adjustments (+ / -) with automatic item removal if quantity reaches 0.
  - Includes explicit "Delete" buttons for removing items.
  - Features "Continue Shopping" and "Checkout" actions.

---

## 🛠️ Tech Stack & Dependencies

- **Frontend Library:** React.js
- **State Management:** Redux Toolkit (`@reduxjs/toolkit` & `react-redux`)
- **Styling:** CSS3
- **Build Tool:** Vite / Create React App

---

## 📁 Repository Structure

```text
├── public/
├── src/
│   ├── assets/
│   ├── AboutUs.jsx       # Company overview and mission statement
│   ├── AboutUs.css       # Styling for AboutUs component
│   ├── App.jsx           # Landing page container & view toggles
│   ├── App.css           # Background image & landing page styles
│   ├── CartItem.jsx      # Shopping cart view with item list and calculations
│   ├── CartItem.css      # Styling for cart view
│   ├── CartSlice.jsx     # Redux slice managing cart items state & reducers
│   ├── ProductList.jsx   # Product grid, categories, & dynamic navbar
│   ├── ProductList.css   # Styling for product cards and grid layout
│   ├── store.js          # Redux store configuration
│   ├── main.jsx          # Entry point wrapping App with Redux Provider
│   └── index.css         # Global styles
├── package.json
└── README.md             # Project documentation
