FreshKart – Bulk Fruit & Vegetable Ordering Platform

FreshKart is a full-stack web application designed for bulk ordering of fruits and vegetables, mainly targeted at retailers, hotels, restaurants, and vendors. The platform allows users to browse products, place bulk orders, and manage orders efficiently.

⸻

🚀 Features

👤 User Features
	•	Browse available fruits and vegetables
	•	View product details (price, quantity, category)
	•	Place bulk orders easily
	•	Simple and clean user interface

🛠️ Admin / Backend Features
	•	RESTful APIs for products and orders
	•	Add, update, and delete products
	•	Manage bulk orders
	•	SQLite database integration

⸻

🏗️ Tech Stack

Frontend
	•	HTML
	•	CSS
	•	JavaScript

Backend
	•	Node.js
	•	Express.js
	•	SQLite3
	•	Nodemon (for development)

⸻

📁 Project Structure

FreshKart-Bulk-Fruit-Vegetable-Ordering-Platform/
│
├── frontend/              # Frontend files
│   ├── index.html
│   ├── css/
│   └── js/
│
├── backend/               # Backend server
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


⸻

⚙️ Installation & Setup

Prerequisites
	•	Node.js (v16 or above recommended)
	•	npm

Steps to Run the Project
	1.	Clone the repository

git clone https://github.com/ajaswanth2002/FreshKart-Bulk-Fruit-Vegetable-Ordering-Platform.git

	2.	Navigate to backend folder

cd FreshKart-Bulk-Fruit-Vegetable-Ordering-Platform/backend

	3.	Install dependencies

npm install

	4.	Start the server

npm start

OR (for development)

npx nodemon server.js

	5.	Open frontend

	•	Open frontend/index.html in your browser

⸻

🔌 API Endpoints

Products
	•	GET /products – Get all products
	•	POST /products – Add a new product

Orders
	•	POST /orders – Place a bulk order
	•	GET /orders – View all orders

⸻

🧪 Database
	•	Uses SQLite3 for lightweight and fast data storage
	•	Suitable for small to medium-scale applications

⸻

📌 Future Enhancements
	•	User authentication (Login / Signup)
	•	Role-based access (Admin / Customer)
	•	Payment gateway integration
	•	Order tracking
	•	Deployment on cloud (AWS / Render / Vercel)

⸻

👨‍💻 Author

Jaswanth Adhikarla
GitHub: ajaswanth2002￼

⸻

📄 License

This project is licensed under the MIT License.
