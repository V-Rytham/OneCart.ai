# AI-Powered E-Commerce Website

A full-stack e-commerce project with a customer website, admin dashboard, and backend APIs.  
It supports product browsing, cart management, authentication, and order placement with Cash on Delivery and Razorpay.

## Tech Stack

### Frontend (User)
- React + Vite
- Tailwind CSS
- React Router
- Axios
- Firebase (Google sign-in related setup)

### Admin Panel
- React + Vite
- Tailwind CSS
- Axios

### Backend
- Node.js + Express
- MongoDB + Mongoose
- JWT auth with cookies
- Cloudinary (image upload)
- Razorpay (online payment)

## Main Features

- User registration/login with cookie-based auth
- Google login support
- Product listing and product detail flow
- Add to cart, update quantity, and cart total calculation
- Place order with:
  - Cash on Delivery
  - Razorpay online payment + verification
- Admin side product upload (multiple images), category/subcategory, sizes, and bestseller flag
- Admin order management (view all orders and update status)
- Basic AI voice-assistant style navigation on frontend (speech recognition + voice feedback)

## Project Structure

- `frontend/` → user-facing e-commerce app
- `admin/` → admin dashboard
- `backend/` → REST APIs, auth, product/cart/order logic

## Setup Instructions

### 1) Clone the project
```bash
git clone https://github.com/V-Rytham/AI-powered-E-Commerce-Website
cd AI-powered-E-Commerce-Website
