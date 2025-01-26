MERN Stack Chat App with Real-Time Messaging and JWT Authentication
🌟 Features
Authentication & Authorization with JWT (JSON Web Tokens).
Real-time messaging using Socket.io.
Online user status indicator.
Global state management using Zustand.
Error handling on both server and client sides.
Mobile-responsive UI with TailwindCSS & Daisy UI.
Easy deployment on platforms like Render.
🚀 Tech Stack
Backend: Node.js, Express.js
Frontend: React, TailwindCSS, Daisy UI
Database: MongoDB (with Mongoose)
Real-Time Communication: Socket.io
Authentication: JWT (JSON Web Token)
State Management: Zustand
File Upload: Cloudinary
Deployment: Render
🛠️ Running the Application
Prerequisites
Ensure you have the following installed on your machine:

Node.js: Download Node.js
MongoDB: Install MongoDB (for local development)
Cloudinary account for file upload functionality: Create an account
1. Clone the repository

git clone https://github.com/yourusername/mern-chat-app.git
cd mern-chat-app
2. Install dependencies

npm install
3. Set up environment variables

MONGO_URI=mongodb://localhost:27017/mern-chat-app
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_URL=your_cloudinary_url
4. Build the app

npm run build
5. Start the application
Backend

npm start
Frontend
The frontend is built into the build folder during the build process. Ensure that the frontend is correctly connected to the backend by starting both servers. You may need to adjust the proxy settings or deploy both to the same platform.

6. Access the app

http://localhost:5000
💡 Development Notes
For local development, make sure MongoDB is running, or configure it to connect to a remote MongoDB database.
For production, consider using services like Render or Heroku for deploying both the backend and frontend.
For file uploads, ensure you’ve set up your Cloudinary account correctly and the API keys are configured in your .env file.


🔧 Troubleshooting
Common Issues:
MongoDB connection failure: Ensure MongoDB is running locally or that you're using a cloud-based MongoDB service like Atlas.
JWT Token issues: Double-check the secret key and expiration time in your .env file.
Socket.io connection errors: Ensure the client and server are correctly connected and that both are running.
