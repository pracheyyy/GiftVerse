<div align="center">

# GiftVerse

### Personalized Gifts for Every Occasion 💝

An Amazon-inspired full-stack e-commerce platform dedicated to personalized and unique gifts. Users can browse products, customize gifts, manage orders, track deliveries, and discover perfect gift recommendations.

![React](https://img.shields.io/badge/React-19-blue)
![NodeJS](https://img.shields.io/badge/Node.js-green)
![MongoDB](https://img.shields.io/badge/MongoDB-brightgreen)
![Express](https://img.shields.io/badge/Express-black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38BDF8)

</div>

---

## 🌟 Overview

GiftVerse is a modern full-stack e-commerce application inspired by Amazon but designed specifically for gifting and personalized products.

The platform allows users to:

- Browse thousands of gifts
- Search and filter products
- Create wishlists
- Add products to cart
- Customize gifts
- Place secure orders
- Track deliveries
- Manage profiles and addresses

Administrators can:

- Manage products
- Manage categories
- Track orders
- View analytics
- Create coupons
- Manage customers

---

## 🚀 Features

### 👤 User Features

- User Authentication
- Secure Login & Registration
- JWT Authorization
- Forgot Password
- User Profile Management
- Address Management
- Wishlist
- Shopping Cart
- Product Reviews & Ratings
- Order Tracking
- Order History
- Personalized Gift Upload

### 🛍 Shopping Features

- Product Search
- Category Filters
- Price Filters
- Rating Filters
- Personalized Gifts
- Related Products
- Product Recommendations
- Coupon Codes
- Gift Wrapping Option

### 💳 Payment Features

- Razorpay Integration
- UPI Payments
- Debit/Credit Cards
- Cash on Delivery

### 🛠 Admin Features

- Dashboard Analytics
- Product Management
- Category Management
- Order Management
- User Management
- Coupon Management
- Sales Reports

### 🤖 AI Features

- AI Gift Recommendation System
- Occasion-Based Suggestions
- Budget-Based Suggestions
- Personalized Product Recommendations

---

## 📸 Screenshots

### Home Page

```text
Hero Banner
Trending Gifts
Categories
Best Sellers
Reviews
```

### Product Page

```text
Product Images
Product Details
Ratings
Reviews
Add To Cart
Buy Now
```

### Admin Dashboard

```text
Revenue Analytics
Orders
Products
Customers
```

---

## 🏗 Project Structure

```bash
giftverse/

├── frontend/
│
├── backend/
│
├── uploads/
│
├── docs/
│
├── README.md
│
└── package.json
```

---

## 🧰 Tech Stack

### Frontend

- React.js
- React Router
- Redux Toolkit
- Axios
- Tailwind CSS
- Framer Motion

### Backend

- Node.js
- Express.js
- JWT Authentication
- Bcrypt
- Multer

### Database

- MongoDB Atlas

### Payment Gateway

- Razorpay

### Deployment

- Vercel
- Render
- MongoDB Atlas

---

## 📂 Database Models

### User

```javascript
{
  name,
  email,
  password,
  avatar,
  role,
  addresses
}
```

### Product

```javascript
{
  title,
  description,
  category,
  price,
  stock,
  images,
  ratings,
  reviews
}
```

### Order

```javascript
{
  user,
  products,
  totalPrice,
  paymentStatus,
  shippingStatus
}
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/giftverse.git
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

---

## 🌍 Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=5000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_secret

RAZORPAY_KEY_ID=your_key

RAZORPAY_SECRET=your_secret
```

---

## 📈 Future Enhancements

- AI Chatbot
- Gift Reminder System
- Referral Program
- Social Login
- Multi-Vendor Support
- Real-Time Order Tracking
- Voice Search
- Gift Subscription Boxes

---

## 🤝 Contributing

Contributions are welcome!

1. Fork Repository
2. Create Feature Branch
3. Commit Changes
4. Open Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Prachi Patil**

B.Tech Information Technology Student

Aspiring Software Engineer | Frontend Developer | Data Analyst
