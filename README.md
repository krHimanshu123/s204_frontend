# s204_frontend

A modern ecommerce frontend built with React and Vite, featuring a responsive design and seamless user experience for browsing, authentication, and shopping.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

**s204_frontend** is a robust single-page application designed for an online electronics store. Users can browse products across categories like computers, mobiles, laptops, and accessories, manage their cart, place orders, and handle authentication (login/signup). The UI is styled for desktop and mobile responsiveness using custom CSS.

## Features

- **Product Browsing:** Explore computers, mobiles, laptops, and accessories with dedicated pages and product grids.
- **Authentication:** Secure login and signup functionality integrated with backend APIs.
- **Shopping Cart:** Add products to cart, proceed to checkout, and view order history.
- **Responsive Design:** Mobile-friendly layouts and adaptive grid systems.
- **Modern SPA Routing:** Fast navigation using React Router.

## Tech Stack

- **Frontend Framework:** React (with Hooks)
- **Build Tool:** Vite
- **Styling:** CSS (custom styles in `/src/components/style.css`, `/src/App.css`, `/src/index.css`)
- **Routing:** React Router
- **State Management:** React Hooks, Context (where used)
- **API Integration:** Axios (for authentication & product services)
- **Linting:** ESLint with React and Hooks plugins
- **Other Tools:** Babel/SWC for fast refresh

## Getting Started

### Prerequisites

- Node.js (version 14+)
- npm or yarn

### Installation

```sh
git clone https://github.com/krHimanshu123/s204_frontend.git
cd s204_frontend
npm install
```

### Running the App

```sh
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```sh
npm run build
```

## Project Structure

```
s204_frontend/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   ├── components/
│   │   ├── HomePage.jsx
│   │   ├── Aboutus.jsx
│   │   ├── Computers.jsx
│   │   ├── Mobiles.jsx
│   │   ├── Laptops.jsx
│   │   ├── Pendrives.jsx
│   │   ├── ProductPage.jsx
│   │   ├── Cart.jsx
│   │   ├── Payment.jsx
│   │   ├── Orders.jsx
│   │   ├── Login.jsx
│   │   ├── Signup.jsx
│   │   └── style.css
│   └── services/
│       ├── authService.js
│       ├── productService.js
│       └── cartService.js
├── vite.config.js
├── eslint.config.js
└── README.md
```

## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests should include a clear description and relevant tests.

## License

This project is currently unlicensed.

---

**Author**: [krHimanshu123](https://github.com/krHimanshu123)

---
