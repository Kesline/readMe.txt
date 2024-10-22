Student Advice Platform

Deployed Links:
Website: https://student-advice-post-server.onrender.com
Client Repo
Server Repo
API Endpoints:
Create Question: POST https://student-advice-post-server.onrender.com/api/questions
Create Post: POST https://student-advice-post-server.onrender.com/api/posts
Login: POST https://student-advice-post-server.onrender.com/api/login
Fetch Posts: GET https://student-advice-post-server.onrender.com/api/posts
Local Dev Endpoints:
Create Post: POST http://localhost:5001/api/posts
Login: POST http://localhost:5001/api/login
Capstone: Step Six - Document Your Project

Time Estimate: 2-3 hours

Project Overview:
This is a platform for students to ask and answer academic-related questions anonymously if desired. Users can create posts, log in, and browse through advice provided by others. The platform aims to facilitate student collaboration and create an online academic community.

Features:
User Registration & Login
Why: To allow students to have a personalized experience where they can log in, create posts, and respond to others.
Post Creation (Questions/Answers)
Why: Enables users to share their academic challenges and solutions in a structured way. Posts include both questions and helpful advice for others.
View Posts
Why: To allow browsing of all submitted posts, which encourages engagement within the platform.
Running Tests:
To test this platform, use tools like Postman or integrate with testing frameworks (e.g., Jest for JavaScript). For backend API endpoints, Postman can be used to simulate different API calls such as POST, GET, LOGIN.

User Flow:
Sign Up / Log In:
The user starts by either creating an account or logging in to their existing one.
Create Post:
Once logged in, the user can create a new post, sharing their academic queries or advice.
Browse Posts:
Users can scroll through all posts, offering advice or learning from others.
API Documentation:
Login API: Authenticates the user based on their credentials.
Post Creation: Allows users to submit new posts with content and titles.
Get Posts: Returns all the posts available on the platform.
Technology Stack:
Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
API Testing: Postman
Deployment: Render for backend