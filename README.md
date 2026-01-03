# 🌿 Paradise Nursery - E-Plant Shopping

A modern, responsive e-commerce web application for purchasing plants online. Built with React and Redux Toolkit, featuring a beautiful landing page, categorized product listings, and a fully functional shopping cart.

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **Beautiful Landing Page**: Welcoming homepage with smooth transitions
- **Categorized Plant Listings**: Browse plants by category:
  - Air Purifying Plants
  - Aromatic Fragrant Plants
  - Insect Repellent Plants
  - Medicinal Plants
  - Low Maintenance Plants
- **Shopping Cart**: Add items to cart, manage quantities, and view cart summary
- **State Management**: Redux Toolkit for efficient state management
- **Responsive Design**: Modern UI that works on all devices
- **About Us Section**: Information about Paradise Nursery

## 🛠️ Tech Stack

- **React** 18.2.0 - UI library
- **Redux Toolkit** 2.2.3 - State management
- **React Redux** 9.1.1 - React bindings for Redux
- **Vite** 5.2.0 - Build tool and dev server
- **ESLint** - Code linting

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd e-plantShopping
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal)

## 📁 Project Structure

```
e-plantShopping/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── AboutUs.jsx          # About Us component
│   ├── AboutUs.css          # About Us styles
│   ├── App.jsx              # Main App component
│   ├── App.css              # App styles
│   ├── CartItem.jsx         # Shopping cart component
│   ├── CartItem.css         # Cart styles
│   ├── CartSlice.jsx        # Redux cart slice
│   ├── ProductList.jsx      # Product listing component
│   ├── ProductList.css      # Product list styles
│   ├── store.js             # Redux store configuration
│   ├── main.jsx             # Application entry point
│   └── index.css            # Global styles
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint
- `npm run deploy` - Deploy to GitHub Pages (requires predeploy)

## 💻 Usage

1. **Landing Page**: Start by viewing the beautiful landing page with the "Get Started" button
2. **Browse Products**: Click "Get Started" to view all available plants organized by categories
3. **Add to Cart**: Click "Add to Cart" on any plant to add it to your shopping cart
4. **View Cart**: Click the cart icon in the navigation bar to view your cart
5. **Manage Cart**: Update quantities or remove items from your cart
6. **Navigate**: Use the "Home" link to return to the landing page

## 🎨 Features in Detail

### Shopping Cart
- Add multiple items to cart
- Automatic quantity tracking
- Remove items from cart
- Update item quantities
- Visual cart badge showing total items

### Product Categories
Each category contains 6 carefully selected plants with:
- High-quality images
- Detailed descriptions
- Pricing information
- Easy add-to-cart functionality

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the Apache License - see the LICENSE file for details.

## 👤 Author

[Shreyas YM]

## 🙏 Acknowledgments

- Plant images from Pixabay and Unsplash
- Icons and UI inspiration from various sources

---

**Paradise Nursery** - Where Green Meets Serenity 🌱
