# Full Stack E-Commerce Website

A modern, feature-rich e-commerce platform built with the MERN stack (MongoDB, Express.js, React, Node.js) and additional technologies for enhanced functionality.

## 🚀 Features

- **User Authentication & Authorization**
  - Secure user registration and login
  - JWT-based authentication
  - Protected routes
  - User profile management

- **Product Management**
  - Product listing and categorization
  - Product search and filtering
  - Product details with images
  - Admin product management

- **Shopping Experience**
  - Shopping cart functionality
  - Wishlist feature
  - Product reviews and ratings
  - Responsive design for all devices

- **Payment Integration**
  - Secure payment processing with Stripe
  - Multiple payment methods
  - Order tracking and history

- **Additional Features**
  - Email notifications using Nodemailer
  - AI-powered features using Google's Generative AI
  - Real-time updates
  - Responsive UI with Tailwind CSS

## 🛠️ Technologies Used

### Frontend
- **React.js** - Frontend framework
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **React Spring** - Animation library
- **Axios** - HTTP client
- **Context API** - State management
- **React Router** - Navigation and routing

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - MongoDB object modeling
- **JWT** - Authentication
- **Bcrypt** - Password hashing
- **Multer** - File upload handling
- **Nodemailer** - Email functionality

### Payment & External Services
- **Stripe** - Payment processing
- **Google Generative AI** - AI features
- **Nodemailer** - Email services

## 📦 Project Structure

```
├── src/                    # Frontend source code
│   ├── assets/            # Static assets
│   ├── Components/        # Reusable components
│   ├── Context/          # React context providers
│   ├── Pages/            # Page components
│   └── App.jsx           # Main application component
│
├── Backend/               # Backend source code
│   ├── config/           # Configuration files
│   ├── controllers/      # Route controllers
│   ├── middlewares/      # Custom middlewares
│   ├── models/           # Database models
│   ├── routes/           # API routes
│   └── server.js         # Entry point
│
└── backend_stripe/       # Stripe integration
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn
- Stripe account (for payment processing)

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd Full-Stack-Ecommerce-Website
```

2. Install frontend dependencies:
```bash
npm install
```

3. Install backend dependencies:
```bash
cd Backend
npm install
cd ..
```

4. Set up environment variables:
Create `.env` files in both root and Backend directories with necessary configurations.

### Running the Application

1. Start the backend server:
```bash
cd Backend
npm start
```

2. In a new terminal, start the frontend:
```bash
npm run dev
```

The application will be available at:
- Frontend: http://localhost:5173
- Backend: http://localhost:5000

## 🔧 Environment Variables

### Backend (.env)
```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
EMAIL_SERVICE=your_email_service
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```

### Frontend (.env)
```
VITE_API_URL=http://localhost:5000
VITE_STRIPE_PUBLIC_KEY=your_stripe_public_key
```

## 🛠️ Development

- Frontend development server with hot reload
- Backend API endpoints
- MongoDB database connection
- Stripe payment integration
- Email service configuration

## 📝 API Documentation

### Authentication Endpoints
- POST /api/auth/register - User registration
- POST /api/auth/login - User login
- GET /api/auth/profile - Get user profile

### Product Endpoints
- GET /api/products - Get all products
- GET /api/products/:id - Get single product
- POST /api/products - Create product (admin)
- PUT /api/products/:id - Update product (admin)
- DELETE /api/products/:id - Delete product (admin)

### Order Endpoints
- POST /api/orders - Create order
- GET /api/orders - Get user orders
- GET /api/orders/:id - Get single order

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- Your Name - Initial work

## 🙏 Acknowledgments

- React.js community
- MongoDB documentation
- Stripe API documentation
- Google AI services 