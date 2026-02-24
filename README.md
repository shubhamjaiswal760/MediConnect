# MediConnect

MediConnect is a full-stack telemedicine platform that enables seamless healthcare management through three different user interfaces:

- Patient Portal
- Doctor Dashboard
- Admin Panel

---

## Features

### Patient

- User registration and profile management
- Browse doctors by specialty and availability
- Real-time appointment booking with time slots
- Online payment integration (Razorpay and Stripe)
- View appointment history and track status

### Doctor

- Secure login and profile management
- Dashboard with earnings and statistics
- Manage appointments (view, complete, cancel)
- Toggle availability status
- Update profile details

### Admin

- System dashboard with analytics
- Add and manage doctors
- Monitor and manage all appointments
- Manage users and system settings

---

## Tech Stack

Frontend:
- React.js
- Tailwind CSS

Backend:
- Node.js
- Express.js

Database:
- MongoDB

Authentication:
- JWT (JSON Web Tokens)

Other Integrations:
- Cloudinary (Image storage)
- Razorpay (Indian payments)
- Stripe (International payments)

---

## Environment Variables

Create a `.env` file in the backend directory and add the following variables:

CURRENCY=

JWT_SECRET=

ADMIN_EMAIL=

ADMIN_PASSWORD=

MONGODB_URI=

CLOUDINARY_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_SECRET_KEY=

RAZORPAY_KEY_ID=

RAZORPAY_KEY_SECRET=

STRIPE_SECRET_KEY=


---

## Installation

1. Clone the repository

```
git clone <your-repo-link>
```

2. Install backend dependencies

```
cd backend
npm install
```

3. Install frontend dependencies

```
cd frontend
npm install
```

4. Run backend server

```
npm run server
```

5. Run frontend

```
npm run dev
```
Shubham Jaiswal  
Email: shubhamjais700@gmail.com
