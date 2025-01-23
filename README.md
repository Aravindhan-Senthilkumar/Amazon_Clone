# Full-Stack Amazon Clone 🛒

Welcome to the **Amazon Clone**, a fully functional e-commerce web and mobile application built using modern web technologies. This app replicates the core features of an online marketplace, including user authentication, product listing, cart management, and order tracking.

---

## 🚀 Features

### Frontend
- **React Native with Expo**: A cross-platform mobile app for seamless user experience.
- **Redux**: State management for handling cart, user sessions, and product data.
- **React Navigation**: Smooth and intuitive user flow.

### Backend
- **Node.js & Express**: RESTful APIs for backend services.
- **MongoDB**: Robust database for user, product, and order data.
- **Authentication**: Secure login and registration using Express and MongoDB.

### Functionality
1. **User Authentication**:
   - Registration and Login with secure password storage.
2. **Product Listing**:
   - View and search for products.
3. **Cart Management**:
   - Add, update, or remove items from the cart.
4. **Order Management**:
   - Place orders and store them in MongoDB along with product details.

---

## 🛠️ Tech Stack

### Frontend
- React Native
- Expo
- Redux
- React Navigation

### Backend
- Node.js
- Express.js
- MongoDB
- Render (for hosting backend services)

---

## 📂 Project Structure

```bash
.
├── .expo/                 # Expo configuration
├── api/                   # Backend service files
├── assets/                # Static assets (images, icons, etc.)
├── components/            # Reusable UI components
├── data/                  # Sample data and utility files
├── navigation/            # Navigation configuration
├── redux/                 # Redux setup for state management
├── screens/               # Screen components for the app
├── App.js                 # Entry point for the app
├── package.json           # Dependencies and scripts
└── README.md              # Project documentation
```

# ⚡ Installation

## Prerequisites
- **Node.js**
- **MongoDB**
- **Expo CLI**

---

# Amazon Clone

## 🚀 Steps to Get Started

### Clone the Repository:
```bash
git clone https://github.com/Aravindhan-Senthilkumar/amazon-clone.git
cd amazon-clone


### Install Dependencies:
```bash
npm install
```

### Start the Backend Server:
1. Navigate to the `api/` folder.
2. Start the backend:
```bash
node server.js
```

### Start the Expo App:
```bash
expo start
```

---

## 📦 API Endpoints

### **User**
- `POST /api/register`: Register a new user.
- `POST /api/login`: Login with credentials.

### **Products**
- `GET /products`: Fetch all products.

### **Orders**
- `POST /orders`: Place a new order.

---

## 🌐 Live Demo
- **Frontend**: Deployed via Expo (https://drive.google.com/file/d/1rjsbA9fv1Pq0mbKMbQ--IiadQCWbdp05/view?usp=sharing).
- **Backend**: Hosted on Render (https://amazon-clone-server-cnk1.onrender.com).

---

## 🙌 Contributions
Contributions are welcome! Please feel free to submit a Pull Request.

---

## 📄 License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

