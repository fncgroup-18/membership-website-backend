# MemberHub Backend

Backend API for the MemberHub membership management system.

## Features

- User Authentication (JWT)
- Company Profile Management
- Membership Management
- RESTful API endpoints

## Tech Stack

- Node.js
- Express.js
- MongoDB
- JWT for authentication

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Create a `.env` file with:
   ```
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   PORT=3000
   ```

3. Run the server:
   ```bash
   node server.js
   ```

## API Endpoints

- POST `/api/auth/signup` - User registration
- POST `/api/auth/login` - User login
- GET `/api/users/profile` - Get user profile
- PUT `/api/users/profile` - Update user profile

## Deployment

The backend is configured for deployment on Render.com using the `render.yaml` configuration file.
