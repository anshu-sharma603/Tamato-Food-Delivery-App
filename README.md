# TOMATO - Food Ordering Website

This repository hosts the source code for TOMATO, a dynamic food ordering website built with the MERN Stack. It offers a user-friendly platform for seamless online food ordering.

## Demo

- User Panel: (https://tamato-food-delivery-app.vercel.app)
- Admin Panel:tamato-food-delivery-app-22du-lerbki3tl-anshusharma8981-8247.vercel.app

- 
## Features

- User Panel
- Admin Panel
- JWT Authentication
- Password Hashing with Bcrypt
- Stripe Payment Integration
- Login/Signup
- Logout
- Add to Cart
- Place Order
- Order Management
- Products Management
- Filter Food Products
- Authenticated APIs
- REST APIs
- Role-Based Identification
- Beautiful Alerts

## Run Locally

Clone the project

```bash
    git clone https://github.com/anshu-sharma603/Food-Delivery
```

Go to the project directory

```bash
    cd Food-Delivery
```

Install dependencies (frontend)

```bash
    cd frontend
    npm install
```

Install dependencies (admin)

```bash
    cd admin
    npm install
```

Install dependencies (backend)

```bash
    cd backend
    npm install
```

Setup Environment Variables

Make a `.env` file in the "backend" folder and store environment variables:

```
  JWT_SECRET=YOUR_SECRET_TEXT
  SALT=YOUR_SALT_VALUE
  MONGO_URL=YOUR_DATABASE_URL
  STRIPE_SECRET_KEY=YOUR_KEY
```

Setup the Frontend and Backend URL

- App.jsx in Admin folder
  const url = YOUR_BACKEND_URL

- StoreContext.js in Frontend folder
  const url = YOUR_BACKEND_URL

- orderController in Backend folder
  const frontend_url = YOUR_FRONTEND_URL

Start the Backend server

```bash
    nodemon server.js
```

Start the Frontend server

```bash
    npm run dev
```

Start the Admin server

```bash
    npm run dev
```

## Tech Stack

* [React](https://reactjs.org/)
* [Node.js](https://nodejs.org/en)
* [Express.js](https://expressjs.com/)
* [MongoDB](https://www.mongodb.com/)
* [Stripe](https://stripe.com/)
* [JWT Authentication](https://jwt.io/introduction)
* [Multer](https://www.npmjs.com/package/multer)

## Deployment

The application is deployed on Render.

## Contributing

Contributions are always welcome!
Just raise an issue, and we will discuss it.

## Feedback

If you have any feedback, please reach out to me [here](https://www.linkedin.com/in/anshu-sharma-67a58b343) or check out my [GitHub](https://github.com/anshu-sharma603).
