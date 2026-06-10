# 🛒 Full Stack E-Commerce Website

A modern **Full Stack E-Commerce Website** built using the **MERN Stack** with secure authentication, product management, cart functionality, online payments, and admin dashboard.

## 🚀 Features

### 👤 User Features
- User Registration & Login
- JWT Authentication
- Secure Password Hashing
- Browse Products
- Product Search & Filter
- Add to Cart
- Update Cart Quantity
- Place Orders
- Online Payment Integration
- Order History
- Responsive UI

### 🛠️ Admin Features
- Admin Dashboard
- Add Products
- Edit Products
- Delete Products
- Manage Orders
- Manage Users

### 💳 Payment Gateway
- Razorpay Payment Integration
- Secure Payment Verification

---

## 🏗️ Tech Stack

### Frontend
- React.js
- Vite
- React Router DOM
- Axios
- Context API
- Tailwind CSS / CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js

### Other Tools
- Cloudinary (Image Upload)
- Multer
- Razorpay
- Nodemailer

---

## 📂 Project Structure

```bash
project-root/
│── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
│── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   └── server.js
│
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install Dependencies

#### Frontend

```bash
cd frontend
npm install
```

#### Backend

```bash
cd backend
npm install
```

---

## 🔐 Environment Variables

Create a `.env` file inside backend folder and add:

```env
PORT=8000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret

EMAIL_USER=your_email
EMAIL_PASS=your_password

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

FRONTEND_URL=http://localhost:5173
```

---

## ▶️ Run Project

### Start Backend

```bash
cd backend
npm run server
```

### Start Frontend

```bash
cd frontend
npm run dev
```

---

## 📸 Screenshots

### Home Page
(Add Screenshot Here)

### Product Page
(Add Screenshot Here)

### Cart Page
(Add Screenshot Here)

### Admin Dashboard
(Add Screenshot Here)

---

## API Endpoints

### Authentication

| Method | Endpoint | Description |
|---------|-----------|-------------|
| POST | `/api/auth/register` | Register User |
| POST | `/api/auth/login` | Login User |
| GET | `/api/auth/user` | Get User Profile |

### Products

| Method | Endpoint |
|---------|-----------|
| GET | `/api/products` |
| GET | `/api/products/:id` |
| POST | `/api/products` |
| PUT | `/api/products/:id` |
| DELETE | `/api/products/:id` |

### Orders

| Method | Endpoint |
|---------|-----------|
| POST | `/api/orders` |
| GET | `/api/orders/my-orders` |

---

## 🔒 Authentication Flow

1. User registers or logs in.
2. JWT token is generated.
3. Token is stored in localStorage/cookies.
4. Protected routes are accessed using middleware.

---

## 🌟 Future Improvements

- Wishlist Feature
- Product Reviews & Ratings
- Coupon System
- Stripe Payment Gateway
- Dark Mode
- Advanced Filters

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push branch

```bash
git push origin feature-name
```

5. Open Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Manjeet Kumar**

GitHub: https://github.com/your-github-username
