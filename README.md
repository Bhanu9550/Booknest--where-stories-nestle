# 📚 SmartBridge Book Store

A full-stack MERN (MongoDB, Express, React, Node.js) book store application with user, seller, and admin dashboards.

![Landing Page](media/image6.png)

---

## 🚀 Features

### **User**
- ✅ Register, login, and manage profile  
- 🔍 Browse books by genre/author  
- 🛒 Add to cart & checkout  
- 📖 Track orders/wishlists  
- ⭐ Leave reviews  

### **Seller**
- 📝 Add/edit book listings  
- 📦 Manage inventory (quantity/condition)  
- 🚚 Process orders  

### **Admin**  
- 👥 Manage users/sellers  
- 📊 Sales analytics  
- 🛠️ Platform oversight  

---

## 🛠️ Tech Stack

| Frontend          | Backend         | Database   | Tools            |
|-------------------|-----------------|------------|------------------|
| React.js          | Node.js         | MongoDB    | Axios (API calls)|
| React Router      | Express.js      | Mongoose   | Bootstrap        |
| Context API       | JWT Auth        |            | Vite             |

---

## ⚙️ Setup

### Prerequisites
- Node.js ≥16.x  
- MongoDB Atlas URI or local instance  

### Backend Setup
```bash
# Clone repo
git clone https://github.com/your-username/smartbridge-bookstore.git
cd smartbridge-bookstore/server

# Install dependencies
npm install express mongoose cors jsonwebtoken dotenv

# Create .env file
echo "PORT=5000
DB_URI=mongodb+srv://<username>:<password>@cluster0.example.mongodb.net/bookstore
JWT_SECRET=your_secret_key" > .env

# Start server
npm start
