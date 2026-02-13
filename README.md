# Photo Studio Website - Backend

This repository contains the Node.js + Express backend powering a full-stack web application developed for a local photo studio.

The backend provides REST API endpoints for:

- Order creation and management
- Secure login and authentication
- Dynamic pricing configuration
- Payment processing via Stripe
- Email notifications

It integrates with MongoDB using Mongoose for persistent storage and implements JWT-based authentication with password hashing via bcrypt.

## Technical Highlights

- Express-based REST API architecture
- MongoDB persistence using Mongoose ODM
- JWT-based authentication & authorization
- Password hashing with bcrypt
- Stripe payment intent integration
- Email handling via Nodemailer
- Structured middleware (request logging, unknown endpoint handling, centralized error handling)
- Environment-based configuration via dotenv
