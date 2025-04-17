# Nike Commercial Website

A fully responsive commercial website for **Nike**, built using **React.js** for the frontend, **Node.js** for the backend, and **JSON** for dynamic data management. This project showcases Nike's latest products, features product filtering, a shopping cart, and user-friendly navigation.

## 🔥 Live Demo

[View Live Website](https://your-demo-link.com)

## 🛠 Tech Stack

- **Frontend:** React.js, Tailwind CSS / CSS Modules
- **Backend:** Node.js, Express.js
- **Data:** JSON (for product data), MongoDB or local JSON file
- **Tools:** Vite / Create React App, Postman, Git, npm

## 🚀 Features

- 🏷️ Product listing with filtering (men, women, kids)
- 🛍️ Shopping cart with add/remove/update quantity
- 🔍 Search bar for products
- 📱 Fully responsive design (mobile-first)
- 🧾 Product details page
- 🧑‍💼 Admin interface to manage product JSON (optional)
- 💬 Customer testimonials (static or fetched from JSON)
- 🧠 Uses modern ES6+ features

## 📁 Project Structure

nike-commercial-website/ │ ├── client/ # React frontend │ ├── public/ │ └── src/ │ ├── components/ │ ├── pages/ │ ├── App.jsx │ └── main.jsx │ ├── server/ # Node.js backend │ ├── routes/ │ ├── controllers/ │ ├── data/products.json # Product data │ └── server.js │ ├── README.md └── package.json

bash
Copy
Edit

## ⚙️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/nike-commercial-website.git
cd nike-commercial-website
Install frontend dependencies:


cd client
npm install
Install backend dependencies:


cd ../server
npm install
Start the development servers:


# Start backend
cd server
node server.js

# Start frontend
cd ../client
npm run dev  # or npm start if using CRA
🔗 API Endpoints
GET /api/products — Get all products

GET /api/products/:id — Get single product

POST /api/cart — Add to cart (future extension)

📦 Sample JSON Format

[
  {
    "id": "1",
    "name": "Nike Air Max",
    "price": 120,
    "category": "Men",
    "image": "/images/airmax.png",
    "description": "Stylish and comfortable shoes from Nike."
  }
]
📸 Screenshots
Add screenshots here if needed.

📃 License
This project is for educational/demo purposes only. Not affiliated with Nike Inc.

Author: Your Name
GitHub: yourusername

---

Let me know if you want the actual code files or need to deploy it as well!








