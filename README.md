# 🛒 King's Collection - E-commerce Web Application

King's Collection is a modern clothing e-commerce platform designed to deliver a seamless shopping experience. The application features a React-based frontend, a robust backend for order processing, and a comprehensive admin panel for efficient management.

## 🌐 Live Links

- Frontend: https://e-commerce-app-frontend-livid.vercel.app/

- Backend: https://e-commerce-app-baackend.vercel.app/

- Admin Panel: https://e-commerce-app-admin-kappa.vercel.app/

## ✨ Key Features

- Product Browsing: Users can view clothing items with images, ratings, and size options.
- Cart Management: Add, update, and remove items from the cart easily.
- User Authentication: Google login for easy access and personalized cart management.
- Payment Integration: Supports payments via Stripe and Razorpay, as well as a Cash on Delivery option.
- Order Management: Users can view their order history and track their orders.
- Admin Dashboard: Manage products, view orders, and track inventory seamlessly.
- Responsive Design: The application is optimized for both desktop and mobile devices.
- Wishlist & Reviews: Upcoming features to enhance customer engagement.
- Toast Notifications: User feedback for actions such as adding products to the cart and successful logins, using react-toastify.

## 🛠️ Technology Stack

### Frontend:

- React.js
- React Router for navigation
- Context API for state management
- Axios for API requests
- Tailwind CSS for styling
- Google Fonts: Custom fonts used ('Outfit' and 'Prata').
- React Toastify for notifications

### Backend:

- Node.js with Express for managing server-side logic
- MongoDB for data persistence (user, product, and order data)
- Cloudinary for image storage
- Payment gateways: Stripe and Razorpay

## 🚀 Getting Started

### Prerequisites

You will need to have Node.js and npm installed on your machine.

### Installation Steps

1. Clone the Repository:
```bash
git clone https://github.com/JigarHingu/ecommerce_app.git
cd ecommerce_app
```

2. Install Dependencies:

- Frontend:
```bash 
cd frontend
npm install
```

- Backend:
```bash
cd backend
npm install
```

3. Environment Variables: Create a .env file in the root directory and add the following variables:
```bash
MONGODB_URI=<your_mongoDB_URI>
STRIPE_SECRET_KEY=<your_stripe_secret_key>
RAZORPAY_KEY_ID=<your_razorpay_key_id>
RAZORPAY_KEY_SECRET=<your_razorpay_key_secret>
CLOUDINARY_NAME=<your_cloudinary_name>
CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_SECRET_KEY=<your_cloudinary_secret_key>
```

4. Start the Application:

- Run Backend:
```bash
cd backend
npm run start
```

- Run Frontend:
```bash
cd frontend
npm run dev
```

5. Access the Application:

- Frontend: http://localhost:5173/
- Backend: http://localhost:5000/

## 📚 Future Plans

- Implement wishlist and review features.
- Enhance filtering options for better product discovery.
- Improve UI/UX for a more intuitive shopping experience.
- Develop an admin dashboard with advanced analytics and reporting capabilities.

## 🤝 Contributions

Contributions are welcome! If you have suggestions, bug reports, or enhancements, please open an issue or submit a pull request. Thank you for your interest in King's Collection!