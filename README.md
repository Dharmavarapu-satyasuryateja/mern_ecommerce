# MERN E-Commerce Platform

A full-featured e-commerce application built with the MERN stack (MongoDB, Express, React, Node.js), featuring user authentication, product management, shopping cart, and order processing.

## 🌟 Features

- ✨ User Authentication (Register & Login)
- 🛍️ Product Catalog with Filtering & Search
- 🛒 Shopping Cart Management
- 💳 Order Processing & History
- 👤 User Profile Management
- 📦 Order Tracking
- ⭐ Product Reviews & Ratings
- 🎨 Responsive UI Design

## 🛠 Tech Stack

- **Frontend:** React.js, JavaScript, CSS3, HTML5
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Deployment:** Vercel (Frontend), [Backend URL]
- **Authentication:** JWT (JSON Web Tokens)

## 🚀 Getting Started

### Prerequisites

- Node.js (v14+)
- npm or yarn
- MongoDB (local or Atlas)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Dharmavarapu-satyasuryateja/mern_ecommerce.git
cd mern_ecommerce
```

2. Install backend dependencies:
```bash
cd server
npm install
```

3. Install frontend dependencies:
```bash
cd ../client
npm install
```

4. Set up environment variables:

**Server (.env):**
```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

**Client (.env.local):**
```
REACT_APP_API_URL=http://localhost:5000
```

### Running Locally

**Terminal 1 - Backend:**
```bash
cd server
npm start
# Backend runs on http://localhost:5000
```

**Terminal 2 - Frontend:**
```bash
cd client
npm start
# Frontend runs on http://localhost:3000
```

## 📁 Project Structure

```
mern_ecommerce/
├── client/                 # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   ├── package.json
│   └── README.md
├── server/                 # Node.js Backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── server.js
│   └── package.json
└── README.md
```

## 🔗 Live Demo

**Frontend:** [View Live](https://mern-ecommerce-iota-inky.vercel.app)

## 📸 Screenshots

[Add screenshots/GIFs showing:]
- Homepage & Product Listing
- Product Details Page
- Shopping Cart
- Checkout Process
- Order Confirmation

## 💡 Usage

1. **Browse Products:** Navigate to the home page to see available products
2. **Add to Cart:** Click "Add to Cart" on any product
3. **View Cart:** Click the cart icon to review items
4. **Checkout:** Proceed to checkout and enter shipping details
5. **Track Orders:** View order history in your profile

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Reporting Issues

Found a bug? Please open an issue with:
- Description of the bug
- Steps to reproduce
- Expected vs. actual behavior
- Screenshots (if applicable)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Satya Suryateja Dharmavarapu**
- GitHub: [@Dharmavarapu-satyasuryateja](https://github.com/Dharmavarapu-satyasuryateja)
- Email: [Add your email]
- LinkedIn: [Add your LinkedIn]

## 🙏 Acknowledgments

- [Add any resources, tutorials, or inspirations]
- MongoDB documentation
- React.js official guides
- Express.js best practices

## 📧 Questions or Suggestions?

Feel free to open an issue or contact me directly!

---

**Made with ❤️ by Satya Suryateja**