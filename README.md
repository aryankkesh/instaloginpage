S# Insta Login Page

Instagram-style signup/login page with a Node.js backend.

## Features
- User signup and login
- Passwords hashed with bcrypt
- JWT-based authentication
- Users stored in MongoDB Atlas

## Tech Stack
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express
- Database: MongoDB Atlas

## Run Locally
1. Clone the repo
   git clone https://github.com/aryankkesh/instaloginpage.git
   cd instaloginpage
2. Install dependencies
   npm install
3. Create a `.env` file with:
   MONGO_URI=your_mongodb_atlas_connection_string
   JWT_SECRET=your_secret_key
4. Start the server
   node server.js
5. Open http://localhost:3000 in your browser
