# real-estate-backend
A comprehensive Node.js backend for a real estate application, providing advanced features including user authentication, property management, search functionality, and transaction processing. Utilizes PostgreSQL for the database, Redis for caching, and integrates various services to ensure high performance and scalability
# Real Estate Backend

## Description

This repository contains the backend code for a real estate application, offering a range of features from user authentication to property management and transaction processing. It uses Node.js with Express for the server, PostgreSQL for the database, and Redis for caching.

## Features

- User Authentication
  - Registration
  - Login
  - Forgot Password
  - Reset Password
  - Email Verification with 6-Digit Codes
- Property Management
  - Add/Edit/Delete Properties
  - Property Listings
- Search Functionality
  - Filter by Location, Price, Property Type, etc.
- Transaction Processing
  - Initiate and Track Transactions
- Redis Caching for Performance and Security

## Technologies Used

- Node.js
- Express
- PostgreSQL
- Sequelize (ORM)
- Redis
- JWT for Authentication
- Bcrypt for Password Hashing
- Nodemailer for Emailing

## Getting Started

### Prerequisites

- Node.js and npm
- PostgreSQL
- Redis
- An email service (e.g., SMTP server)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/real-estate-backend.git
   cd real-estate-backend
   
