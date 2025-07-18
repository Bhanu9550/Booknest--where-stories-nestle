# 📚 Book Store

A full-stack MERN (MongoDB, Express, React, Node.js) book store application with user, seller, and admin dashboards.


---

## 🚀 Key Features

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

## 📌 Future Enhancements
- Payment Gateway: Integrate Stripe/PayPal.
- Advanced Search: AI-based book recommendations.
- Mobile App: React Native version.
- Analytics Dashboard: Visualize sales trends.

## 🐞 Known Issues
- UI inconsistencies on mobile screens.
- No email notifications for orders (future scope).

## ⚙️ Setup

### Prerequisites
- Node.js ≥16.x  
- MongoDB Atlas URI or local instance  

### Backend Setup & Frontend Setup
```bash
# Install dependencies
npm install express mongoose cors jsonwebtoken dotenv

# Create .env file
echo "PORT=5000
DB_URI=mongodb+srv://<username>:<password>@cluster0.example.mongodb.net/bookstore
JWT_SECRET=your_secret_key" > .env

# Start server
npm start  

# Frontend Setup

cd ../client

# Install dependencies
npm install axios react-router-dom react-bootstrap

# Start dev server
npm run dev
