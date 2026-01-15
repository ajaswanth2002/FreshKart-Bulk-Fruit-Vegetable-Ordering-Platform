FreshKart – Bulk Fruit & Vegetable Ordering Platform

FreshKart is a full-stack web application for bulk ordering of fruits and vegetables, designed for retailers, hotels, restaurants, and vendors. It provides a modern React-based frontend and a Node.js + Express backend with SQLite for data storage.

⸻

🚀 Features

🧑‍💼 User Features
	•	Browse fruits and vegetables in bulk quantities
	•	Add products to cart
	•	Place orders easily
	•	Simple checkout and order success flow

🛠️ Admin Features
	•	View all bulk orders
	•	Manage products (via backend APIs)
	•	Lightweight and fast database using SQLite

⸻

🏗️ Tech Stack

Frontend
	•	React.js
	•	JavaScript (ES6)
	•	HTML5, CSS3
	•	Webpack

Backend
	•	Node.js
	•	Express.js
	•	SQLite3
	•	Nodemon

⸻

📁 Project Structure
```
FreshKart-Bulk-Fruit-Vegetable-Ordering-Platform/
│
├── frontend/
│   └── src/
│       ├── assets/
│       ├── components/
│       │   └── Navbar.js
│       ├── data/
│       │   ├── heroImages.js
│       │   └── products.js
│       ├── pages/
│       │   ├── Home.jsx
│       │   ├── Cart.jsx
│       │   ├── Order.jsx
│       │   ├── Payment.jsx
│       │   ├── Success.jsx
│       │   └── AdminOrders.jsx
│       ├── styles/
│       │   ├── Home.css
│       │   ├── Cart.css
│       │   ├── Navbar.css
│       │   └── Payment.css
│       ├── App.js
│       └── index.js
│
├── backend/
│   ├── routes/
│   │   ├── productRoutes.js
│   │   └── orderRoutes.js
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
├── .gitignore
├── README.md
└── package.json
```

⸻

⚙️ Installation & Setup

Prerequisites
	•	Node.js (v16+ recommended)
	•	npm

⸻

🔹 Backend Setup
```
cd backend
npm install
npm start
```
Server will run on:

http://localhost:5000


⸻

🔹 Frontend Setup

cd frontend
npm install
npm start

Frontend will run on:

http://localhost:3000/FreshKart-Bulk-Fruit-Vegetable-Ordering-Platform


⸻

🔌 API Endpoints

Products
	•	GET /products – Fetch all products
	•	POST /products – Add a product

Orders
	•	POST /orders – Place an order
	•	GET /orders – Fetch all orders

⸻

🧪 Database
	•	Uses SQLite3 for simplicity and fast access
	•	Ideal for small to medium-scale applications

⸻

📌 Future Enhancements
	•	User authentication (Login / Signup)
	•	Role-based access (Admin / User)
	•	Payment gateway integration
	•	Order tracking & status updates
	•	Cloud deployment (Render / AWS / Vercel)

⸻

👨‍💻 Author

Jaswanth Adhikarla
GitHub: https://github.com/ajaswanth2002

⸻

📄 License

This project is licensed under the MIT License.
