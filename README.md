
Job Portal Application

A comprehensive job portal application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application allows job seekers to browse job listings, apply for jobs, and manage applications seamlessly. Employers can post jobs, view applications, and manage their listings—all in one platform.





Features
User Authentication: Secure and role-based authentication using JWT (JSON Web Tokens) for both job seekers and employers.

Job Listings: Browse through a wide range of job listings fetched from MongoDB.

Application Management:
Job seekers can manage their job applications.
Employers can view and manage received applications.
Responsive Design: Optimized for a seamless experience across all devices.
Image Upload: Integrated with Cloudinary for storing and managing uploaded images.


Technologies Used
Frontend

React.js

React Router

Bootstrap

Backend

Node.js

Express.js


MongoDB

Authentication


Deployment
Frontend: Vercel
Backend: Render
Database: MongoDB Atlas
Getting Started
\





Prerequisites
Node.js (v22.2.0 or above) installed on your machine
MongoDB Atlas account (or a local MongoDB server)
Cloudinary account for image storage
Installation
Clone the repository:


git clone https://github.com/Arvind7Goud/Job-portal.git
Navigate to the project directory:

cd Job-portal
Install dependencies for the backend:

cd backend
npm install
Install dependencies for the frontend:

cd ../frontend
npm install
Set up environment variables:

Create a config.env file inside a config folder in the backend directory.
Add the following variables and replace the placeholders with your specific configuration:
plaintext


PORT=5000
CLOUDINARY_API_KEY=your_cloudinary_api_key

CLOUDINARY_API_SECRET=your_cloudinary_api_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name

FRONTEND_URL=http://localhost:3000

DB_URL=your_mongodb_connection_string

JWT_SECRET_KEY=your_jwt_secret

JWT_EXPIRE=7d

COOKIE_EXPIRE=7

Run the application:

Start the backend:


cd ../backend
npm run dev
Start the frontend:


cd ../frontend
npm start
Open your browser and navigate to http://localhost:3000 to view the app.


Contributing
Contributions are welcome! Follow these steps to contribute:

Fork the repository.
Create a branch for your feature or bug fix:


git checkout -b feature/YourFeatureName
Commit your changes:


git commit -m "Add your message here"
Push to your branch:


git push origin feature/YourFeatureName
Open a pull request.
Contact
Arvind Goud
GitHub: Arvind7Goud
Project Link: Job Portal Repository
