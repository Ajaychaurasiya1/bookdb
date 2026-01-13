MERN Blogging Platform

A full-featured MERN stack blogging platform that allows users to create, read, update, and delete blog posts with a responsive and intuitive user interface.

Features

User Authentication & Authorization: Secure login/signup with JWT; protected routes for user-specific actions.

CRUD Operations: Create, read, update, and delete blog posts seamlessly.

Comment System: Users can comment on posts.

Responsive UI: Built with React.js, ensuring a smooth experience across devices.

RESTful APIs: Backend built with Node.js and Express.js, following modular architecture.

Database: MongoDB used for storing users, posts, and comments.

Tech Stack

Frontend: React.js, HTML5, CSS3, JavaScript

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT (JSON Web Tokens)

Tools & Libraries: Postman (API testing), Git/GitHub (version control)

Installation

Clone the repository:

git clone https://github.com/your-username/mern-blog-app.git


Install dependencies for both frontend and backend:

cd backend
npm install
cd ../frontend
npm install


Create a .env file in the backend folder with the following:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000


Run the backend server:

cd backend
npm start


Run the frontend:

cd frontend
npm start


Open http://localhost:3000
 to view the app.

Usage

Register or log in to access full functionality.

Create, edit, or delete your blog posts.

Comment on posts and explore content from other users.

Folder Structure
mern-blog-app/
│
├── backend/          # Node.js + Express API
│   ├── controllers/  # API route controllers
│   ├── models/       # MongoDB models
│   ├── routes/       # Express routes
│   ├── middleware/   # Auth & error handling
│   └── server.js
│
└── frontend/         # React frontend
    ├── src/
    │   ├── components/ # Reusable UI components
    │   ├── pages/      # App pages
    │   ├── services/   # API calls
    │   └── App.js

Contributing

Fork the repository

Create your branch (git checkout -b feature/YourFeature)

Commit your changes (git commit -m 'Add some feature')

Push to the branch (git push origin feature/YourFeature)

Open a Pull Request

License

This project is licensed under the MIT License.
