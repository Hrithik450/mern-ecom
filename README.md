## Powered By CodeEase 🚀

[![NPM Version](https://img.shields.io/npm/v/ecom-quickstart.svg)](https://www.npmjs.com/package/ecom-quickstart)
[![License](https://img.shields.io/npm/l/ecom-quickstart.svg)](https://github.com/Hrithik450/mern-ecom/blob/main/LICENSE)
[![Downloads](https://img.shields.io/npm/dm/ecom-quickstart.svg)](https://www.npmjs.com/package/ecom-quickstart)

---

### ⬇️ Installation

```sh
npm i ecom-quickstart@1.0.1
```

### 🚀 Introduction

ecom-launcher automates setting up frontend and backend folders, installing dependencies, and initializing servers, making development faster and hassle-free.

---

### 🛠 Features

- ✅ Automatic Folder Setup.
- ✅ Installs Dependencies Automatically.
- ✅ Fast and Efficient Setup.
- ✅ Built-in Routing System.
- ✅ Built-in Tailwind CSS Configuration.
- ✅ Built-in Redux Toolkit with Store and Slices.
- ✅ Supports React.js, Node.js, Express.js, Tailwind CSS, MongoDB.

📜 **License**: MIT License

---

This project is licensed under the MIT License.

### 🎯 Usage

To create a new project, run:

```sh
npm i ecom-quickstart@1.0.1
```

You will be prompted with:

- You can enter '.' for current dir, '..' to go back one level, or a full path for a custom location
- Enter the directory: ..
- Enter project name: Demo

This will generate:

```sh
Demo/
├── frontend/ (React.js setup)
└── backend/ (Express/Node.js setup)
```

### 📦 Module Type Selection

```sh
Which module type do you prefer? (Enter 'cjs' for CommonJS or 'esm' for ES Module):
```

```sh
esm
```

### 🎨 Select a Framework

```sh
React
```

### 🛠 Select a Variant

```sh
JavaScript
```

---

### 📂 Project Structure

### **Frontend Folder Structure**

```sh
frontend/
│── public/
│── src/
│ ├── assets/
│ ├── components/
│ │ ├── admin/
│ │ ├── auth/
│ │ ├── cart/
│ │ ├── common/
│ │ ├── layout/
│ │ ├── home/
│ │ ├── product/
│ ├── hooks/
│ ├── pages/
│ │ ├── Home.jsx
│ │ ├── Admin.jsx
│ │ ├── Auth.jsx
│ │ ├── Cart.jsx
│ │ ├── Checkout.jsx
│ │ ├── Product.jsx
│ │ ├── NotFound.jsx
│ ├── routes/
│ │ ├── PrivateRoute.jsx
│ │ ├── AppRoute.jsx
│ │ ├── AdminRoute.jsx
│ │ ├── index.jsx
│ ├── store/
│ │ ├── slices/
│ │ ├── store.jsx
│ ├── utils/
│ ├── App.jsx
│ ├── main.jsx
│ ├── App.css
│ ├── index.css
│── .env
│── package.json
│── README.md
```

### **Backend Folder Structure**

```sh
backend/
│── src/
│ ├── config/
│ │ ├── db.js
│ │ ├── config.env
│ ├── controllers/
│ │ ├── authController.js
│ │ ├── productController.js
│ │ ├── orderController.js
│ │ ├── adminController.js
│ ├── middlewares/
│ │ ├── authMiddleware.js
│ │ ├── errorHandler.js
│ │ ├── catchAsyncError.js
│ ├── models/
│ │ ├── User.js
│ │ ├── Product.js
│ │ ├── Order.js
│ ├── routes/
│ │ ├── authRoutes.js
│ │ ├── productRoutes.js
│ │ ├── orderRoutes.js
│ │ ├── adminRoutes.js
│ ├── services/
│ │ ├── emailService.js
│ │ ├── paymentService.js
│ ├── utils/
│ │ ├── generateToken.js
│ ├── index.js
│── package.json
│── README.md
```

---

### 🚀 Start the Servers

- Before starting the server, configure the `.env` file.

### Start the Frontend:

```sh
cd Demo/frontend
npm run dev
```

### Start the Backend:

```sh
cd Demo/backend
npm run dev
```

✅ **MERN eCommerce platform setup completed successfully!!**
