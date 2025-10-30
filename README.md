🛒 E-Commerce Cart System

A simple and fully functional E-Commerce Cart System built with modern web technologies.
This project allows users to browse products, add them to their shopping cart, adjust quantities, and place orders — mimicking a real-world online shopping experience.

🚀 Features

🧩 User Features

Browse available products with images, names, and prices.

Add, remove, and update items in the cart.

View total cart value in real-time.

Save cart items using local storage or database.

Proceed to checkout (dummy or integrated payment flow).


⚙️ Admin Features (optional)

Add, edit, and delete products.

Manage product inventory.

View customer orders.



---

🛠️ Tech Stack

Category	Technologies

Frontend	HTML, CSS, JavaScript (or React / Vue / Angular)
Backend	Node.js, Express.js (or PHP / Django / Laravel / etc.)
Database	MongoDB / MySQL / Firebase
API	RESTful API for product and cart management
Version Control	Git & GitHub

📂 Folder Structure

ecommerce-cart-system/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   │   ├── products.js
│   │   └── cart.js
│   ├── models/
│   │   ├── Product.js
│   │   └── Cart.js
│   └── db/
│       └── connect.js
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   ├── pages/
│   │   ├── cart.html
│   │   └── checkout.html
│   └── assets/
│       └── images/
│
├── package.json
├── README.md
└── .gitignore

⚡ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/yourusername/ecommerce-cart-system.git
cd ecommerce-cart-system

2️⃣ Install dependencies

npm install

3️⃣ Setup environment variables

Create a .env file in the root folder and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string

4️⃣ Start the server

npm start

5️⃣ Run the frontend

If using a static frontend:

open frontend/index.html

Or if using React:

npm run dev

🧠 API Endpoints

Method	Endpoint	Description

GET	/api/products	Get all products
GET	/api/products/:id	Get single product
POST	/api/cart	Add product to cart
GET	/api/cart	View cart items
PUT	/api/cart/:id	Update item quantity
DELETE	/api/cart/:id	Remove item from cart


💾 Example JSON Data

Product Example

{
  "id": "p01",
  "name": "Wireless Headphones",
  "price": 1299,
  "image": "/assets/images/headphones.jpg",
  "category": "Electronics"
}

Cart Example

{
  "userId": "u01",
  "items": [
    {
      "productId": "p01",
      "quantity": 2
    }
  ],
  "totalAmount": 2598


🎨 UI Preview

Page	Description

🏠 Home Page	Displays all available products
🛍 Product Page	View detailed info and add to cart
🛒 Cart Page	Shows selected items and total
💳 Checkout Page	Order summary and confirmation



---

🧩 Future Enhancements

User authentication (login/signup)

Payment gateway integration (Stripe / Razorpay)

Order history & tracking

Wishlist system

Admin dashboard

🤝 Contributing

1. Fork the repository


2. Create your feature branch (git checkout -b feature/new-feature)


3. Commit your changes (git commit -m "Add new feature")


4. Push to the branch (git push origin feature/new-feature)


5. Create a new Pull Request

📜 License

This project is licensed under the MIT License — feel free to use and modify it.

🧑‍💻 Author

Your Name
📧 your.email@example.com
🌐 yourportfolio.com
🐙 GitHub
