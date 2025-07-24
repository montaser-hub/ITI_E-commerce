# ITI_Ecommerce 🛍️

A fully functional E-Commerce web application built using **HTML, CSS, and Vanilla JavaScript**.

This project supports two user types:
- **Admin**: Product & order management
- **Customer**: Product browsing, cart, wishlist, ordering

---

## 🚀 Features

### 👥 User Management
- Admin & Customer login/register
- Full validation and error messages
- Logout functionality

### 🛒 Product System
Each product includes:
- ID
- Name
- Image
- Category
- Price
- Description
- Stock Quantity

---

## 🔧 Admin Panel
- ✅ CRUD operations on products
- ✅ CRUD operations on categories
- ✅ View all customer orders
- ✅ Confirm/Reject orders

---

## 🛍️ Customer Interface
- 🔍 View & filter products
- ❤️ Add/remove from wishlist (stored in localStorage)
- 🛒 Add/remove from shopping cart
- 📦 Place orders (initially "pending")
- 📄 View order history

---

## 💾 Data Storage
- Uses **Firebase Realtime Database** or **Local Storage**

---

## 🎁 Bonus Features
- 💳 PayPal sandbox integration for payments
- ⭐ Product rating & feedback system
- 🔄 Return orders functionality

---

## 📁 Project Structure (Vanilla JS)


/ecommerce/
├── index.html
├── register.html
├── admin/
│ ├── dashboard.html
│ ├── products.html
│ ├── categories.html
│ └── orders.html
├── customer/
│ ├── home.html
│ ├── cart.html
│ ├── wishlist.html
│ └── orders.html
├── css/
│ └── styles.css
├── js/
│ ├── auth.js
│ ├── product.js
│ ├── cart.js
│ ├── order.js
│ └── firebase.js
└── assets/

## 📦 Technologies Used
- HTML5
- CSS3 (No theme libraries used)
- JavaScript (ES6+)
- Firebase (or localStorage fallback)
- PayPal JS SDK

---

## 🌐 Live Demo (optional)
You can deploy your project using:
- GitHub Pages
- Netlify
- Firebase Hosting

---

## 📜 License
This project is open-source under the [MIT License](LICENSE).

---

## 🤝 Contributions
Pull requests are welcome. For major changes, open an issue first to discuss what you’d like to change.


