# 🛒 Full-Stack Ecommerce Website

A feature-rich and fully responsive Ecommerce Web Application built with MERN stack. It supports user authentication, shopping cart, order placement, multiple payment methods (Stripe, Razorpay, Cash on Delivery), and an admin panel for product/order management.

---

## 🚀 Features

### 👤 User Features
- Sign up / Login with JWT authentication
- Browse products by category or search
- View detailed product pages
- Add/Remove items from Cart
- Place orders with:
  - 💳 Stripe
  - 🪙 Razorpay
  - 💵 Cash on Delivery (COD)
- View past orders and order status
- Track order delivery progress

### 🛠 Admin Portal
- Admin login with role-based access
- Create, Edit, Delete products
- View and manage all customer orders
- Change order delivery status (e.g., Pending → Shipped → Delivered)
- Manage user accounts and roles
- Dashboard analytics (optional)

---

## 🧰 Tech Stack

| Frontend        | Backend        | Database | Payment Gateways |
|----------------|----------------|----------|------------------|
| React.js        | Node.js, Express | MongoDB  | Stripe, Razorpay |

---

## 🏁 Getting Started (Local Setup)

### 1. Clone the Repository
```bash
git clone https://github.com/kishangupta99/Ecommerce-Websites.git
cd Ecommerce-Websites




cd backend
npm install


PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret




cd ../frontend
npm install

REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_publishable_key
REACT_APP_RAZORPAY_KEY_ID=your_razorpay_key_id



# Backend
cd backend
npm start

# Frontend (in a new terminal)
cd frontend
npm start
