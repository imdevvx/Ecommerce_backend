# 🛍️ E-Commerce Backend

A **production-ready E-Commerce Backend API** built using **Node.js, Express, and MongoDB**.  
This is a **real-world application backend** designed to handle authentication, product management, cart operations, and order processing at scale.

---

## 🚀 Overview

This backend powers the **DVL (clothing brand) E-Commerce platform**, enabling a complete shopping experience:

- Browse products  
- Add items to cart  
- Secure authentication (OTP-based)  
- Place and manage orders  
- Handle user profiles and addresses  

Built with a focus on **scalability, security, and clean architecture**.

---

## 🔄 Application Flow

1. User visits the website  
2. Browses products  
3. Selects a product  
4. Adds to cart  
5. Signs up / logs in (OTP verification via email)  
6. Authenticated using JWT  
7. Proceeds to checkout  
8. Adds address  
9. Places order  
10. Views order history  

---

## ✨ Features

### 🔐 Authentication & Security
- JWT-based authentication  
- Password hashing using bcrypt  
- OTP-based signup/login using SendGrid  
- Forgot password & reset password functionality  

### 🛒 Cart System
- Add items to cart  
- Update quantity  
- Remove items  
- Persistent cart per user  

### 📦 Order Management
- Create orders  
- Track order details  
- Store order history  

### 📍 Address Management
- Add, update, delete addresses  
- Multiple address support  

### 🛍️ Product & Category
- Product listing  
- Category-based filtering  
- Structured product management  

---

## 🗂️ Database Models

The backend uses MongoDB with the following models:

- **User Model**  
- **Product Model**  
- **Category Model**  
- **Cart Model**  
- **Order Model**  
- **Address Model**  
- **OTP Model**  
- **Reset Password Model**  

---

## 📡 API Routes

| Route | Description |
|------|-------------|
| `/api/product` | Product operations |
| `/api/category` | Category management |
| `/api/auth` | Authentication & user actions |
| `/api/cart` | Cart operations |
| `/api/order` | Order processing |
| `/api/address` | Address management |

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB, Mongoose  
- **Authentication:** JWT, bcrypt  
- **Email Service:** SendGrid (OTP system)  
- **Environment Config:** dotenv  
- **Middleware:** CORS, JSON parsing  

---

## ⚙️ Setup & Installation

### 1. Clone the repository
```
git clone https://github.com/syncdecodes/your-repo-name.git
cd your-repo-name
```
### 2. Install dependencies
``` 
npm install
```

### 3. Create a .env file
```
PORT=5000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key
SENDGRID_API_KEY=your_sendgrid_api_key
```

### 4. Run the server
```
npm start
# or
npm run dev
```

## 🧪 Base Route
- **GET /**
- Response:
```
{
  "msg": "Ecommerce backend server is listening.."
}
```

## 📈 Highlights

- Real-world backend system

- Clean and modular architecture

- Secure authentication & authorization

- OTP-based email verification

- Scalable database design

- RESTful API structure

## 🤝 Contributions

This is a personal production-level project, so contributions aren’t expected —
but feedback, suggestions, and improvements are always welcome!

## ✍️ AUTHOR

DEV

Created by [syncdecodes](https://github.com/syncdecodes)
